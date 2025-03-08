---
icon: simple/matrix
---
# MITRE ATT&CK
## 🔹 Что такое MITRE ATT&CK?

> **MITRE ATT&CK (Adversarial Tactics, Techniques, and Common Knowledge)** — это база знаний, описывающая тактики, техники и процедуры (TTPs), используемые злоумышленниками на разных стадиях кибератак.

Она используется в **SOC, Threat Intelligence, Red Teaming и Blue Teaming** для анализа угроз, выявления атак и построения защитных механизмов.

📌 **Официальный сайт:** https://attack.mitre.org

## 🔹 Структура MITER ATTACK

**ATT&CK Matrix** состоит из **14 тактик** (Tactics), внутри которых сгруппированы **техники и под-техники** (Techniques & Sub-techniques).

📌 **Пример:**  
Тактика: **Execution (Исполнение кода)**  
Техника: **T1059 - Command and Scripting Interpreter**  
Под-техника: **T1059.001 - PowerShell**

## 🔹 Номера техник для собеседований!

**📌 1. Reconnaissance (Разведка)**

- **T1595 - Active Scanning (Активное сканирование)**

- **T1592 - Gather Victim Host Information (Сбор информации о хосте жертвы)**  
    💡 Злоумышленник собирает данные о системе перед атакой.

**📌 2. Resource Development (Развитие ресурсов)**

- **T1583 - Acquire Infrastructure (Приобретение инфраструктуры)**  
    💡 Атакующий подготавливает домены, сервера, учётные записи.

**📌 3. Initial Access (Первичный доступ)**

- **T1566 - Phishing (Фишинг)**

- **T1190 - Exploit Public-Facing Application (Эксплуатация веб-приложений)**  
    💡 Взлом через фишинг или уязвимость в системе.

**📌 4. Execution (Исполнение кода)**

- **T1059 - Command and Scripting Interpreter (Командная строка и интерпретаторы скриптов)**

- **T1204 - User Execution (Исполнение через пользователя)**  
    💡 Запуск вредоносного кода.

**📌 5. Persistence (Закрепление в системе)**

- **T1547 - Boot or Logon Autostart Execution (Автозапуск при загрузке или входе в систему)**

- **T1136 - Create Account (Создание учетной записи)**  
    💡 Злоумышленник создает бэкдор или автозапуск для персистентности.

**📌 6. Privilege Escalation (Повышение привилегий)**

- **T1068 - Exploitation for Privilege Escalation (Эксплуатация уязвимостей для повышения привилегий)**  
    💡 Получение админских прав.

**📌 7. Defense Evasion (Обход защитных механизмов)**

- **T1036 - Masquerading (Маскировка)**

- **T1070 - Indicator Removal on Host (Удаление индикаторов компрометации)**  
    💡 Скрытие вредоносного ПО.

**📌 8. Credential Access (Кража учетных данных)**

- **T1003 - OS Credential Dumping (Дамп учетных данных Windows)**

- **T1555 - Credentials from Password Stores (Извлечение паролей из хранилищ)**  
    💡 Сбор паролей и учетных данных.

**📌 9. Discovery (Разведка внутри сети)**

- **T1087 - Account Discovery (Разведка учетных записей)**

- **T1018 - Remote System Discovery (Поиск удаленных систем)**  
    💡 Поиск пользователей, компьютеров, сетей.

**📌 10. Lateral Movement (Перемещение по сети)**

- **T1021 - Remote Services (Использование удаленных сервисов)**

- **T1570 - Lateral Tool Transfer (Передача инструментов для перемещения)**  
    💡 Злоумышленник перемещается на другие машины.

**📌 11. Collection (Сбор данных)**

- **T1114 - Email Collection (Сбор почтовых данных)**

- **T1056 - Input Capture (Перехват ввода, кейлоггеры)**  
    💡 Сбор файлов, паролей, переписки.

**📌 12. Command and Control (Управление и контроль)**

- **T1071 - Application Layer Protocol (Протоколы прикладного уровня, HTTP, DNS)**

- **T1095 - Non-Application Layer Protocol (Скрытый трафик на L3/L4 уровнях)**  
    💡 Управление зараженной системой.

**📌 13. Exfiltration (Вывод данных)**

- **T1041 - Exfiltration Over C2 Channel (Вывод через C2-сервер)**

- **T1567 - Exfiltration Over Web Service (Вывод через облачные сервисы, FTP, Telegram)**  
    💡 Воровство данных.

**📌 14. Impact (Воздействие)**

- **T1486 - Data Encrypted for Impact (Шифрование данных, Ransomware)**

- **T1565 - Data Manipulation (Манипуляция данными, изменение логов, файлов)**  
    💡 Уничтожение данных или шифрование.

Не обязательно заучивать их все - главное знать основные и уметь рассказать о них. В реальной работе можно будет спокойно обратить к самой MITRE ATTACK через сайт. Но ориентироваться в любом случае нужно ;)