OozieActions
============

1. File System Action
2. SSH Action
3. Java Action
4. Hive Action
5. Sqoop Action
6. Pig Action
7. MR Action

Fork and Join in #5 and #6

Coordinator is set to run every day at 5am UTC

Submit coordinator: oozie job -oozie http://<oozie_host>:11000/oozie -config <your_path>/coordinatorApp/coordinator.properties -run

Run workflow once: oozie job -oozie http://<oozie_host>:11000/oozie -config <your_path>/coordinatorApp/workflowApp/job.properties -run
