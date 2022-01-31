# Ecommerce
This site is being created using Vue.js in frontend and Django in backend.

`dj_ecom_second_mediusware` is the root directory, where all the project requirements exists for both frontend and backend.

`src` is the project directory where all the code exists.

#### Step 1. To get started first clone the repo, by this command
```shell
git clone https://github.com/Oytizzo/dj_ecom_second_mediusware.git
```

#### Step 2. Then go to the root directory where .git exist and open `git bash` and checkout to `dev.1.0.0` branch
```shell
git checkout dev.1.0.0
```

#### Step 3. After checking out to the latest `dev.1.0.0` branch, open `terminal` and execute the commands below
```shell
pipenv install
```
```shell
pipenv shell
```

#### Step 4. Open another `terminal` in the same directory and execute the commands below
```shell
npm install
```
```shell
npm run watch
```

#### Step 5. Create a superuser for login. Go to the `src` directory and run
For windows,
```shell
python manage.py createsuperuser
```
For linux or Mac,
```shell
python3 manage.py createsuperuser
```
Give the superuser name, email and password in terminal to register superuser.

#### Step 6. Then go to the `src` directory where manage.py exists and run
For windows,
```shell
python manage.py runserver
```
For linux or Mac,
```shell
python3 manage.py runserver
```
