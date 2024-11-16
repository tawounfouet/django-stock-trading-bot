

```sh
celery -A cfehome worker

celery -A cfehome worker -l INFO


celery -A cfehome beat
#celery -A cfehome worker info --beat
celery -A cfehome worker --beat -l info