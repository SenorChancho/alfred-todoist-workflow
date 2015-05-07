alfred-todoist-workflow
=======================

##Usage
+ `tdconfig` Configure Todoist API token
+ `td t` Show tasks due today, click to complete
+ `td q [query]` Show tasks for the query, click to complete
+ `td a [task]` Add a new task with no due to the __Inbox__ or an existing project
+ `td a [task] due` Add a new task with a due to the __Inbox__ or an existing project

##Examples
+  td a go to store - adds task with no due
+  td a go to store tomorrow - add task due tomorrow
+  td a go to store monday - add task due on monday
+  currently does not support adding tasks with dates like "td a go to store may 15"
