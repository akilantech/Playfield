## Steps of distributed job scheduler
* Multiple worker nodes pull tasks from a central coordinator.
* Tasks have priorities and execution deadlines.
* The scheduler should support re-queuing failed tasks.
* Workers should poll tasks efficiently without overloading the coordinator.
* You can assume in-memory storage, but design in a way that can scale.
