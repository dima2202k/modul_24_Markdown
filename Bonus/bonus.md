# Акторы

Пользователь, система.

*Цель:* я как клиент, хочу получить бонусы при заказе, чтобы тратить их на следующие заказы.

# Сценарии

## **Основной сценарий:**

1. При оплате пользователь вводит количество бонусов, которое он хочет потратить на заказ.

2. Система учитывает количество бонусов, при оплате заказа.

## **Альтернативный сценарий:**

2. При оплате пользователь указывает большее количество бонусов, чем у него имеется в личном кабинете.

3. Система устанавливает сумму бонусов для списания равную всем бонусам клиента.

4. Переход на п.2 основного сценария.

## **Исключение:**

2. При оплате пользователь вводит большее количество бонусов, чем сумма заказа.

3. Система не проводит оплату такого заказа и выводит ошибку.