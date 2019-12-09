# PWMS: Projects & Works Management System
With DDD(Domain-Driven Design) and mORMot (an amazing framework by Synopse)

This is an example to design and implement a real application through DDD (Domain-Driven Design and mORMot).


## Introducing the system: the initial requeriments
I want to develop a software to estimate projects, and break them into tasks. Besides, I should be able to estimate the time to complete these tasks. I should be able to impute works done on a task (and the time invested in doing it), too.

So, with this new software, I must be able to:
- Define a project and break it into tasks.
- Define works done (related to a task).
- Generate “timesheets” (estimated time, invested time...), to budget them, or to invoice them, or to check the time invested in them.
- Generate a workday “sheets” (with the invested times on), to report the workday of an employee.

## The Model of the “Projects&Works” domain
You can see here the class diagram design.

## Applications
I define this four user-level application functions (to assign to a four application layer classes):
- To define projects (to create projects, related tasks, and estimate them)
- To add works (to impute works done related to a task)
- To generate the WorkDay timesheets
- To check the related times of a given project.

## Repositories


## Dependencies
mORMot framework by Synopse:
https://synopse.info/fossil/wiki?name=SQLite3+Framework
