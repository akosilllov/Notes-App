Стек технологий:

HTML/CSS/Webpack/JS/Firebase

Demo : https://react-native-todoapp-827b6.firebaseapp.com

В ходе проделанной работы было разработано приложение по добавлению и сохранению заметок. 
Приложение содержит:
Экран с формой авторизации.
Экран со списком заметок.
модальное окно с формой добавления заметки.

Список заметок содержит:
Дату создания
Сколько времени прошло со времени создания.(мин, час, день)
Название
Описание

Чтобы аторизоваться нужно использовать email: Kosil@mail.ru, пароль: 111111
Если данные будут введены не верны, доступ к заметкам будет запрещен и через alert выведен необходимый для
для входа email и пароль 
 

Для авторизации пользователя и хранения заметок была использована облачная база данных Firebase.
Рендер, пройдедонного с момента создание заметки, времени происходит через каждую минуту.

Чтобы запустить приложение, нужно перейти в папку проекта и набрать команду
### `npm run start`

