# testDiary


> MyDiary is an online journal where you can
> pen down your thoughts and feelings

## Running the app locally
  1. Clone the repository:
  ```
  git clone https://github.com/fuadazhar73/DiarySample
  ```
  2. Navigate into the cloned repository folder

  3. Install dependencies:
  ```
  $ npm install
  ```
  4. run `npm run start` to start the server

  5. visit `http://localhost:8000`



## App's API documentation
  visit `http://localhost:8000/api-docs` 

## App's API endpoints

| Functionality       |  HTTP Method  |         API endpoints                |
| ------------------- | --------------|------------------------------------- |
| Login               | POST          | /api/v1/auth/login                   |
| Registration        | POST          | /api/v1/auth/signup                  |
| Update Profile      | PUT           | /api/v1/auth/update                  |
| Add entry           | POST          | /api/v1/entries                      |
| Update entry        | PUT           | /api/v1/entries/&lt;entryId&gt;      |
| Entry List          | GET           | /api/v1/entries                      |
| Entry Detail        | GET           | /api/v1/entries/&lt;entryId&gt;      |
| Delete entry        | DELETE        | /api/v1/entries/&lt;entryId&gt;      |
| Add/update reminder | POST          | /api/v1/reminders                    |
| Delete reminder     | DELETE        | /api/v1/reminders/&lt;remindersId&gt;|



