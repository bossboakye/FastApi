# FastApi This is a quick guide into getting started with FastAPI (Guide by Very Academy on YouTube)

* Create a .env file with the below entries:
```php
DATABASE_URL=postgresql+psycopg2://{DB_USER}:{DB_PASSWORD}@db:5432/{DB_NAME}
DB_USER=
DB_PASSWORD=
DB_NAME=
PGADMIN_EMAIL=
PGADMIN_PASSWORD=
```
* Install the dependencies (preferably in a Virtual environment)
RUN pip3 install -r requirements.txt

* RUN docker-compose run app alembic revision --autogenerate -m "New Migration" (For your migrations)

* RUN docker-compose run app alembic upgrade head (To commit the Migration)

* RUN docker-compose build 

* RUN docker-compose up
