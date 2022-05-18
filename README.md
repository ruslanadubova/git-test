<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="assets/style.css">
</head>

<body>
    <div class="container">
        <h1 class="container__title">Форма реєстрації</h1>
        <form class="registration-form" action="register.php" method="get">
            <fieldset class="registration-form__list">
                <legend>Обов'язкові</legend>
                <div class="registration-form__list__item">
                    <label for="login">ПІБ:</label>
                    <input class="registration-form__list__item__element" id="login" name="login" type="text" required
                        placeholder="Прізвище Ім'я по Батькові" minlength="6" maxlength="50">
                </div>
                <div class="registration-form__list__item">
                    <label for="email">Імейл:</label>
                    <input class="registration-form__list__item__element" id="email" name="email" placeholder="Імейл"
                        type="email">
                </div>
                <div class="registration-form__list__item">
                    <label for="password">Пароль:</label>
                    <input class="registration-form__list__item__element" id="password" name="password" minlength="7"
                        maxlength="15" placeholder="Пароль" type="password">
                </div>
            </fieldset>
            <fieldset class="registration-form__list">
                <legend>Додаткові</legend>
                <div class="registration-form__list__item">
                    <label for="url">Адреса сайта</label>
                    <input class="registration-form__list__item__element" id="url" name="url"
                        value="https://mysite.name">
                </div>
                <div class="registration-form__list__item">
                    <label for="file">Ваше фото:</label>
                    <input class="registration-form__list__item__element" id="file" name="file" type="file">
                </div>
            </fieldset>
            <fieldset class="registration-form__list">
                <legend>Дата народження</legend>
                <div class="registration-form__list__item">
                    <label for="date">Ваша дата народження:</label>
                    <input class="registration-form__list__item__element" id="date" name="date" type="date">
                </div>
            </fieldset>
            <fieldset class="registration-form__list">
                <legend>Стать</legend>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item--choice" id="man" type="radio" name="gender"
                        value="man">
                    <label for="man">Чоловіча</label>
                </div>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item--choice" id="woman" type="radio" name="gender"
                        value="woman">
                    <label for="woman">Жіноча</label>
                </div>
            </fieldset>
            <fieldset class="registration-form__list">
                <legend>Улюблена кухня</legend>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item--choice" id="ua" checked name="kitchen"
                        value="ukrainian" type="checkbox">
                    <label for="ua">Українська</label>
                </div>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item--choice" id="ital" checked name="kitchen"
                        value="italian" type="checkbox">
                    <label for="ital">Італійська</label>
                </div>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item--choice" id="usa" checked name="kitchen" value="amerian"
                        type="checkbox">
                    <label for="usa">Американська</label>
                </div>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item--choice" id="jap" checked name="kitchen"
                        value="japanese" type="checkbox">
                    <label for="jap">Японська</label>
                </div>
            </fieldset>
            <fieldset class="registration-form__list">
                <legend>Уточнення</legend>
                <div class="registration-form__list__item">
                    <label for="txt">Про себе:</label>
                    <textarea class="registration-form__list__item__element" id="txt" name="txt" rows="10"
                        cols="50"></textarea>
                </div>
            </fieldset>
            <fieldset class="registration-form__list">
                <legend>Управління</legend>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item__element" type="submit" value="Відправити">
                </div>
                <div class="registration-form__list__item">
                    <input class="registration-form__list__item__element" type="reset" value="Скинути">
                </div>
            </fieldset>
        </form>
    </div>
</body>

</html>
