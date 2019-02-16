Operators:
* AnsibleOperator
* AnsiblePlaybookOperator
* AnsibleInventoryOperator
* AnsibleLintOperator

Executors:
* AnsibleTaskExecutor

Backend:
* DAGTaskQueueManager (https://github.com/ansible/ansible/blob/devel/lib/ansible/executor/task_queue_manager.py)
* XComPlayContext (https://github.com/ansible/ansible/blob/devel/lib/ansible/playbook/play_context.py)
