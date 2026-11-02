## Требования:
1. A NEW order can be paid or cancelled.
2. A PAID order can be shipped.
3. A SHIPPED order can be delivered.
4. A CANCELLED order cannot change its state.
5. A DELIVERED order cannot change its state.
6. Shipping is not allowed before payment.
7. Delivery is not allowed before shipping.
## Tasks:
1. Create a State Transition Table.
2. List all Valid Transitions.
3. List all Invalid Transitions.
4. Create test cases for these transitions.
5. Explain why you selected this number of test cases.
## Solution
1. img/state_table.jpg
2. new to paid, mew to cancelled, paid to shipping, shipping to delivered
3. all other
4. Мы создаем список с характеристиками(например new может прыгнуть только paid и canceld) после чего прогоняем различные варианты через цикл где идет проверка на валидность transition.
