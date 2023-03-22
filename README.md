# ConfPoster
Афиша по событиям, конференциям и другим мероприятиям. С возможностью выбрать роль, а также указать необходимость в бронировании отеля.

Ежегодно проводятся научные конференции по различным направлениям развития науки. Для проведения конференции необходимо подать заявку и стать участником. Справочник персоналий участников конференции (фамилия, имя, отчество, ученая степень, ученое звание, место работы, кафедра (отдел), должность, страна, город, почтовый индекс, адрес, рабочий телефон, домашний телефон, e-mail), и информацию, связанную с участием в конференции (докладчик или участник, дата поступления заявки, тема доклада, отметка о поступлении тезисов, дата рассылки приглашения, дата поступления орг.взноса, размер поступившего орг.взноса, дата приезда, дата отъезда, потребность в гостинице).

В различных городах планируется проведение научных конференций по различным тематикам, но каждая конференция имеет строго определенную научную тематику. Ученые, живущие в разных городах, участвуют в этих конференциях.
Каждый ученый имеет свой статус, который зависит от количества сообщений:
•	Junior (присваивает при количестве сообщений равных от 0 до 50, но этот промежуток может быть уменьшен, в зависимости от глубины и точности рассмотрения данной тематической темы);
•	Member (присваивает при количестве сообщений равных от 50 до 500);
•	Moderator (присваивает при количестве сообщений равных от 500 и более).
Каждый ученый проводит исследования по определенной научной тематике.
При анализе предметной области «Научные конференции» выделяются объекты и атрибуты

1. Персональные_данные:
•	код_участника,
•	фамилия,
•	имя,
•	отчество,
•	код_статуса_ученого,

2. Контактные_данные:
•	код_участника,
• код_города,
•	e-mail,
•	мобильный_телефон,

3. Город:
•	код_города,
•	название_города,
•	страна,

4. Статус_учёного:
•	код_статуса_ученого,
•	статус_ученого,
•	количество_сообщений,

5. Заявка:
•	номер_заявки,
•	код_участника,
•	номер_конференции,
• код_статуса_ученого,
• дата_заявки,


6. Учёный_конференция
•	код_статуса_ученого
•	номер_доклада,
•	код_участника,
•	номер_конференции,
• тема_доклада
• отметка_о_поступлении_тезисов
• дата_поступления_тезисов

7. Тематика:
•	номер_тематики,
•	название_тематики,
•	тематические_темы,
•	количество_сообщений_в_теме,

8. Конференция:
•	номер_конференции,
•	шифр_тематики,
•	код_города,
•	название_конференции,
•	дата_проведения,
•	номер_заявки,

9. Оргвзнос:
• номер_регистрационного_взноса,
•	номер_заявки,
•	Дата_поступления_орг_взноса,
•	Размер_поступившего_орг_взноса,

10. Транспортные_вопросы_и_проживание:
• номер_транспортных_вопросов,
•	номер_заявки,
•	Дата_приезда,
•	Дата_отъезда,
•	Наличие_потребности_в_гостиннице.
