# Django: N+1 문제

FK 는 `select_related`, M2M/역참조는 `prefetch_related` 로 쿼리 수를 줄인다. `django-debug-toolbar` 로 쿼리 수를 확인하자.
