# Требования к проекту
# Содержание
[1. Введение](#Введение)<br/>
&nbsp;&nbsp;[1.1 Назначение](#Назначение)<br/>
&nbsp;&nbsp;[1.2  Бизнес-требования](#Бизнес-требования)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.1  Исходные данные](#Исходные-данные)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.2  Возможности бизнеса](#Возможности-бизнеса)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.3  Границы проекта](#Границы-проекта)<br/>
&nbsp;&nbsp;[1.3  Аналоги проекта](#Аналоги-проекта)<br/>
[2.Требования пользователя](#Требования-пользователя)<br/>
&nbsp;&nbsp;[2.1 Программные интерфейсы](#Программные-интерфейсы)<br/>
&nbsp;&nbsp;[2.2 Интерфейс пользователя](#Интерфейс-пользователя)<br/>
&nbsp;&nbsp;[2.3 Характеристики пользователей](#Характеристики-пользователей)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3.1 Классы пользователей](#Классы-пользователей)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3.2 Аудитория приложения](#Аудитория-приложения)<br/>
[3.Системные требования](#Системные-требования)<br/>
&nbsp;&nbsp;[3.1 Функциональные требования](#Функциональные-требования)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.1.1 Основные функции](#Основные-функции)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;;[3.1.2 Ограничения и исключения](#Ограничения-и-исключения)<br/>
&nbsp;&nbsp;[3.1 Нефункциональные требования](#Нефункциональные-требования)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.2.1 Аттрибуты качества](#Аттрибуты-качества)<br/>

<a name="Введение"></a>
# 1. Введение

<a name="Назначение"></a>
## 1.1 Назначение
Разрабатываемое приложение носит название “Каталог фильмов” и предназначено для предоставления информации о кинематографических произведениях по выбранным параметрам.

<a name="Бизнес-требования"></a>
## 1.2 Бизнес-требования

<a name="Исходные-данные"></a>
### 1.2.1 Исходные данные
Киноленты в настоящий момент являются очень распространенным способом проведения досуга, несмотря на наличие разнообразных видов отдыха и развлечений. Большое количество жанров кинометографии позволяют пользователю выбрать произведение на любой вкус. На сегодняшний день существует множество приложений и web-сайтов, которые специализируются на предоставлении информации о фильмах, в том числе и о их характеристиках. Однако, поиск необходимой киноленты, используя, например, специализированный web-сайт может занимать большое количество времени, а также требует наличия web-браузера. Таким образом, данные проблемы использования подобных проектов постарается решить данное настольное приложение.

<a name="Возмоности-бизнеса"></a>
### 1.2.2 Возможности бизнеса
Пользователи, интересующиеся кинематографией и использующие разрабатываемое приложение, будут всегда иметь “под рукой” удобное настольное приложение, позволяющее быстро и комфортно находить интересующие его киноленты по выбранным параметрам, видеть самые последние премьеры, в том числе и узнать их характеристики (качество изображения, длительность, актерский состав, руководящий состав, краткий сюжет и т.д.), а также добавлять заинтерисующие киноленты в личный каталог. Данное приложение может быть использовано, например, в кинотеатрах для привлечение большего количество посетителей и, соответственно, увеличения дохода организации.

<a name="Границы-проекта"></a>
### 1.2.3 Границы проекта
"Каталог фильмов" обеспечит предоставление списка необходимых кинолент, найденных по заданным параметрам и категориям и, в том числе, автоматическое предоставление премьер, а также добавление произведений в личный каталог для авторизованных пользователей.

<a name="Аналоги-проекта"></a>
## 1.3 Аналоги проекта
В качестве аналогов можно выделить несколько следующих настольных приложения:</br>
1. Zona - </br>
2. MediaGet – </br>
3. Shareman - </br>

<a name="Требования-пользователя"></a>
# 2 Требования пользователя

<a name="Программные-интерфейсы"></a>
# 2.1 Программные интерфейсы
Для разработки данного приложения используется:</br>
1. Язык программирования – Java (java development kit 12.0.2);</br>
2. Среда разработки - IntelliJ IDEA Community Edition 2019.2.1;</br>
3. GUI будет разработан с помощью JavaFX, а также с использованием графического инструмента Scene Builder.</br>
Все функциональные элементы управления GUI проекта оснащены текстовым описанием, представляющие собой простые пояснения к использованию. 

<a name="Интерфейс-пользователя"></a>
## 2.2 Интерфейс пользователя
При открытии приложения пользователь предстоит увидеть базовое окно, в котором будут предоставлены премьеры кинематографа( в виде иконок).
![Главноеокно](Mockups/Главное-окно.PNG)
При нажатии на иконку определенного фильма откроется окно описания этой картины.

Для создания личного каталога пользователя необходимо авторизоваться в системе с помощью электронной почты и пароля.

Пользователи, авторизованные в системе, могут добавлять произведения в личный каталог, а также отмечать их как просмотренные.

Для входа уже зарегистрированных пользователей вход в систему можео произвести с помощью следующего окна.

Для регистрации пользователям будет предложено следующее окно.

Также в случае,если пользователь забыл свой пароль, может его напомнить с помощью следующего окна.

<a name="Характеристики-пользователей"></a>
## 2.3 Характеристики пользователей

<a name="Классы-пользователей"></a>
### 2.3.1 Классы пользователей
Приложение предоставляет весь свой функционал абсолютно всем пользователям и является удобным и комфортным для всех классов пользователей, вне зависимости от их интересов и образования. Также данную систему могут использовать как и незарегистрированные пользователи, так и зарегистрированные. Однако только вторые имеют возможность добавлять произведения в свой личный каталог и редактировать его.

<a name="Аудитория-приложения"></a>
### 2.3.2 Аудитория приложения
В качестве целевой аудитории приложения могут выступать люди любой возрастной категории, интересующиеся кинематографией вне зависимости от их уровня информационного образования.

<a name="Системные-требования"></a>
# 3 Системные требования

<a name="Функциональные-требования"></a>
## 3.1 Функциональные требования

<a name="Основные-функции"></a>
### 3.1.1 Основные функции
Разрабатываемое приложение должно обеспечивать возможность выполнения следующих функций:</br>
1. Авторизация пользователей, если это необходимо;</br>
2. Ввод предоставленных параметров для уточнения поиска;</br>
3. Предоставление текущий премьер;</br>
4. Предоставление информации о выбранном произведении;</br>
5. Получение списка кинолент, соответствующих заданным параметрам;</br>
6. Возможность добавления произведений в личный каталог;</br>
7. Возможность редактирования личного каталога пользователя;</br>
8. Возможность выхода из своего профиля.

<a name="Ограничения-и-исключения"></a>
### 3.1.2 Ограничения и исключения
1. Приложение не работает без достука к Интернету.</br>
2. Функционал связанный с работы в личном каталоге доступен лишь для авторизованных пользователей.

<a name="Нефункциональные-требования"></a>
## 3.2 Нефункциональные требования

<a name="Аттрибуты-качества"></a>
### 3.2.1 Аттрибуты качества
1. Личный каталог пользователя будет достаточно надёжным от посторонныих лиц, так как одним из пунктов доступа к системе будет прохождение авторизации.
2. Приложение имеет только одно главное окно, что упрощает ориентацию в проекте.
3. Приложение будет комфортно как и пользователям, ранее использовавшим проекты подобного формата, так и новичкам данного жанра.

