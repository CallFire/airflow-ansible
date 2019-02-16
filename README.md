Operators:
* AnsibleOperator
* AnsiblePlaybookOperator
* AnsibleInventoryOperator
* AnsibleLintOperator

Executors:
* AnsibleTaskExecutor<CeleryExecutor> (https://github.com/apache/airflow/blob/master/airflow/executors/celery_executor.py)

Backend:
* DAGTaskQueueManager (https://github.com/ansible/ansible/blob/devel/lib/ansible/executor/task_queue_manager.py)
* XComPlayContext (https://github.com/ansible/ansible/blob/devel/lib/ansible/playbook/play_context.py)
