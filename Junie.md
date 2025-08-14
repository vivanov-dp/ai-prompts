# Junie prompts

## Plan a task

Consider the following task:

....

Write a structured plan to perform the task in a .md file in the `tasks/` folder.
The file should contain a list of logically ordered tasks, grouped into stages for implementation.
Every stage should have a number and contain no more than a few tasks that can be logically done as a unit.
It is ok the plan to contain only one stage if it's small enough.
There should be a placeholder checkbox before each task, to be checked off when completed.

------

Write a structured plan to perform the following task in a .md file in the `tasks/` folder:

{
  ...
  ...
}

The file with the plan should contain a list of logically ordered sub-tasks, grouped into stages for implementation.
Every stage should have a number and contain no more than a few tasks that can be logically done as a unit.
It is ok the plan to contain only one stage if it's small enough.
There should be a placeholder checkbox before each sub-task, to be checked off when completed.

## Execute stage of planned task

Analyze the list of tasks in `tasks/auth-login.md` and consider context stored at the of the file.
Perform the items listed under Stage 3 and mark them as done.
Preserve context by adding it to the end of the file, so that you can read it back and continue working on the tasks in the future.

-----

Analyze the list of tasks in `tasks/auth-login.md` and consider context stored at the end of the file.
Determine the first stage that needs to be completed and perform it.
Preserve context by adding it to the end of the file and mention the number of the stage that was just completed, 
so that you can read it back and continue working on the tasks in the future.
