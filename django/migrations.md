# Django: 마이그레이션

모델을 바꾼 뒤 `python manage.py makemigrations` → `python manage.py migrate`. 적용 상태는 `showmigrations`, 실제 SQL 은 `sqlmigrate app 0001` 로 확인한다.
