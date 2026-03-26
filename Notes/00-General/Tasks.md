# Todoist Tasks

```todoist  
filter: "today | overdue"  
```

# Compiled Tasks

```tasks
# Only tasks that are not done, that is, which begin like this (but without the quotes):
#   '- [ ] ' or
#   '* [ ] ' or
#   '1. [ ] '
# Indented tasks are supported, but only single-line tasks.

# Restrict to at most 100 tasks.
# If you ask Tasks to display many hundreds or thousands of tasks,
# Obsidian's editing performance really slows down.
limit 100

#path includes 03-Work

# Group and sort the output:
group by root
group by path
sort by due reverse
sort by description

# Optionally, ask Tasks to explain how it interpreted this query:
explain
```
