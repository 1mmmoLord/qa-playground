**Требования:**
- Пользователь может войти по Email и Password.
- Пользователь может запросить восстановление пароля.
- При неправильных данных система отклоняет авторизацию.
- Заблокированный пользователь не может войти.
- После успешного входа пользователь попадает на Dashboard.


**Твоя задача:**
- Один Use Case.
- Actor и Preconditions.
- Main Flow.
- Минимум 2 Alternative Flows.
- Минимум 2 Exception Flows.
- Postconditions.

##
- Use Case - login 
- Actor - registered user
- Preconditions - user, on login page
- Main flow - User enter correct login and password of non banned account on Login page, press button and transfer to Dashboard
**Alternative flow**
- 1. User enter corret login and password on login page and after pressing sumbit button he doesnt login because his account banned
- 2. User doesnt remember his password and he presses forgot password button makes new password and logins successful
**Exception flow**
- 1. User enter only login and press sumbit button, after that he gets message "password is required"
- 2. User enter only password without login and he gets message "login is required"
- Postconditions - 
- Successful login: user authenticated, session created.
- Unsuccessful login: user not authenticated, no session created.
- Password recovery: recovery request accepted by the system.

