>astro dev start

>astro dev stop

> astro dev bash

to use the airflow cli with astro 

without astro 

> docker ps

copy the container id of the web server container 

> docker exec -it <container id> /bin/bash 

Test just a task

`<dag id> <task id> <Date in the past>`

> astro dev run tasks test stock_market is_api_available 2025-01-01

Test the dag

`<dag id> <Date in the past>`

> astro dev run dags test stock_market 2025-01-01

## airflow commands

> airflow -h

> airflow db check

> airflow db clean

> airflow db export-archived

> airflow dags reserialize

ok, but where would I run this in fr8 infrastructure ? 

> airflow task test my_dag my_task ...

before running the whole dag, running just a task

> airflow cheat-sheet