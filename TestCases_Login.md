| Test Case ID  | Title                 | Steps                                             | Expected Result                             | Type     |
| ------------- | --------------------- | ------------------------------------------------- | ------------------------------------------- | -------- |
| TC\_Login\_01 | Login with valid data | Click Login → Enter valid user/pass → Click Login | User gets logged in                         | Positive |
| TC\_Login\_02 | Login with blank data | Click Login → Leave fields empty → Click Login    | Show alert “Please fill out Username/Pass.” | Negative |
| TC\_Login\_03 | Wrong credentials     | Enter invalid user/pass → Click Login             | Show error message                          | Negative |
| TC\_Login\_04 | SQL Injection Test    | Enter `' OR 1=1 --` as username                   | Should not allow login                      | Security |
