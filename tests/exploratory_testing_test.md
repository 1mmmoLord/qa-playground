Представь, что тебе дали интернет-магазин с тремя функциями:
- Login
- Product Search
- Add to Cart
Твоя задача — составить Test Charter для Exploratory Testing.

Условия:
- Выбери одну из трёх функций.
- Определи цель тестирования.
- Укажи, что именно будешь исследовать.
- Придумай минимум 8 Test Ideas.
- Для каждой идеи напиши, какое неожиданное поведение или дефект ты пытаешься обнаружить.

**login**
- Test charter - verify the correct behavior  of the login page
- Scope - email field, password field, login button, forgot password button
**Test Ideas**
- 1. Entering correct email and password, and click login button. Unexpected behavior - Login button doesnt work, staying on login page.
- 2. Entering correct email but incorrect password, and click login button. Unexpected behavior - no messsage about incorrect password.
- 3. Entering incorrect email but correct password and click login button. Unexpected behavior - no massage about incorrect email.
- 4. Stay both field empty, and click login button. Unexpected behavior - no message about required email and password.
- 5. Click password forget button. Unexpected behavior - nothing happens, staying on login page.
- 6. Entering wrong password but correct email, click login button. Unexpected behavior - No message about invalid password.
- 7. Entering wrong email but correct password, click login button. Unexpected behavior - No message about invalid email.
- 8. After login pressing backpage button. Unexpected behavior - nothing happens.