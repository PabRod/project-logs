Here we list some useful prompts for managing tasks.
## Moved to GitHub
Tasks promoted to a GitHub issue. Their status lives there now.
```tasks
status.name includes Moved to GitHub
short mode
```
## Urgent tasks
Overdue and due soon.
```tasks
not done

(due on or before this week) OR (due this or next week)

sort by due date
```
## Top priority tasks
Show just the top 3.
```tasks
not done
sort by priority
limit 3
```
## Open tasks
```tasks
not done
short mode
sort by due date
```
## Old tasks
Tasks created long ago and still open. Good candidates for being tagged as `cancelled`.
```tasks
not done
created date before last month
sort by created date
```
## Recently closed tasks
Tasks closed in the last week.
```tasks
status.type is DONE
sort by done date
(done this week or last week)
```

