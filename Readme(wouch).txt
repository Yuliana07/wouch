http://j06932379.myjino.ru/32/index.php
phpMyAdmin: j06932379{
 comments - кометарии, оставленные пользователем(id)
 posts - посты, оставленные пользователем(id)
 users - пользователи(id)
 likes - скольким users_id понравился ваш проект
}

lk.php{
 Личный кабинет пользователя: выложенные посты, каллендарь, подписанные организации.
(php,html,css,js)
{
 
addComment.php{
 Соединение с базой данных. Функция: комментирование.
}
index.php{
	Главная страница, лента мероприятий. 

<p><?php echo "Автор: " . $post['login']; ?></p>
  <h3><?php echo $post['post_title']; ?></h3>
<p style="word-wrap: break-word;"><?php echo $post['text']; ?></p>
}
Инструменты: css,html,php,js
Описание: регистрация, войти, выйти, добавление постов, удаление, редактирование, лайки, комментирование
from_post_add, post_add, updateProject - добавление постов.
deleteProject - удаление
login.php, login_check.php, logout.php, signUpCheck.php, singup.php - регистрация, войти, выйти.
32_backup2.zip - резервная копия(открывайте этот файл).
По плану +подписки, +коллаборация, +теги, +редактирование.
Модальное окно на index.php - гифка-изображение


Контакты: 8(999)173-66-79, julianaskryabina07@mail.ru.
