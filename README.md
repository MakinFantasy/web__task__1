# BEM
head <br>
head__eye_side_left <br>
head__eye_side_right <br>
head__mouth_status_opened <br>

hair <br>
hair_color_black <br>
hair_length_short <br>
hair_style_curve <br>

body <br>
body__hand_side_right <br>
body__hand_side_left <br>
body__chest_status_strong <br>


legs <br>
legs__left_tattoo_true <br>
legs__right_tattoo_false <br>
legs__right_scar_true <br>

# Emmet
## Header
![alt text](./img/header.jpg)<br>
header>div.header>img.header__logo+(nav.header__nav>a*5)+button.header__btn

## Form
![alt text](./img/sign-up.jpg)<br>
(section.sign-up>img.sign-up__plane_right+(p.sign-up__title_upper)+(h2.sign-up__title)+(form.sign-up__form>(label[for=""]>input[type="text" class="sign-up__form__input"])+(button.sign-up__form__button))+img.sign-up__plane_left)

## Card
![alt text](./img/card.jpg)<br>
(div.featured__card>img.featured__card__image+(div.featured__card__container>(h4.featured__card__theme)+(p.featured__card__content)+(p.featured__card__published_date)))

## My Choice
![alt text](./img/elevate.jpg)<br>
(section.elevate-engagement>(div.elevate-engagement__container>(h2.elevate-engagement__title)+(p.elevate-engagement__text)+(a.elevate-engagement__link))+img.elevate-engagement__image)