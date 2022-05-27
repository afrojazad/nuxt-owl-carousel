# nuxt-owl-carousel
Nuxtjs owl carousel plugins

#Installation
npm i -s vue-owl-carousel or yarn add vue-owl-carousel

#Basic Usage

<carousel>

    <img src="https://placeimg.com/200/200/any?1">

    <img src="https://placeimg.com/200/200/any?2">

    <img src="https://placeimg.com/200/200/any?3">

    <img src="https://placeimg.com/200/200/any?4">

</carousel>

#Set options,
<carousel :autoplay="true" :nav="false">

//

</carousel>

#Few more options
:autoplay="true" 
:items="2"
:loop="true"
:margin="10"
:nav="true"
:dots="true"
:responsive="{
    0: {
    items: 1
    },
    768: {
    items: 4
    }
}"

