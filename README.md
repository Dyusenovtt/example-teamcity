# Домашнее задание к занятию 11 «Teamcity»

## 1. Подготовка инфраструктуры
Используем terraform и ansible для быстрого развертывания vm
<img width="974" height="479" alt="image" src="https://github.com/user-attachments/assets/6d84fc13-88d8-4a75-975c-9a51a7cf9ad5" />
<img width="1639" height="115" alt="image" src="https://github.com/user-attachments/assets/24dce76a-3cce-4d04-8ec4-4b1097478456" />
<img width="974" height="519" alt="image" src="https://github.com/user-attachments/assets/83a70a09-a1c8-4a4e-a030-761f02d0da66" />

## 2. Настройка сборки
<img width="974" height="689" alt="image" src="https://github.com/user-attachments/assets/6c3a4f86-f128-4a0e-8918-8c3ea66f1910" />
<img width="2276" height="1474" alt="image" src="https://github.com/user-attachments/assets/87b3fb43-5e54-4b56-94a3-9b49aef43eef" />
<img width="974" height="649" alt="image" src="https://github.com/user-attachments/assets/61d1d06b-1154-4846-834e-bd29d748ca25" />
<img width="974" height="460" alt="image" src="https://github.com/user-attachments/assets/a5a6ccb8-03b7-48d2-8b76-736cb892b9a0" />
<img width="974" height="567" alt="image" src="https://github.com/user-attachments/assets/8cb1de31-abc5-4402-a41e-eb4ea8615588" />


### 2.2 Maven Settings
- Загружен `settings.xml`
- В `pom.xml` обновлены ссылки на Nexus

## 3. Ветка Feature и тесты
- Ветка: `feature/add_reply`.
- Добавлен метод в `Welcomer` и тест 
- Сборка ветки прошла успешно
<img width="974" height="405" alt="image" src="https://github.com/user-attachments/assets/e86368e4-2d14-4fa1-b0ba-11d2e9f58d2d" />


## 4. Merge и артефакты
- Merge в master выполнен.
- **Artifact Paths**: Настроен путь `target/*.jar`.
- Сборка master прошла успешно, артефакт присутствует .
  <img width="974" height="662" alt="image" src="https://github.com/user-attachments/assets/95f9a5a0-13b1-47ab-ba31-dd15044e5ebd" />
  <img width="974" height="604" alt="image" src="https://github.com/user-attachments/assets/5f6fa1c4-62a1-447b-b2a6-bd894fa4cfaa" />



## 5. Версионирование конфигурации
- Включен `Versioned Settings`, конфигурация сохранена в репозиторий.
