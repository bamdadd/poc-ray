# POC for Ray

Run main.py or actors.py and check http://127.0.0.1:8265 

- Graph requires Graphna and Prometheus to be running. which is slightly more setup than DASK. where you get those out of the box.
- While the jobs are running you can run to see the tasks
    ```bash
    ray summary tasks
    ```
