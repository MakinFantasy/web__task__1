#BEM
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

#Emmet
## Header
![alt text](./img/header.jpg)
header>div.header>img.menu__logo+div.header__nav>nav.menu__nav>a+a+a+a+a+a+button.menu__btn

## Form
![alt text](./img/sign-up.jpg)
(section.sign-up>(div.sign-up__form>img.sign-up__plane-right+(h3.sign-up__subtitle)+(h2.sign-up__title)+(form.sign-up__btnIn>(label>input.sign-up__input)+(button.sign-up__button))+img.sign-up__plane-left))

## Card
![alt text](./img/card.jpg)
(div.featured__element>(img.featured__element-image)+(div.featured__element-text>(p.featured__element-theme+p.featured__element-content))+p.featured__element-published)

## My Choice
![alt text](./img/elevate.jpg)
(section.elevate-engagement>div.elevate-engagement__content>((div.elevate-engagement__img>img)+(div.elevate-engagement__text>(div.elevate-engagement__text-title>h2)+(div.elevate-engagement__text-main>p)+(div.elevate-engagement__text-link>a))))