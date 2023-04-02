# Автоматизируемые сценарии: 
1.	Переход по страницам от главной страницы сайта до формы для заполнения. 
2.	Заполнение формы:
    - позитивный кейс:
       - заполнение поля "Имя"
       - заполнение поля "Телефон"
       - нажатие кнопки "Записаться"
      
    - негативные кейсы 

# Инструменты
1.  Gradle  - система сборки, удобная для прогона автотестов.
2.	JUnit – широко используемый фреймворк для автотестов
3.	Faker – позволит автоматически создавать данные для тестов
4.	Selenide – удобный экономичный фреймворк для UI тестов
5.	Docker – позволяет запускать контейнер с SQL 
6.	Allure – простая понятная система репортинга

# Перечень необходимых разрешений, данных и доступов
1. Необходим генератор данных пользователей
2. Нужен тестовый режим в системе/заглушки, которые позволят "отправлять" заявку
3. Нужны данные о реальном поведении пользователей от аналитиков

# Перечень и описание возможных рисков при автоматизации
1. Изменится структура сайта и тесты устареют
2. Написание автотестов займёт больше времени, чем ручной прогон.

# Перечень необходимых специалистов для автоматизации
1. Специалист по автоматизации
2. Аналитик
3. Разработчик (для написания SUT)

# Интервальная оценка с учётом рисков в часах
1. Прохождение тестового сценария вручную - 15 минут
2. Анализ данных пользовательского поведения, полученных от аналитиков  - 1 час
3. Настройка тестового окружения - 2 часа
3а. Ожидание пока разработчики сделают тестовый режим для системы - 2 дня.
4. Написание дата-классов - 2 часа
5. Настройка SQL - 1 час
6. Написание Page Objects - 8 часов
7. Написание позитивного теста - 1 час
8. Написание негативных кейсов - 4 часа 
9. Настройка репортинга - 1 час
10. Подготовка отчётов по тестированию - 3 часа. 

*Итого*  
24 часа работы тест-инженера + 2 дня разработчикам. 
