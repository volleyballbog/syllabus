[Назад к главной странице курса](https://github.com/db2018ss/syllabus)

## 2. Теория нормализации

### Цель работы

Усвоение принципов и приемов нормализации схем отношений, приобретение умения выявлять и анализировать функциональные и многозначные зависимости между атрибутами отношения.

### Содержание контрольной работы

Предварительно ознакомиться: [материалы лекций по теории нормализации](http://aksenov.in/guap/db/lectures/doku.php?id=lectures:lecture3).

Контрольная работа заключается в закреплении материалов по теории нормализации [1, 2, 3] и состоит из 4 заданий, из которых одно представляет собой практическое упражнение, а три других имеют вид вопроса с несколькими вариантами ответа, из которых правилен только один.

Каждое задание сопровождается подсказкой, выделенной курсивом и объясняющей, каким методом следует воспользоваться при выполнении того или иного задания.

#### Задание 1

Первое задание заключается в декомпозиции отношения с заданной схемой (как правило, в низкой нормальной форме (далее - НФ)) и парой кортежей с реальными данными. Кортежи даны исключительно для лучшего представления о сути предметной области и в выполнении задания роли не играют.

Для отношения необходимо:

1. определить множество полностью нетривиальных функциональных зависимостей (далее - ФЗ);
2. вычислить потенциальный ключ (или несколько);
3. установить самую высокую НФ, в которой находится отношение;
4. при необходимости декомпозировать отношение без потерь.

Для каждого из полученных после декомпозиции отношений также выполняются шаги 3-4.

Каждое действие необходимо сопровождать пояснениями (например, нужно привести вычисление замыкания для множества атрибутов, составляющих ключ, привести обоснование нахождения отношения в той или иной НФ).

Пример первого задания приведен в образце [4], его выполнение рассмотрено в лекциях.

#### Задания 2-3

Задания 2 и 3 представляют собой вопросы с 4 вариантами ответа, касающиеся выявления и анализа функциональных зависимостей. В зависимости от номера варианта контрольной работы, типы заданий могут быть следующими:

* Даны заголовок отношения и множество ФЗ в нем. Определить, какое из 4 множеств атрибутов является для этого отношения ключом (пример задания приведен в образце [4]).
* Даны заголовок отношения и множество ФЗ в нем. Определить, какое из 4 множеств атрибутов функционально не определяет множество атрибутов Х.
* Дан заголовок отношения. Определить, для какого из 4 множеств ФЗ оно находится в BCNF (пример задания приведен в образце [4]).
* Даны заголовок отношения и множество ФЗ в нем. Определить, какой из 4 ФЗ оно гарантированно удовлетворяет.
* Даны заголовок отношения, один кортеж и две ФЗ в нем. Определить, какой из 4 кортежей может быть добавлен в отношение без нарушения ФЗ.

Каждый ответ необходимо сопровождать пояснениями, почему был выбран именно он.

#### Задание 4

Задание 4 представляет собой вопрос с 4 вариантами ответа, касающийся выявления и анализа многозначных зависимостей (далее - МЗ). В зависимости от номера варианта контрольной работы, типы задания могут быть следующими:

* Даны схема отношения и множество кортежей в нем. Определить, какой из 4 МЗ оно не удовлетворяет (пример задания приведен в образце [4]).
* Даны схема отношения и множество кортежей в нем. Определить, какой из 4 МЗ оно удовлетворяет.
* Даны схема отношения, два кортежа и две МЗ в нем. Определить, какой из 4 кортежей должен быть добавлен в отношение для соблюдения МЗ.

Ответ необходимо сопроводить пояснениями, почему был выбран именно он.

### Выполнение и сдача контрольной работы

Задание по контрольной работе выдается группе в фиксированную заранее оглашенную дату и представляет собой лист формата А5, выдаваемый каждому студенту лично в руки. 

Контрольная работа выполняется аудиторно в течение 45-50 минут. При выполнении контрольной работы можно пользоваться конспектом и другими материалами, но нельзя общаться с другими людьми (за исключением преподавателя, к которому можно обращаться за уточняющими вопросами).

Каждое действие при выполнении всех заданий необходимо документировать, то есть давать пояснения к выбранному ответу или принятому решению. При отсутствии пояснения задание не засчитывается, даже если выбран правильный ответ.

Контрольная работа считается сданной, если правильно выполнено задание 1, а также два из трех заданий 2-4. При этом допускаются и прощаются небольшие недочеты при выполнении задания 1, не влияющие на правильность декомпозиции.

Если правильно выполнены все задания, а задание 1 выполнено без недочетов, контрольная работа считается сданной с отличием, что учитывается при аттестации.

Если студент не смог присутствовать в день написания контрольной работы, то она считается несданной. При возникновении спорной ситуации при аттестации данного студента ему будет предоставлен шанс ее написания в конце семестра.

### Вспомогательные материалы

1. [Проектирование реляционных баз данных с использованием нормализации](http://citforum.ru/database/osbd/glava_23.shtml)
2. [Нормальные формы отношений](http://citforum.ru/database/dblearn/dblearn06.shtml)
3. [Нормальные формы более высоких порядков](http://citforum.ru/database/dblearn/dblearn07.shtml)
4. [Образец задания по контрольной работе](https://www.dropbox.com/s/kirfsqfq5a7lg3g/kr2example.pdf?dl=0)

[Назад к главной странице курса](https://github.com/db2018ss/syllabus)
