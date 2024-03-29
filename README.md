# Проект 2. Разведывательный анализ данных

### Цели и задачи проекта:
* Анализ и первичная обработка данных
* Отбор признаков для последующего моделирования
* Отчет по итогам проделанной работы

### Краткая информация о данных:
Данные представляют собой 395 наблюдений и 29 признаков. Целевой переменной является *score*, где собраны итоговые баллы учащихся за гос. экзамен по математике.
Оснавная часть данных - категориальные признаки. Практически все переменные содержат пропуски, что потребовало основательной работы по их устранению. Выбросы найдены лишь в двух признаках *Fedu* и *famrel*.

### Этапы работы над проектом:
1) Первичный осмотр данных
2) Оптимизация использования памяти
3) Работа с пропусками
* дихотомические переменные
* порядковые переменные
* номинальные переменные
* числовые признаки
4) Выбор признаков для модели
* анализ номинативных переменных
* анализ иных переменных
* корреляционный анализ
5) Выводы

### Ответы на вопросы:

**1. Какова была моя роль в команде?**
* Ведущей! (честно говоря, не понял, о какой команде речь)

**2. Какой частью своей работы вы остались особенно довольны?**
* Работа с пропусками: применил несколько разных imputation-методов, использовал библиотку sklearn, до которой мы еще не дошли в курсе;
* Корреляционный анализ и сделанные на его основе выводы.

**3. Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?**
* Не всегда получалось визуализировать данные, как хотелось бы. Здесь обнаружил у себя проблемы при создании необходимых функций;
* Не понял, по какому принципу нужно отбирать признаки для модели. Использовал коэф. корреляции признаков с target, но все они не превышали 0.25, что описывается как очень слабая корреляция. Скорее всего, это неверный подход;
* Не совсем понял смысл теста Стьюдента для определения статистической разницы в распределении баллов по номинативным признакам. Пробелы в знаниях по статистике.

**4. Что интересного и полезного вы узнали в этом модуле?**
* Получил базовые знания в статистике (нормальное распределение, распр. Стьюдента, дов. интрвал, ЦПТ, тестирование гипотез);
* В ходе работы над итоговым проектом самостоятельно узнал массу нового (библиотека sklearn, разные методы работы с пропусками, pipeline & columntransformer, OneHotEncoder & get_dummies);
* Получил представление о том, как должен выглядеть грамотный EDA.

**5. Что является вашим главным результатом при прохождении этого проекта?**
* Преодолел все трудности, с которыми столкнулся в ходе прохождения модуля и выполнения итогового проекта;
* Сделал значительный шаг на пути к профессии DS.

**6. Какие навыки вы уже можете применить в текущей деятельности?**
* Загрузить данные в библиотеку Pandas;
* Почистить и преобразовать эти данные;
* Провести первичный анализ и сделать выводы;
* Отобрать переменные для модели машинного обучения.

**7. Планируете ли вы дополнительно изучать материалы по теме проекта?**
* Если речь о конкретном проекте UNICEF - нет, не планирую;
* Если речь в целом о EDA, data cleaning, ML etc. - конечно планирую и изучаю.

