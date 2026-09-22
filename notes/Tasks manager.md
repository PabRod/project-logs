Here we list some useful prompts for managing tasks.
## Urgent tasks
Overdue and due soon.
```tasks
status.type is not DONE

(due on or before this week) OR (due this or next week)
```
## Top priority tasks
Show just the top 3.
```tasks
status.type is not DONE
sort by priority
limit 3
```


## Open tasks
```tasks
status.type is not DONE
short mode
sort by due date
```
## Recently closed tasks
Tasks closed in the last week.
```tasks
status.type is DONE
sort by done date
(done this week or last week)
```
