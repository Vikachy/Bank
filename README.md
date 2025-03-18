Результат работы приложения до изменений:
![image](https://github.com/user-attachments/assets/c7b3b086-49e6-4aca-83fc-a5fe3875774d)

Результат работы приложения после изменений:
![image](https://github.com/user-attachments/assets/0b3eeaf4-e230-440b-bb97-bfd9db83bb8a)

Результат обозревателя тестов:
![image](https://github.com/user-attachments/assets/949df82e-b0c8-4ef4-aa96-79b97b9e2e87)

В ходе работы был создан проект Bank, содержащий класс BankAccount с методами Debit и Credit. Эти методы были протестированы с использованием модульных тестов в проекте BankTests. 
Были созданы следующие тестовые методы:

- Debit_WithValidAmount_UpdatesBalance — проверка корректности списания средств при допустимой сумме.

- Debit_WhenAmountIsLessThanZero_ShouldThrowArgumentOutOfRange — проверка выброса исключения при попытке списания отрицательной суммы.

- Debit_WhenAmountIsMoreThanBalance_ShouldThrowArgumentOutOfRange — проверка выброса исключения при попытке списания суммы, превышающей баланс.

Также был проведен рефакторинг кода метода Debit для улучшения читаемости и добавления более информативных сообщений об ошибках.
Успешное выполнение тестов:
- Тесты были успешно пройдены после исправления ошибки в методе Debit, где вместо вычитания суммы происходило ее добавление.
- Рефакторинг кода и добавление корректных проверок на выброс исключений улучшили качество кода.

Неуспешное выполнение тестов:
- Изначально тест Debit_WithValidAmount_UpdatesBalance не был пройден из-за ошибки в коде метода Debit. После исправления ошибки тест был успешно пройден.

## Выводы 
В ходе работы были успешно созданы и протестированы методы класса BankAccount с использованием модульных тестов.
Модульные тесты позволили выявить ошибку в логике метода Debit и убедиться в корректности его работы после исправления.
Рефакторинг кода и добавление информативных сообщений об ошибках улучшили качество и надежность кода.
Работа с модульными тестами в Microsoft Visual Studio показала их эффективность для автоматизированного тестирования программных модулей.



