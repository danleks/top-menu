<template>
    <nav class="navigation">
         <ul class="navigation__container">
                <li class="navigation__item">
                    <a href="#" class="navigation__link">Item 01</a>
                </li>
                <li class="navigation__item">
                    <a href="#" class="navigation__link">Item 02</a>
                </li>
                <li class="navigation__item">
                    <a href="#" class="navigation__link">Item 03</a>
                </li>
                <li class="navigation__item">
                    <a href="#" class="navigation__link">Item 04</a>
                </li>
                <li class="navigation__item">
                    <a href="#" class="navigation__link">Item 05</a>
                </li>
                <li class="navigation__item">
                    <a href="#" class="navigation__link">Item 06</a>
                </li>
                <li class="navigation__item navigation__item--social">
                    <a href="#" class="navigation__link"><i class="icon ion-logo-twitter"></i></a>
                </li>
                <li class="navigation__item navigation__item--social">
                    <a href="#" class="navigation__link"><i class="icon ion-logo-facebook"></i></a>
                </li>
                <li class="navigation__item navigation__item--social">
                    <a href="#" class="navigation__link">
                            <i class="icon ion-logo-github"></i>
                    </a>
                </li>
                <li class="navigation__item navigation__item--social">
                    <a href="#" class="navigation__link"><i class="icon ion-logo-instagram"></i></a>
                </li>
            </ul>
    </nav>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

    .navigation {

        &__container {
            display: flex;
            flex-wrap: wrap;
            margin-top: 50px;

            border: 1px solid rgba(0, 0, 0, .3);
            box-shadow: 2px 2px 4px rgba(0, 0, 0, .3);
            background-color: rgba(0, 0, 0, .3);
        }

        &__item {
            flex: 3 1;
            list-style: none;
            text-align: center;
            padding: 10px 0;

            &:hover {
                background-color: rgba(0,0,0,.3);
            }

            @media(max-width: 900px) {
                flex-basis: 50%;
            }

            @media(max-width: 600px) {
                flex-basis: 100%;
            }

            &--social {
                flex: 1;

                @media(max-width: 600px) {
                flex-basis: 100%;
            }
            }
        }

        &__link {

            &:link,
            &:visited {
                color: #fff;
                text-decoration: none;
            }
        }
    }



</style>
