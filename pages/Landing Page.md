---
title: Landing Page
permalink: /landing-page/
description: ""
---
```
```
<style>
@font-face {
    font-family: "DIN Alternate Bold";
    src: url("https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/fonts/din_alternate_bold-webfont.woff2") format("woff2"),
        url("https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/fonts/din_alternate_bold-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}

@font-face {
    font-family: "DIN Alternate Regular";
    src: url("https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/fonts/din_alternate-webfont.woff2") format("woff2"),
        url("https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/fonts/din_alternate-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}

@font-face {
    font-family: "DIN Black";
    src: url("https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/fonts/din-black-webfont.woff2") format("woff2"),
        url("https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/fonts/din-black-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}
* {
    padding: 0;
    margin: 0;
}
:root {
    --blue: #0037cc;
    --yellow: #ffd700;
    --cyan: #00c5e4;
    --green: #75d200;
}

body,
html {
    overflow-x: hidden;
}
.img-full {
    width: 100%;
}
.bg-yellow {
    background-color: var(--yellow);
}
.bg-cyan {
    background-color: var(--cyan);
}
.bg-green {
    background-color: var(--green);
}
.landing {
    background: #0037cc url(../img/grid-background.svg) no-repeat center;
    background-size: cover;
}
.item__button-landing {
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.item__button-landing a {
    display: block;
    width: 120px;
    height: 120px;
    position: relative;
}
.content-landing {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.logo-landing {
    width: 50%;
    max-width: 730px;
    margin-right: 130px;
}

.desc-landing {
    width: 40%;
    max-width: 400px;
    color: #fff;
    font-size: 18px;
    font-weight: 700;
    line-height: 22px;
    font-family: "DIN Alternate Bold";
    flex-shrink: 0;
}

.desc-landing a {
    color: #fff;
    text-decoration: none;
    font-family: "DIN Alternate Bold";
    font-size: 18px;
}
.item__button-landing > div {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.desc-landing h4 {
    color: #fff;
    text-decoration: none;
    font-family: "DIN Alternate Bold";
    font-size: 20px;
    line-height: 19px;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 38px;
    text-align: center;
    margin-top: 30px;
    margin-bottom: 0;
    width: 120%;
}
.item-button-truck a img {
    width: 92px;
    margin-bottom: 15px;
}
.logo-footer-landing {
    margin-top: 40px;
}
.item-button-find-out-more a {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #75d200;
}

.item-button-find-out-more {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
}

.item-button-truck {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 120px;
    margin-right: 57px;
}
.item-button-truck a {
    display: flex;
    width: 120px;
    justify-content: center;
    align-items: flex-end;
    background-color: #fff;
}
.item__button-landing a::after {
    content: "";
    position: absolute;
    top: 10px;
    right: -10px;
    bottom: -10px;
    left: 10px;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
    background-color: #000;
    z-index: -1;
}

.button-landing {
    margin-top: 30px;
    position: relative;
    z-index: 9;
}

.item__button-landing a:hover:after {
    right: -15px;
    bottom: -15px;
    left: 15px;
}
.item-button-truck a span {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    overflow: hidden;
}
img {
    max-width: 100%;
}
.header-home {
    background: #0037cc url(../img/grid-background.svg) no-repeat center;
    background-size: cover;
    padding: 120px 60px;
    min-height: 80vh;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.bg-blue-grid {
    background: #0037cc url(../img/grid-background.svg) no-repeat center;
    background-size: cover;
}
.py-80 {
    padding: 80px 0;
}
.h-full {
    height: 100%;
}
.content-footer {
    height: 120px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
footer .socmed a {
    display: block;
}

footer .socmed {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 19px;
}
.v-center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
}
.left-col__home-header {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    padding-right: 80px;
    position: relative;
    z-index: 2;
}

.left-col__home-header h1 {
    color: #fff;
    font-size: 32px;
    font-family: "DIN Alternate Bold";
    margin: 25px 0;
    max-width: 383px;
}
a {
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
}
.btn-rounded {
    text-decoration: none;
    padding: 13px 20px;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    border-radius: 50px;
    font-size: 18px;
    font-family: "DIN Black";
    line-height: 16px;
    position: relative;
    border: none;
    cursor: pointer;
}

.btn-rounded.bg-green {
    color: #fff;
}
.btn-rounded.bg-green:hover {
    color: #eee;
}
.btn-rounded-white {
    background-color: #fff;
    color: #000;
    text-decoration: none;
    padding: 13px 20px;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    border-radius: 50px;
    font-size: 18px;
    font-family: "DIN Black";
    line-height: 16px;
    position: relative;
    border: none;
    cursor: pointer;
}
.btn-rounded-yellow {
    background-color: #ffd700;
    color: #000;
    text-decoration: none;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    border-radius: 50px;
    font-size: 18px;
    font-family: "DIN Black";
    line-height: 16px;
    position: relative;
    padding: 13px 20px;
    border: none;
    cursor: pointer;
}
.btn-rounded-white:hover,
.btn-rounded-yellow:hover {
    color: #2b2b2b;
}
p,
li {
    font-family: "DIN Alternate Bold";
    font-size: 16px;
    line-height: 22px;
}
p:last-child {
    margin-bottom: 0;
}

.shadow-button {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 6px;
    left: 6px;
    background-color: #000;
    border-radius: 50px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    -ms-border-radius: 50px;
    -o-border-radius: 50px;
    z-index: -1;
}
/* .wrapper-button::after {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 6px;
    left: 6px;
    background-color: #000;
    border-radius: 50px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    -ms-border-radius: 50px;
    -o-border-radius: 50px;
    z-index: -1;
} */
.copyright {
    font-size: 16px;
    font-family: "DIN Alternate Bold";
    color: #0037cc;
}
.nav-home {
    position: fixed;
    left: 0;
    right: 0;
    top: 0;
    padding: 40px 0 0;
}
.nav-home {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    padding: 40px 0 0;
}

.top-menu li a {
    font-size: 16px;
    color: #fff;
    font-family: "DIN Black";
    text-transform: uppercase;
    text-decoration: none;
}

.top-menu > li {
    list-style: none;
    margin-right: 48px;
}

.top-menu {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    margin: 0;
    padding: 0;
    position: relative;
    z-index: 5;
}

.submenu {
    opacity: 0;
    position: absolute;
    top: 29px;
    right: 0;
    padding: 10px 20px;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
    transform: translateY(-20px);
    -webkit-transform: translateY(-20px);
    -moz-transform: translateY(-20px);
    -ms-transform: translateY(-20px);
    -o-transform: translateY(-20px);
    z-index: -9;
    background: #fff;
    border-radius: 0;
    pointer-events: none;
}
.backdrop-nav {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: transparent;
    z-index: -999;
}

.map-truck {
    width: 808px;
    margin: 110px auto 40px;
}
.outCircle {
    width: 432px;
    height: 201px;
    background-color: transparent;
    left: 50%;
    position: absolute;
    top: 45%;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
    transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%);
    -moz-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    -o-transform: translate(-50%, -50%);
}
.outCircleFloatTruck3 {
    width: 100px;
    height: 100px;
    background-color: transparent;
    position: absolute;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
    right: 34px;
    top: 6em;
}
.outCircleFloatTruck4 {
    width: 100px;
    height: 130px;
    background-color: transparent;
    left: 39%;
    position: absolute;
    top: 93%;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
}
.outCircleFloatHomeIcon5 {
    width: 90px;
    height: 90px;
    background-color: transparent;
    right: 38px;
    position: absolute;
    bottom: 81px;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
}
.outCircleFloatHomeIcon6 {
    width: 100px;
    height: 100px;
    background-color: transparent;
    left: 272px;
    position: absolute;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
    bottom: 95px;
}
.outCircleFloatHomeIcon7 {
    width: 150px;
    height: 150px;
    background-color: transparent;
    left: -13px;
    position: absolute;
    top: 222px;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
}
.outCircleFloatHomeIcon4 {
    width: 150px;
    height: 150px;
    background-color: transparent;
    position: absolute;
    top: 209px;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
    right: -24px;
}
.outCircleFloatHomeIcon3 {
    width: 100px;
    height: 100px;
    background-color: transparent;
    right: -43px;
    position: absolute;
    top: 33px;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
}
.outCircleFloatHomeIcon2 {
    width: 110px;
    height: 110px;
    background-color: transparent;
    left: 220px;
    position: absolute;
    top: 55px;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
}
.outCircleFloatHomeIcon1 {
    width: 120px;
    height: 120px;
    background-color: transparent;
    left: 165px;
    position: absolute;
    top: 23px;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
}
.outCircleFloatTruck1 {
    width: 191px;
    height: 162px;
    background-color: transparent;
    left: -32px;
    position: absolute;
    top: 28px;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
}
.outCircleIconTruck {
    width: 253px;
    height: 233px;
    background-color: transparent;
    left: 48%;
    position: absolute;
    top: 34%;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
    transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%);
    -moz-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    -o-transform: translate(-50%, -50%);
}
.show_popup-truck {
    width: 55px;
    height: 55px;
    position: absolute;
    cursor: pointer;
    z-index: 99;
}
#header-truck {
    background-attachment: fixed;
}
.title-section {
    font-size: 48px;
    line-height: 50px;
    font-family: "DIN Black";
}
.wrapper-desc-item-truck {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.desc-item-truck {
    width: 413px;
}

.title-item-truck {
    background-color: #fff;
    display: inline-block;
    padding: 5px 18px;
    border: 5px solid var(--blue);
    border-bottom: none;
}

.title-item-truck h2 {
    font-size: 36px;
    line-height: 50px;
    font-family: "DIN Black";
    margin: 0;
    color: var(--blue);
}

.text-item-truck {
    background-color: #fff;
    padding: 30px;
    border: 5px solid var(--blue);
}
.show_popup-truck-1 {
    top: 56px;
    right: 270px;
}

.show_popup-truck-2 {
    right: 162px;
    bottom: 121px;
}

.show_popup-truck-3 {
    bottom: 176px;
    left: 108px;
}
.outCircleFloatTruck2 {
    width: 155px;
    height: 133px;
    background-color: transparent;
    right: -126px;
    position: absolute;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 100px;
    bottom: 55px;
}
.innerIconTruck img {
    width: 100%;
}
.rotate {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateFloatHomeIcon7 {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateFloatHomeIcon6 {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateFloatHomeIcon5 {
    width: 100%;
    height: 100%;
    animation: circle 5s infinite linear;
    -webkit-animation: circle 5s infinite linear;
}
.rotateFloatHomeIcon4 {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateFloatHomeIcon3 {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateFloatHomeIcon2 {
    width: 100%;
    height: 100%;
    animation: circle 5s infinite linear;
    -webkit-animation: circle 5s infinite linear;
}
.rotateFloatHomeIcon1 {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateFloatTruck1 {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateFloatTruck2 {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}
.rotateIconTruck {
    width: 100%;
    height: 100%;
    animation: circle 10s infinite linear;
    -webkit-animation: circle 10s infinite linear;
}

.counterrotate {
    width: 200px;
    height: 200px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatTruck3 {
    width: 79px;
    height: 79px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatTruck4 {
    width: 78px;
    height: 104px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatHomeIcon7 {
    width: 116px;
    height: 116px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatHomeIcon6 {
    width: 74px;
    height: 74px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatHomeIcon5 {
    width: 76px;
    height: 76px;
    animation: ccircle 5s infinite linear;
    -webkit-animation: ccircle 5s infinite linear;
}
.counterrotateFloatHomeIcon4 {
    width: 117px;
    height: 116px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatHomeIcon3 {
    width: 73px;
    height: 73px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatHomeIcon2 {
    width: 77px;
    height: 76px;
    animation: ccircle 5s infinite linear;
    -webkit-animation: ccircle 5s infinite linear;
}
.counterrotateFloatHomeIcon1 {
    width: 100px;
    height: 100px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatTruck1 {
    width: 200px;
    height: 200px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateFloatTruck2 {
    width: 200px;
    height: 200px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.counterrotateIconTruck {
    width: 100px;
    height: 90px;
    animation: ccircle 10s infinite linear;
    -webkit-animation: ccircle 10s infinite linear;
}
.right-col__home-header {
    position: relative;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.inner {
    width: 185px;
    height: 185px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatTruck3 {
    width: 79px;
    height: 79px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatTruck4 {
    width: 78px;
    height: 104px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatHomeIcon7 {
    width: 116px;
    height: 116px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatHomeIcon6 {
    width: 74px;
    height: 74px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatHomeIcon5 {
    width: 76px;
    height: 76px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatHomeIcon4 {
    width: 117px;
    height: 116px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatHomeIcon3 {
    width: 73px;
    height: 73px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatHomeIcon2 {
    width: 77px;
    height: 76px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatHomeIcon1 {
    width: 93px;
    height: 93px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatTruck1 {
    width: 185px;
    height: 185px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerFloatTruck2 {
    width: 185px;
    height: 185px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.innerIconTruck {
    width: 185px;
    height: 185px;
    background: transparent;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 100px;
    position: absolute;
    left: 0px;
    top: 0px;
    background-color: transparent;
    display: block;
}
.popup-truck {
    background-color: #fff;
    display: inline-block;
    padding: 16px 18px;
    border-radius: 35px;
    position: absolute;
    box-shadow: 6px 6px 0px #000000;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
}
.popup-truck-1 {
    left: 490px;
    top: -133px;
}
.popup-truck.expanded {
    width: 350px;
}

.popup-truck.expanded .title-popup {
    justify-content: space-between;
}

.popup-truck.expanded .arrow-popup-truck {
    width: 38px;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 4px;
}

.popup-truck.expanded .arrow-popup-truck img:nth-child(2) {
    left: 14px;
}
.popup-truck.expanded .arrow-popup-truck img:nth-child(3) {
    left: 28px;
}

.popup-truck-2 {
    width: 200px;
    top: 25em;
    left: 36.6em;
}

.popup-truck-3 {
    width: 206px;
    top: 25.5em;
    left: -40px;
}

.popup-truck article {
    display: none;
    position: relative;
    z-index: 5;
}
.title-popup {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    cursor: pointer;
}
.arrow-popup-truck {
    justify-content: center;
    align-items: center;
    position: relative;
    width: 10px;
    height: 14px;
    margin-left: 8px;
}

.arrow-popup-truck img {
    position: absolute;
    left: 0;
    top: 0;
    width: 10px;
    z-index: 999;
    height: 14px;
    display: block;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
}
.popup-truck-1:after {
    content: "";
    position: absolute;
    left: 21px;
    top: 44px;
    height: 174px;
    background-color: #fff;
    width: 3px;
}
.popup-truck-2:after {
    content: "";
    position: absolute;
    left: 32px;
    top: -54px;
    height: 67px;
    background-color: #fff;
    width: 3px;
}
.popup-truck-3:after {
    content: "";
    position: absolute;
    left: 174px;
    top: -114px;
    height: 128px;
    background-color: #fff;
    width: 3px;
}
.title-popup h2 {
    font-size: 20px;
    margin: 0;
    font-family: "DIN Black";
    user-select: none;
}
.popup-truck-1 .title-popup h2 {
    color: var(--green);
}
.popup-truck-2 .title-popup h2 {
    color: var(--cyan);
}
.popup-truck-3 .title-popup h2 {
    color: var(--yellow);
}

.popup-truck h3 {
    font-size: 16px;
    font-family: "DIN Alternate Bold";
    line-height: 24px;
    color: var(--blue);
    margin: 0;
}

.popup-truck-1 article {
    margin-top: 7px;
}
.submenu li a {
    color: var(--blue);
}
.submenu.show {
    opacity: 1;
    padding: 10px 20px;
    transform: translateY(0);
    -webkit-transform: translateY(0);
    -moz-transform: translateY(0);
    -ms-transform: translateY(0);
    -o-transform: translateY(0);
    z-index: 9;
    pointer-events: auto;
}
.submenu li {
    padding: 5px 0;
    list-style: none;
}
.has-submenu {
    position: relative;
    margin-right: 68px !important;
}

.has-submenu::after {
    content: "";
    position: absolute;
    right: -20px;
    top: 50%;
    transform: translateY(-50%) rotate(0);
    -webkit-transform: translateY(-50%) rotate(0);
    -moz-transform: translateY(-50%) rotate(0);
    -ms-transform: translateY(-50%) rotate(0);
    -o-transform: translateY(-50%) rotate(0);
    width: 13px;
    height: 9.5px;
    background: url(../img/caret-down.svg) no-repeat center;
    background-size: contain;
    cursor: pointer;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
}
.nav-white .has-submenu::after {
    background: url(../img/caret-down-blue.svg) no-repeat center !important;
}
.has-submenu.open::after {
    top: 50%;
    transform: translateY(-50%) rotate(180deg);
    -webkit-transform: translateY(-50%) rotate(180deg);
    -moz-transform: translateY(-50%) rotate(180deg);
    -ms-transform: translateY(-50%) rotate(180deg);
    -o-transform: translateY(-50%) rotate(180deg);
}
.hamburger {
    display: none;
}

.nav-white {
    position: absolute;
    width: 100%;
    top: 30px;
}

.nav-white .top-menu {
    background-color: #fff;
    height: 92px;
    padding: 0 48px;
}

.nav-white .top-menu li a {
    color: var(--blue);
}
.header-nav-white {
    padding-top: 180px;
}

.img-about-header {
    position: relative;
    margin: 35px 0 -230px;
}
.logo-nav {
    width: 94px;
}

.nav-white__logo {
    margin-right: 75px !important;
}
.left-col__header-careers article {
    background-color: #fff;
    width: 353px;
    padding: 20px 20px 30px;
    margin-left: 57px;
}
.right-col__header-careers {
    width: 439px;
    margin-right: auto;
}
#header-careers {
    padding-bottom: 150px;
}
.wrapper-button {
    position: relative;
    z-index: 2;
    display: inline-block;
}
.wrapper-title-careers a {
    display: flex;
    background-color: #ffd700;
    border: 2px solid #fff;
    width: 20%;
    height: 45px;
    color: #000;
    text-decoration: none;
    font-family: "DIN BLACK";
    justify-content: center;
    align-items: center;
    font-size: 24px;
}

.wrapper-title-careers {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    max-width: 1064px;
    margin: -110px auto 0;
}
.content-results-careers {
    max-width: 1064px;
    margin: 50px auto;
}

.title-result-career {
    border: 5px solid var(--blue);
    display: inline-block;
    padding: 5px 20px;
    font-size: 36px;
    font-family: "DIN Black";
    color: var(--blue);
    border-bottom: none;
}

.box-info-career {
    border: 5px solid var(--blue);
    padding: 30px 25px;
    margin-bottom: 25px;
}
.box-info-career h2 {
    color: var(--blue);
    font-family: "DIN Black";
    font-size: 24px;
}
.wrapper-title-careers a.active {
    background-color: #75d200;
    color: #fff;
}
.box-info-career__right-top {
    margin-top: 69px;
}
.selected-career {
    display: none;
}
.backdrop-careers {
    position: fixed;
    left: 0;
    top: 0;
    right: 0;
}
.show-backdrop .backdrop-careers {
    bottom: 0;
}
.loading img {
    width: 80px;
}
.wrapper-title-careers a:hover {
    position: relative;
    color: #000;
    background-color: #75d200;
    border-color: #75d200;
    box-shadow: 6px 6px 0px #000000;
}
.swiperTrails {
    width: 100%;
    height: auto;
}

.swiperTrails .swiper-slide {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 22px;
    font-weight: bold;
    color: #fff;
}
.container-pagination-trails .prev-slide {
    margin-right: -7px;
}

.container-pagination-trails .next-slide {
    margin-left: -1px;
}
.swiperTrails .swiper-pagination {
    position: relative;
    height: 45px;
    bottom: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #fff;
    font-size: 18px;
    font-family: "DIN Black";
}
.container-pagination-trails {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    width: 196px;
    height: 50px;
    margin: 30px auto 60px;
}
.wrapper-title-trails {
    margin-left: 50px;
    margin-bottom: -50px;
    position: relative;
    z-index: 2;
}

.wrapper-title-trails article {
    width: 294px;
    background-color: #fff;
    padding: 15px;
    margin-left: 53px;
}
#header-trails {
    padding-bottom: 50px;
    background-attachment: fixed;
}
.title-content-trails span {
    font-size: 24px;
    font-family: "DIN Black";
    display: inline-flex;
    justify-content: center;
    align-items: center;
    background-color: #000;
    color: #fff;
    padding: 8px 17px;
}

.title-content-trails h2 {
    font-size: 24px;
    font-family: "DIN Black";
    background-color: #00c5e4;
    margin: 0;
    padding: 8px 17px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    color: #fff;
}

.title-content-trails {
    display: flex;
    justify-content: flex-start;
    align-items: stretch;
    height: 40px;
}

.content-trails {
    padding-left: 100px;
}

.item-content-trails {
    margin-bottom: 50px;
}

.item-content-trails article {
    color: #fff;
    margin: 20px 0;
}
.form-trails {
    background-color: #fff;
    display: inline-block;
    padding: 20px;
    border-radius: 25px;
    filter: drop-shadow(6px 6px 0px #000000);
    -webkit-filter: drop-shadow(6px 6px 0px #000000);
    width: 305px;
    position: relative;
    display: none;
}
.form-trails.success {
    min-height: 180px;
}
.form-group__informed label {
    font-size: 18px;
    font-family: "DIN Black";
    line-height: 16px;
}

.form-group__informed {
    margin-bottom: 11px;
}

.form-group__informed .form-input {
    border: none;
    border-bottom: 2px solid #000;
    padding: 2px 5px;
    margin-left: 5px;
}
.form-group__informed .form-input:focus {
    outline: none;
    box-shadow: none;
}
label.error {
    color: red;
    font-family: "DIN Alternate Bold";
    font-size: 12px;
}
.swiper-slide img {
    width: 100%;
}
.right-col__header-trails {
    margin-top: 175px;
}
.form-trails .wrapper-button {
    margin-top: 15px;
}
.success-submit-trails {
    text-align: center;
    font-size: 20px;
    font-family: "DIN Black";
    color: var(--blue);
    margin: 0;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
    padding: 20px;
}
.loading-form-trails {
    text-align: center;
    margin: 50px 0;
}

.loading-form-trails img {
    width: 50px;
}
.left-col__header-newsroom,
.right-col__header-newsroom {
    position: relative;
    filter: drop-shadow(6px 6px 0px #000000);
    -webkit-filter: drop-shadow(6px 6px 0px #000000);
}

.left-col__header-newsroom span,
.right-col__header-newsroom span {
    position: absolute;
    top: 20px;
    left: 30px;
    color: #fff;
    font-family: "DIN Alternate Bold";
    font-size: 32px;
    line-height: 38px;
    z-index: 5;
}
.col__header-newsroom {
    position: relative;
}

.col__header-newsroom:after {
    content: "";
    position: absolute;
    background-color: rgba(0, 0, 0, 0.7);
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 1;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
}
.col__header-newsroom:hover:after {
    background-color: rgba(0, 0, 0, 0);
}
.col__header-newsroom:hover span {
    opacity: 0;
}

#header-newsroom {
    padding-bottom: 50px;
}

.title-page {
    font-size: 48px;
    color: #fff;
    line-height: 50px;
    font-family: "DIN Black";
    margin-bottom: 21px;
}
.wrapper-content-newsroom {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.item-content-newsroom {
    width: calc(25% - 20px);
    position: relative;
}

.item-content-newsroom:hover .title-content-newsroom {
    opacity: 0;
}
.item-content-newsroom::after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0, 0, 0, 0.6);
}
.item-content-newsroom:hover:after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    background-color: transparent;
}

.title-content-newsroom {
    position: absolute;
    top: 16px;
    left: 20px;
    width: 210px;
    opacity: 1;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
    z-index: 2;
}

.title-content-newsroom h2 {
    font-size: 24px;
    line-height: 28px;
    color: #fff;
    font-family: "DIN Alternate Bold";
    margin-bottom: 8px;
}

.date-news-room {
    font-size: 16px;
    line-height: 28px;
    color: #fff;
    font-family: "DIN Alternate Regular";
}

.button-download-newsroom {
    position: absolute;
    z-index: 2;
    bottom: 23px;
    left: 20px;
}

.thumbnail-newsroom {
    box-shadow: 6px 6px 0px #000000;
}
.pagination-newsroom .number {
    width: 78px;
    height: 45px;
    background-color: #000;
    color: #fff;
    font-family: "DIN Alternate Bold";
    display: flex;
    justify-content: center;
    align-items: center;
    margin-left: -10px;
}

.pagination-newsroom {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    margin-top: 40px;
}

/* Custom Select */
/* The container must be positioned relative: */
.custom-select {
    position: relative;
    font-family: Arial;
}

.custom-select select {
    display: none; /*hide original SELECT element: */
}

.select-selected {
    background-color: transparent;
}

/* Style the arrow inside the select element: */
.select-selected:after {
    position: absolute;
    content: "";
    top: 14px;
    right: -50px;
    width: 0;
    height: 0;
    border: 18px solid transparent;
    border-color: var(--blue) transparent transparent transparent;
}
.custom-select {
    margin-right: 50px;
    margin-left: 15px;
}
.form-group-contact textarea {
    width: 100%;
    min-height: 190px;
    border: none;
}
/* Point the arrow upwards when the select box is open (active): */
.select-selected.select-arrow-active:after {
    border-color: transparent transparent var(--blue) transparent;
    top: -5px;
}

/* style the items (options), including the selected item: */

.select-selected {
    color: var(--blue);
    border-bottom: 5px solid var(--blue);
    cursor: pointer;
    min-height: 45px;
    font-family: "DIN Black";
    font-size: 24px;
}
.select-items div {
    color: var(--blue);
    padding: 0 23px;
    cursor: pointer;
    font-size: 24px;
    font-family: "DIN Black";
    line-height: 50px;
}
.form-group-contact ::-webkit-input-placeholder {
    font-size: 24px;
    font-family: "DIN Black";
    color: var(--blue);
    line-height: 50px;
    margin-right: 15px;
}

.form-group-contact ::-ms-input-placeholder {
    font-size: 24px;
    font-family: "DIN Black";
    color: var(--blue);
    line-height: 50px;
    margin-right: 15px;
}

.form-group-contact ::placeholder {
    font-size: 24px;
    font-family: "DIN Black";
    color: var(--blue);
    line-height: 50px;
    margin-right: 15px;
}
.search-courses ::-webkit-input-placeholder {
    font-size: 14px;
    font-family: "DIN Black";
    color: var(--blue);
}

.search-courses ::-ms-input-placeholder {
    font-size: 14px;
    font-family: "DIN Black";
    color: var(--blue);
}

.search-courses ::placeholder {
    font-size: 14px;
    font-family: "DIN Black";
    color: var(--blue);
}

/* Style items (options): */
.select-items {
    position: absolute;
    background-color: #fff;
    top: calc(100% - 5px);
    left: 0;
    right: 0;
    z-index: 99;
    border: 5px solid var(--blue);
    box-shadow: 4px 4px 0px #0037cc;
}
/* Hide the items when the select box is closed: */
.select-hide {
    display: none;
}

.select-items div:hover,
.same-as-selected {
    background-color: rgba(0, 0, 0, 0.1);
}
.form-contact {
    width: 955px;
    position: relative;
    margin: 0 auto 0;
}

#frm-contact {
    background-color: #fff;
    width: 844px;
    height: 540px;
    margin-left: auto;
    border: 5px solid var(--blue);
    padding: 25px 50px;
}
.title-contact {
    width: 432px;
}

#header-contact {
    padding-bottom: 74px;
}
.form-group-contact label {
    font-size: 24px;
    font-family: "DIN Black";
    color: var(--blue);
    line-height: 50px;
    margin-right: 15px;
}

.form-name-email__contact {
    display: flex;
    gap: 20px;
    justify-content: space-between;
    align-items: center;
}

.form-name-email__contact .form-group-contact {
    width: calc(50% - 10px);
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

.form-name-email__contact .form-group-contact input {
    flex-grow: 1;
    border: none;
    border-bottom: 5px solid var(--blue);
}
.form-group-contact {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    margin-bottom: 20px;
    position: relative;
    margin-bottom: 40px;
}
.form-group-contact input:focus,
.form-group-contact textarea:focus {
    outline: none;
    box-shadow: none;
}
.form-group-contact input,
.form-group-contact textarea {
    font-size: 24px;
    font-family: "DIn Black";
    line-height: 50px;
    color: var(--blue);
}

/* End Custom Select */

.form-group-contact label.error {
    padding-left: 26px;
    font-size: 16px;
    width: 100%;
    position: absolute;
    bottom: -48px;
    color: #ff0000;
    font-family: "DIN Alternate Regular";
    font-weight: 700;
    line-height: 20px;
    min-height: 45px;
}
.form-group-contact label.error[for="message"] {
    top: 15px;
    left: 113px;
}
.form-group-contact label.error:before {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    width: 18px;
    height: 18px;
    background: url(../img/icon-error.svg) no-repeat center;
    background-size: contain;
}
.subject-hidden {
    margin-top: -40px;
    opacity: 0;
}
.error[for="subjects"] {
    display: block;
    top: -29px;
}
.nav-home.fixed {
    position: fixed;
    background-color: var(--blue);
    z-index: 9999;
    height: 81px;
    left: 20px;
    right: 20px;
    top: 20px;
    border-radius: 50px;
    padding: 0 20px 0;
    display: flex;
    justify-content: center;
    align-items: center;
    animation: slide-in--down 420ms cubic-bezier(0.165, 0.84, 0.44, 1);
    -webkit-animation: slide-in--down 420ms cubic-bezier(0.165, 0.84, 0.44, 1);
}
.parent-menu {
    cursor: pointer;
    user-select: none;
}
.back-to-top {
    position: fixed;
    right: 20px;
    bottom: 100px;
    cursor: pointer;
    display: none;
    z-index: 9999999;
}
#frm-contact.success {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

#frm-contact.success h3 {
    font-size: 40px;
    line-height: 50px;
    font-family: "DIN Black";
    color: var(--blue);
}
.form-group-contact textarea {
    resize: none;
}

.animate-button-text:hover span {
    animation: SlideText 1s forwards;
    -webkit-animation: SlideText 1s forwards;
}
.loading-contact {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
#header-virtual-fair-2022 {
    padding-bottom: 80px;
}

.header-left-virtual-fair-2022 article {
    background-color: #fff;
    padding: 15px;
    margin-left: 44px;
}

.header-left-virtual-fair-2022 {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
}
.p-relative {
    position: relative;
}
.wrapper-iframe {
    position: relative;
    padding-bottom: 56.25%;
    width: 100%;
    display: block;
    height: 0;
}

.wrapper-iframe iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.title-video {
    border: 5px solid var(--blue);
    font-size: 36px;
    font-family: "DIN Black";
    line-height: 50px;
    display: inline-block;
    padding: 3px 18px;
    color: var(--blue);
    border-bottom: none;
    background-color: #fff;
}

.desc-video {
    padding: 25px;
    border: 5px solid var(--blue);
    width: 414px;
    background-color: #fff;
}

.text-video {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
}
.inner-paginate-videos a {
    display: block;
    width: 20px;
    height: 20px;
    background-color: var(--blue);
    border-radius: 50%;
    margin: 5px 0;
    cursor: pointer;
}

.pagination-video {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    -moz-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    -o-transform: translateY(-50%);
    right: 0;
}
.new-pagination-video {
    display: none;
}
.inner-paginate-videos {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-end;
}
.inner-paginate-videos a.active {
    box-shadow: inset 0 0 0px 6px var(--blue) !important;
    background-color: #fff !important;
}
.row-item-video {
    display: none;
    transform: translateY(20px);
    -webkit-transform: translateY(20px);
    -moz-transform: translateY(20px);
    -ms-transform: translateY(20px);
    -o-transform: translateY(20px);
    transition: 0.5s;
    -webkit-transition: 0.5s;
    -moz-transition: 0.5s;
    -ms-transition: 0.5s;
    -o-transition: 0.5s;
}
.row-item-video.show {
    display: flex;
    transform: translateY(0);
    -webkit-transform: translateY(0);
    -moz-transform: translateY(0);
    -ms-transform: translateY(0);
    -o-transform: translateY(0);
}
.subtitle-tiktok {
    width: 540px;
    border: 5px solid #75d200;
    padding: 30px;
    margin: -5px 0 0 44px;
}

.wrapper-title-tiktok {
    margin-bottom: 50px;
}
.subtitle-tiktok {
    width: 540px;
    border: 5px solid #75d200;
    padding: 30px;
    margin: -5px 0 0 44px;
}

.wrapper-title-tiktok {
    margin-bottom: 50px;
}

.no-scroll {
    overflow-y: hidden;
}

.no-scroll body {
    overflow: scroll;
}
.tiktok-swiper_nav {
    display: none;
}
.footer-nav {
    margin-top: 40px;
    margin-bottom: 40px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
.button-nav span {
    display: inline-block;
    background-color: #000;
    color: #fff;
    font-size: 18px;
    line-height: 22px;
    padding: 10px;
    font-family: "DIN Alternate Bold";
    margin-right: -5px;
}
.container-video {
    display: none;
}

.container-video.show {
    display: block;
}
.container-video .row {
    margin-bottom: 70px;
}
.footer-nav-vf-2021 span {
    margin-left: -10px;
}
.img-header-courses {
    width: 439px;
    position: absolute;
    right: 0;
    bottom: -168px;
}
.courses-dropdown {
    background-color: #fff;
    display: inline-block;
    border: 5px solid var(--blue);
    padding: 8px 80px 10px 30px;
    cursor: pointer;
}

.courses-dropdown h2 {
    font-family: "DIN Black";
    text-transform: uppercase;
    font-size: 48px;
    line-height: 50px;
    margin: 0;
    color: var(--blue);
    position: relative;
}
.courses-dropdown h2:after {
    content: "";
    position: absolute;
    right: -54px;
    top: 50%;
    transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    -moz-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    -o-transform: translateY(-50%);
    width: 31px;
    height: 22px;
    background: url(../img/caret-down-blue.svg) no-repeat center;
    background-size: contain;
}
.left-header-courses article {
    background-color: #fff;
    padding: 20px 30px;
    border: 5px solid var(--blue);
    margin-left: 105px;
    margin-top: -5px;
}

.left-header-courses {
    margin-top: 40px;
    margin-bottom: 40px;
    padding: 15px 0;
}
#search-courses {
    border: 2px solid var(--blue);
    border-radius: 25px;
    width: 100%;
    height: 40px;
    padding: 0 25px;
    position: relative;
    color: var(--blue);
    font-size: 16px;
    font-family: "DIN Alternate Bold";
}
#search-courses:focus {
    outline: none;
    box-shadow: none;
}
.search-courses {
    width: 306px;
    height: 40px;
}
.search-courses:after {
    content: "";
    position: absolute;
    right: 15px;
    top: 50%;
    transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    -moz-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    -o-transform: translateY(-50%);
    width: 20px;
    height: 20px;
    background: url(../img/icon-search.svg) no-repeat center;
    background-size: contain;
}
.item-dropdown-courses > h2 {
    font-size: 32px;
    font-family: "DIN Black";
    color: var(--blue);
    line-height: 50px;
}
.item-dropdown-courses .accordion-button {
    font-size: 24px;
    font-family: "DIN Black";
    line-height: 50px;
    padding: 0;
    border-color: transparent;
    border: none;
    text-transform: uppercase;
    color: #000;
}
.item-dropdown-courses .accordion-button:not(.collapsed) {
    color: #000;
    background-color: transparent;
    box-shadow: none;
}
.item-dropdown-courses .accordion-item {
    border: none;
}
.accordion-body {
    font-size: 24px;
    font-family: "DIN Alternate Bold";
    padding: 10px 0;
    color: #000;
}
.accordion-button:focus {
    box-shadow: none;
}
.item-dropdown-courses .accordion-button.collapsed::after {
    flex-shrink: 0;
    width: 28px;
    height: 28px;
    margin-left: auto;
    content: "";
    background-image: url(../img/icon-plus.svg);
    background-repeat: no-repeat;
    background-size: contain;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
}
.item-dropdown-courses .accordion-button::after {
    flex-shrink: 0;
    width: 28px;
    height: 28px;
    margin-left: auto;
    content: "";
    background-image: url(../img/icon-minus.svg);
    background-repeat: no-repeat;
    background-size: contain;
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
}
.item-dropdown-courses .accordion-body ul li {
    font-size: 20px;
    line-height: 26px;
    font-family: "DIN Black";
    list-style: none;
    margin-bottom: 20px;
    position: relative;
    padding-right: 60px;
}

.item-dropdown-courses .accordion-body ul {
    padding: 0;
    margin: 0;
}
.item-dropdown-courses .accordion-body ul li:after {
    content: "";
    width: 20px;
    height: 20px;
    background: url(../img/arrow-list.svg) no-repeat center;
    background-size: contain;
    position: absolute;
    right: 0;
    top: 50%;
    transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    -moz-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    -o-transform: translateY(-50%);
}
.item-dropdown-courses {
    padding: 17px 0;
    border-bottom: 1px solid var(--blue);
}

.item-dropdown-courses:last-child {
    border-bottom: none;
}
.popup-menu-courses {
    position: absolute;
    top: 87px;
    left: 0;
    background-color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    transform: scaleY(0);
    -webkit-transform: scaleY(0);
    -moz-transform: scaleY(0);
    -ms-transform: scaleY(0);
    -o-transform: scaleY(0);
    transition: 0.3s;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -ms-transition: 0.3s;
    -o-transition: 0.3s;
    transform-origin: top center;
    border: 5px solid var(--blue);
    padding: 20px 20px;
    box-shadow: 8px 8px 0px #0037cc;
}
.popup-menu-courses.show {
    transform: scaleY(1);
    -webkit-transform: scaleY(1);
    -moz-transform: scaleY(1);
    -ms-transform: scaleY(1);
    -o-transform: scaleY(1);
    z-index: 999;
}

.popup-menu-courses ul {
    padding: 0;
    margin: 0;
}

.popup-menu-courses ul li {
    list-style: none;
    padding: 0;
    margin: 0;
}

.popup-menu-courses ul li a {
    font-size: 48px;
    line-height: 50px;
    font-family: "DIN Black";
    text-decoration: none;
    color: var(--blue);
    text-transform: uppercase;
}
.backdrop-courses {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    background-color: transparent;
}
.search-courses-mobile {
    display: none;
}
.accordion-inner-page .accordion-button {
    font-size: 32px;
    line-height: 50px;
    color: var(--blue);
}
.accordion-inner-page .accordion-button:not(.collapsed) {
    color: var(--blue);
}
.accordion-inner-page .accordion-body ul li {
    font-size: 24px;
    line-height: 36px;
}
.nav-white.fixed {
    position: fixed;
    z-index: 999999;
    animation: slide-in--down 420ms cubic-bezier(0.165, 0.84, 0.44, 1);
    -webkit-animation: slide-in--down 420ms cubic-bezier(0.165, 0.84, 0.44, 1);
}
.row-item-video.show {
    display: flex;
}
.button-download-newsroom a {
    display: block;
    cursor: pointer;
}
.pagination-newsroom a {
    display: block;
    cursor: pointer;
}
.float-home-img {
    position: absolute;
}

.outer-parallax {
    position: relative;
    width: 600px;
}

.outer-parallax .main-img {
    width: 100%;
}

.new-pagination-video {
    position: fixed;
    right: 30px;
    top: 50%;
    transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    -moz-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    -o-transform: translateY(-50%);
}
.truck-home {
    position: absolute;
    top: 47%;
    left: 49%;
    transform: translate(-50%, -50%);
    width: 187px;
}
@media (max-width: 1399px) {
    .content-trails {
        padding-left: 60px;
    }
    #header-about p {
        font-size: 14px;
    }
}
@media (max-width: 1199px) {
    .outCircleIconTruck {
        width: 287px;
        height: 180px;
        background-color: transparent;
        left: 48%;
        position: absolute;
        top: 32%;
        -moz-border-radius: 100px;
        -webkit-border-radius: 100px;
        border-radius: 100px;
        transform: translate(-50%, -50%);
        -webkit-transform: translate(-50%, -50%);
        -moz-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
        -o-transform: translate(-50%, -50%);
    }
    .innerIconTruck {
        width: 155px;
        height: 140px;
        background: transparent;
        -moz-border-radius: 50px;
        -webkit-border-radius: 50px;
        border-radius: 100px;
        position: absolute;
        left: 0px;
        top: 0px;
        background-color: transparent;
        display: block;
    }
    .outer-parallax {
        width: 500px;
    }

    .float-home-img {
        transform: scale(0.8);
    }

    .desc-video {
        width: 100%;
    }
    .outCircleFloatHomeIcon1 {
        left: 122px;
        top: 18px;
    }
    .outCircleFloatHomeIcon2 {
        width: 90px;
        height: 90px;
        left: 181px;
        top: 55px;
    }
    .outCircleFloatHomeIcon3 {
        width: 90px;
        height: 90px;
        right: -43px;
        top: 11px;
    }
    .outCircleFloatHomeIcon4 {
        width: 100px;
        height: 100px;
        top: 209px;
        right: -1px;
    }
    .outCircleFloatHomeIcon5 {
        width: 90px;
        height: 90px;
        right: 22px;
        bottom: 46px;
    }
    .outCircleFloatHomeIcon6 {
        width: 90px;
        height: 90px;
        left: 216px;
        bottom: 72px;
    }
    .outCircleFloatHomeIcon7 {
        width: 100px;
        height: 100px;
        left: -13px;
        top: 183px;
    }
    .title-content-newsroom h2 {
        font-size: 18px;
        line-height: 22px;
    }

    .title-content-newsroom {
        left: 10px;
        top: 10px;
        width: 180px;
    }

    .button-download-newsroom {
        width: 40px;
        left: 10px;
        bottom: 10px;
    }
    .title-content-trails h2,
    .title-content-trails span {
        font-size: 18px;
    }
    .inner {
        width: 187px;
        height: 169px;
    }
    .counterrotate {
        width: 187px;
        height: 169px;
    }
    .outCircle {
        width: 413px;
        height: 231px;
        top: 41%;
        left: 48%;
    }
    .content-landing {
        padding: 0 30px;
    }
    .logo-landing {
        margin-right: 80px;
    }
}

@media (max-width: 991px) {
    .outCircleFloatTruck3 {
        display: none;
    }

    .outCircleFloatTruck4 {
        display: none;
    }
    .right-col__header-trails {
        margin-top: 0;
    }
    .desc-item-truck {
        width: 100%;
        margin-top: 55px;
    }

    .map-truck {
        width: 600px;
        margin: 0 auto;
    }
    .map-truck > img {
        margin-bottom: 50px;
    }
    .outCircleFloatTruck1,
    .outCircleFloatTruck2 {
        display: none;
    }
    .popup-truck-1:after,
    .popup-truck-2:after,
    .popup-truck-3:after {
        background-color: transparent;
    }
    .outCircleIconTruck {
        width: 240px;
        height: 183px;
        top: 21%;
    }
    .popup-truck {
        position: relative;
        display: block;
    }

    .popup-truck-1,
    .popup-truck-2,
    .popup-truck-3 {
        right: unset;
        top: unset;
        bottom: unset;
        left: unset;
        margin: 24px 0;
        width: 100%;
    }
    .popup-truck.expanded {
        width: 100%;
    }

    .innerIconTruck {
        width: 100px;
        height: 90px;
    }
    .desc-item-truck {
        width: 100%;
        margin-top: 55px;
    }
    .row-reverse {
        flex-direction: column-reverse;
    }
    .title-careers {
        position: relative;
        z-index: 9;
    }
    .row-header-courses {
        flex-direction: column-reverse;
    }
    .left-header-courses {
        margin-top: 15px;
    }
    .img-header-courses {
        position: relative;
        width: 100%;
        bottom: 0;
    }
    .container-video {
        display: block;
    }
    .tiktok-swiper_nav {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 30px;
        gap: 15px;
    }
    .wrapper-tiktok {
        display: unset;
    }
    .item-tiktok {
        width: 100%;
    }
    .pagination-video {
        display: none;
    }
    .row-item-video {
        display: block;
        margin-bottom: 70px;
    }

    .text-video {
        margin-bottom: 35px;
        justify-content: flex-start;
    }
    .row-header__virtual-fair-2002 {
        flex-direction: column-reverse;
    }
    #frm-contact.success {
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        height: 400px;
    }

    .title-contact {
        width: 227px;
    }

    .form-contact {
        margin: 30px auto 0;
    }

    #frm-contact {
        width: 96%;
        height: auto;
    }

    .form-name-email__contact {
        flex-direction: column;
        align-items: stretch;
        gap: 0;
    }

    .form-name-email__contact .form-group-contact {
        width: 100%;
    }
    .title-content-newsroom h2 {
        font-size: 18px;
        line-height: 24px;
    }

    .title-content-newsroom {
        width: 150px;
        left: 15px;
        top: 15px;
    }

    .button-download-newsroom {
        width: 40px;
        left: 15px;
        bottom: 15px;
    }
    .item-content-newsroom {
        width: calc(33.3% - 20px);
        position: relative;
    }
    .left-col__header-newsroom {
        margin-bottom: 15px;
    }
    .right-col__header-trails {
        padding-top: 50px;
    }
    .form-trails {
        width: 100%;
        padding: 25px 30px 30px;
    }

    form.form-trails input {
        width: 100;
    }

    .form-group__informed {
        display: flex;
        align-items: center;
        justify-content: flex-start;
        margin-bottom: 23px;
        flex-wrap: wrap;
    }
    label.error {
        display: block;
        width: 100%;
        margin-top: 8px;
    }

    .form-group__informed .form-input {
        flex-grow: 1;
    }

    .form-group__informed:last-child {
        margin-bottom: 0;
    }
    .wrapper-title-trails article {
        width: auto;
    }
    #header-trails {
        padding-bottom: 0;
    }
    .title-content-trails {
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        height: auto;
    }
    .wrapper-title-trails {
        margin-left: 0;
        margin-bottom: 30px;
        margin-top: 30px;
    }
    .swiperTrails {
        width: 80%;
    }
    .content-trails {
        padding-left: 0;
    }
    .selected-career {
        display: flex;
        background-color: #ffd700;
        border: 2px solid #fff;
        width: 212px;
        height: 45px;
        color: #000;
        text-decoration: none;
        font-family: "DIN BLACK";
        justify-content: center;
        align-items: center;
        margin-top: -22px;
        font-size: 24px;
        position: relative;
        z-index: 9;
    }
    .selected-career img {
        transition: 0.3s;
        -webkit-transition: 0.3s;
        -moz-transition: 0.3s;
        -ms-transition: 0.3s;
        -o-transition: 0.3s;
        transform: rotate(0deg);
        -webkit-transform: rotate(0deg);
        -moz-transform: rotate(0deg);
        -ms-transform: rotate(0deg);
        -o-transform: rotate(0deg);
    }
    .selected-career.show img {
        transform: rotate(180deg);
        -webkit-transform: rotate(180deg);
        -moz-transform: rotate(180deg);
        -ms-transform: rotate(180deg);
        -o-transform: rotate(180deg);
    }
    .container-title-careers {
        position: relative;
    }

    .wrapper-title-careers {
        position: absolute;
        z-index: 9;
        display: none;
    }

    .wrapper-title-careers a {
        width: 212px;
    }
    .wrapper-title-careers {
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        margin: 0;
    }
    .box-info-career__right-top {
        margin-top: 0;
    }
    .left-col__header-careers {
        margin-top: -30px;
    }
    .row-header-careers {
        flex-direction: column-reverse;
    }

    .right-col__header-careers {
        width: 100%;
    }

    .left-col__header-careers article {
        width: calc(100% - 57px);
    }

    #header-careers {
        padding-bottom: 80px;
    }
    .inner {
        width: 100px;
        height: 90px;
    }
    .counterrotate {
        width: 100px;
        height: 90px;
    }
    .truck-home {
        width: 100%;
    }
    .outCircle {
        width: 296px;
        height: 180px;
        top: 42%;
    }
    .right-col__home-header {
        height: 500px;
    }
    .header-nav-white {
        padding-top: 150px;
    }

    img.img-about-header {
        margin: 35px 0 0;
    }
    .nav-white__logo {
        margin-right: 40px !important;
    }
    .nav-white .top-menu > li {
        list-style: none;
        margin-right: 20px;
    }
    .nav-white .has-submenu {
        position: relative;
        margin-right: 44px !important;
    }
    .nav-white .top-menu {
        background-color: #fff;
        padding: 0 30px;
    }
    .row-header-home {
        flex-direction: column-reverse;
    }

    .left-col__home-header h1 {
        max-width: 100%;
    }
    .left-col__home-header {
        padding-right: 0;
    }

    .header-home {
        padding: 100px 0;
    }
    #insider-experience {
        padding-bottom: 50px;
    }
    .content-landing {
        flex-direction: column;
        padding: 30px 0;
        justify-content: flex-start;
    }
    .logo-landing {
        margin: 40px 0 40px;
        width: 90%;
    }
    .desc-landing {
        width: 90%;
        max-width: unset;
    }
    .button-landing {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .thumbnails-trails-mobile img {
        width: 100%;
    }

    .thumbnails-trails-mobile {
        margin-top: 30px;
    }

    .title-content-trails h2,
    .title-content-trails span {
        font-size: 24px;
    }
}

@media (max-width: 767px) {
    .outCircle {
        width: 198px;
        height: 145px;
        top: 42%;
    }
    .inner,
    .counterrotate {
        width: 75px;
        height: 68px;
    }
    .map-truck {
        width: 90%;
    }

    .outCircleIconTruck {
        width: 40%;
        height: 23%;
        top: 19%;
    }

    .innerIconTruck {
        width: 60px;
        height: 60px;
    }
    .title-page-truck {
        width: 291px;
        margin-top: 75px;
    }
    .title-popup h2 {
        font-size: 18px;
    }

    .title-item-truck h2 {
        font-size: 32px;
    }
    .map-truck > img {
        margin-bottom: 40px;
    }
    .title-section {
        font-size: 24px;
        line-height: 28px;
        margin-bottom: 40px;
    }
    .counterrotateIconTruck {
        width: 60px;
        height: 60px;
    }
    .outer-parallax {
        width: 450px;
    }

    .outCircleFloatHomeIcon1,
    .outCircleFloatHomeIcon2,
    .outCircleFloatHomeIcon3,
    .outCircleFloatHomeIcon4,
    .outCircleFloatHomeIcon5,
    .outCircleFloatHomeIcon6,
    .outCircleFloatHomeIcon7 {
        transform: scale(0.85);
        -webkit-transform: scale(0.85);
        -moz-transform: scale(0.85);
        -ms-transform: scale(0.85);
        -o-transform: scale(0.85);
    }
    .outCircleFloatHomeIcon6 {
        width: 90px;
        height: 90px;
        left: 189px;
        bottom: 51px;
    }
    .outCircleFloatHomeIcon7 {
        width: 100px;
        height: 100px;
        left: -13px;
        top: 156px;
    }
    .title-video {
        font-size: 32px;
        line-height: 43px;
        padding: 12px 20px;
    }
    .content-courses {
        padding: 0 20px;
    }
    .courses-dropdown h2 {
        font-size: 24px;
        line-height: 28px;
    }

    .item-dropdown-courses > h2 {
        font-size: 24px;
        line-height: 28px;
    }

    .item-dropdown-courses .accordion-button {
        font-size: 20px;
        line-height: 30px;
    }

    .item-dropdown-courses .accordion-body ul li {
        font-size: 16px;
        line-height: 20px;
    }

    .item-dropdown-courses .accordion-button.collapsed::after {
        width: 15px;
        height: 15px;
    }

    .item-dropdown-courses .accordion-button::after {
        width: 15px;
        height: 15px;
    }

    .item-dropdown-courses .accordion-body ul li:after {
        width: 15px;
        height: 15px;
    }
    .popup-menu-courses ul li a {
        font-size: 24px;
        line-height: 28px;
    }
    .popup-menu-courses {
        box-shadow: 8px 8px 0px #0037cc;
        right: unset;
        bottom: unset;
        width: auto;
        padding: 15px;
        top: 66px;
        left: 0;
    }
    .popup-menu-courses.show {
        box-shadow: 8px 8px 0px #0037cc;
        right: unset;
        bottom: unset;
        width: auto;
        padding: 15px;
        top: 66px;
        left: 0;
    }

    .popup-menu-courses ul li a {
        margin: 9px 0;
        display: block;
    }
    .item-dropdown-courses .accordion-body ul li {
        font-size: 16px;
        line-height: 20px;
    }
    .courses-dropdown h2:after {
        width: 21px;
        height: 12px;
    }
    .search-course-desktop {
        display: none;
    }
    .search-courses {
        width: 100%;
    }
    .search-courses-mobile {
        display: block;
        margin-bottom: -20px;
    }
    .left-header-courses {
        margin-bottom: 10px;
    }
    .left-header-courses article {
        background-color: #fff;
        padding: 20px 30px;
        border: 5px solid var(--blue);
        margin-left: 20px;
        margin-top: -5px;
    }
    .img-right-header-virtual-fair-2021 {
        margin-top: 40px;
    }
    .subtitle-tiktok {
        width: calc(100% - 44px);
    }
    .title-virtual-fair-2022 {
        width: 230px;
    }
    .img-right-header-virtual-fair-2022 {
        margin-top: 30px;
    }
    .header-left-virtual-fair-2022 {
        margin-top: 30px;
    }
    #frm-contact.success h3 {
        font-size: 24px;
        line-height: 30px;
        font-family: "DIN Black";
        color: var(--blue);
    }
    .h-full {
        height: auto;
    }
    .form-group-contact label.error[for="message"] {
        top: 0;
        left: 80px;
    }
    .form-group-contact textarea {
        min-height: 180px;
    }
    .select-selected:after {
        border: 10px solid transparent;
        border-color: var(--blue) transparent transparent transparent;
        right: -28px;
    }
    .custom-select {
        margin-right: 25px;
    }
    .form-group-contact label {
        font-size: 16px;
        line-height: 20px;
    }

    .form-name-email__contact {
        gap: 0;
    }
    .select-items div {
        font-size: 15px;
        line-height: 21px;
        padding: 7px 10px;
    }

    .select-items {
        border: 3px solid var(--blue);
    }
    .form-name-email__contact .form-group-contact input {
        border-bottom: 3px solid var(--blue);
        font-size: 16px;
        line-height: 20px;
    }

    .form-group-contact input,
    .form-group-contact textarea {
        font-size: 16px;
        line-height: 20px;
    }
    .select-selected {
        min-height: 27px;
        border-bottom: 3px solid var(--blue);
        font-size: 16px;
    }
    .form-group-contact ::-webkit-input-placeholder {
        font-size: 16px;
        line-height: 20px;
    }

    .form-group-contact ::-ms-input-placeholder {
        font-size: 16px;
        line-height: 20px;
    }

    .form-group-contact ::placeholder {
        font-size: 16px;
        line-height: 20px;
    }
    .form-contact {
        margin: 115px 0 0;
    }

    .form-group-contact label {
        font-size: 16px;
        line-height: 20px;
    }

    #frm-contact {
        padding: 20px 15px;
    }
    .wrapper-content-newsroom {
        justify-content: space-between;
    }

    .title-content-newsroom h2 {
        font-size: 16px;
        line-height: 19px;
    }

    .title-content-newsroom {
        width: 141px;
        left: 8px;
        top: 8px;
    }

    .date-news-room {
        font-size: 16px;
        line-height: 19px;
    }
    .item-content-newsroom {
        width: calc(50% - 10px);
    }
    .button-download-newsroom {
        width: 28px;
        bottom: 8px;
        left: 10px;
    }
    .title-page {
        font-size: 32px;
        padding-top: 71px;
    }
    .left-col__header-trails {
        margin-top: 70px;
    }

    .header-nav-white {
        padding-top: 0;
    }
    .title-about {
        width: 289px;
    }
    .nav-white__logo {
        display: none;
    }
    .hamburger {
        display: flex;
        position: fixed;
        right: 30px;
        top: 30px;
        z-index: 5;
        justify-content: center;
        align-items: center;
    }
    .hamburger-logo {
        width: 60px;
        margin-right: 10px;
    }
    .inner-hamburger {
        background-color: #fff;
        width: 120px;
        height: 55px;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .inner-hamburger::after {
        content: "";
        position: absolute;
        width: 100%;
        height: 100%;
        right: -6px;
        bottom: -6px;
        background-color: #000;
        z-index: -1;
    }
    .top-menu {
        flex-direction: column;
        align-items: flex-start;
        padding: 25px;
        background-color: #fff;
        display: inline-flex;
    }
    .nav-white .top-menu {
        padding: 25px;
        height: auto;
    }
    .wrapper-top-nav {
        opacity: 0;
        z-index: -999;
        transform: translateY(-10px);
        -webkit-transform: translateY(-10px);
        -moz-transform: translateY(-10px);
        -ms-transform: translateY(-10px);
        -o-transform: translateY(-10px);
        transition: 0.3s;
        -webkit-transition: 0.3s;
        -moz-transition: 0.3s;
        -ms-transition: 0.3s;
        -o-transition: 0.3s;
        z-index: -9999;
    }
    .wrapper-top-nav.show {
        opacity: 1;
        z-index: 999;
        transform: translateY(0);
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
    }

    .nav-home,
    .nav-white {
        left: unset;
        padding: 0;
        right: 62px;
        z-index: -999;
        transition: 0.3s;
        -webkit-transition: 0.3s;
        -moz-transition: 0.3s;
        -ms-transition: 0.3s;
        -o-transition: 0.3s;
        position: fixed;
        top: 85px;
    }

    .nav-white {
        width: unset;
    }
    .submenu.show {
        padding: 0;
        transform: unset;
        top: 0;
        position: relative;
    }
    .top-menu li a {
        color: var(--blue);
    }
    .has-submenu::after {
        background: url(../img/caret-down-blue.svg) no-repeat center;
        background-size: contain;
        top: 12px;
    }
    .has-submenu.open::after {
        top: 12px;
    }
    #nav-icon {
        width: 30px;
        height: 19px;
        position: relative;
        -webkit-transform: rotate(0deg);
        -moz-transform: rotate(0deg);
        -o-transform: rotate(0deg);
        transform: rotate(0deg);
        -webkit-transition: 0.5s ease-in-out;
        -moz-transition: 0.5s ease-in-out;
        -o-transition: 0.5s ease-in-out;
        transition: 0.5s ease-in-out;
        cursor: pointer;
    }
    .top-menu > li {
        margin-right: 0;
    }
    .submenu {
        position: absolute;
        padding: 0;
        text-align: left;
        transform: translateY(0);
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
        transition: unset;
        -webkit-transition: unset;
        -moz-transition: unset;
        -ms-transition: unset;
        -o-transition: unset;
        padding-left: 20px !important;
    }
    .nav-white .has-submenu {
        margin-right: 0 !important;
    }

    .has-submenu {
        margin-right: 0 !important;
    }

    .top-menu li {
        margin: 6px 0;
    }
    #nav-icon span {
        display: block;
        position: absolute;
        height: 3px;
        width: 100%;
        background: var(--blue);
        border-radius: 9px;
        opacity: 1;
        left: 0;
        -webkit-transform: rotate(0deg);
        -moz-transform: rotate(0deg);
        -o-transform: rotate(0deg);
        transform: rotate(0deg);
        -webkit-transition: 0.25s ease-in-out;
        -moz-transition: 0.25s ease-in-out;
        -o-transition: 0.25s ease-in-out;
        transition: 0.25s ease-in-out;
    }
    #nav-icon span:nth-child(1) {
        top: 0px;
    }

    #nav-icon span:nth-child(2),
    #nav-icon span:nth-child(3) {
        top: 8px;
    }

    #nav-icon span:nth-child(4) {
        top: 16px;
    }

    #nav-icon.open span:nth-child(1) {
        top: 20px;
        width: 0%;
        left: 50%;
    }

    #nav-icon.open span:nth-child(2) {
        -webkit-transform: rotate(45deg);
        -moz-transform: rotate(45deg);
        -o-transform: rotate(45deg);
        transform: rotate(45deg);
    }

    #nav-icon.open span:nth-child(3) {
        -webkit-transform: rotate(-45deg);
        -moz-transform: rotate(-45deg);
        -o-transform: rotate(-45deg);
        transform: rotate(-45deg);
    }

    #nav-icon.open span:nth-child(4) {
        top: 18px;
        width: 0%;
        left: 50%;
    }
    .content-footer {
        height: 154px;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .content-footer {
        align-items: flex-start;
    }
    .copyright {
        margin-bottom: 12px;
    }
}
@media (max-width: 575px) {
    .outer-parallax {
        width: 300px;
    }
    .outCircleFloatHomeIcon1,
    .outCircleFloatHomeIcon2,
    .outCircleFloatHomeIcon3,
    .outCircleFloatHomeIcon4,
    .outCircleFloatHomeIcon5,
    .outCircleFloatHomeIcon6,
    .outCircleFloatHomeIcon7 {
        transform: scale(0.85);
        -webkit-transform: scale(0.55);
        -moz-transform: scale(0.85);
        -ms-transform: scale(0.85);
        -o-transform: scale(0.85);
    }
    .outCircleFloatHomeIcon1 {
        left: 65px;
        top: -22px;
    }
    .outCircleFloatHomeIcon2 {
        width: 90px;
        height: 90px;
        left: 92px;
        top: 8px;
    }
    .outCircleFloatHomeIcon3 {
        width: 85px;
        height: 85px;
        right: -43px;
        top: -5px;
    }
    .outCircleFloatHomeIcon4 {
        width: 100px;
        height: 100px;
        top: 88px;
        right: -15px;
    }
    .outCircleFloatHomeIcon5 {
        width: 90px;
        height: 90px;
        right: -5px;
        bottom: 16px;
    }
    .outCircleFloatHomeIcon6 {
        width: 90px;
        height: 90px;
        left: 112px;
        bottom: 24px;
    }
    .outCircleFloatHomeIcon7 {
        width: 100px;
        height: 100px;
        left: -17px;
        top: 91px;
    }
    .left-col__header-careers article {
        width: calc(100% - 57px);
        margin-left: 47px;
    }
    .title-careers {
        width: 292px;
    }
    .left-col__header-careers {
        margin-top: -30px;
    }
    .inner {
        width: 80px;
        height: 80px;
    }
    .counterrotate {
        width: 80px;
        height: 80px;
    }
    .outCircle {
        width: 200px;
        height: 100px;
    }
    .right-col__home-header {
        height: 300px;
    }
    .left-col__home-header h1 {
        font-size: 16px;
        line-height: 22px;
    }
}

@media (max-width: 480px) {
    .outCircleFloatHomeIcon3 {
        width: 85px;
        height: 85px;
        right: -35px;
        top: -5px;
    }
    .outer-parallax {
        width: 320px;
    }
    .outCircle {
        width: 141px;
        height: 100px;
    }
    .inner,
    .counterrotate {
        width: 50px;
        height: 45px;
    }
}
.wrapper-tiktok-iframe {
    padding-top: 143%;
    position: relative;
    width: 80%;
    margin: 0 auto;
}
.wrapper-tiktok-iframe iframe {
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
}
@media (min-width: 768px) {
    .wrapper-tiktok-iframe {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 450px;
        margin: 0 auto;
        position: relative;
        padding-top: 116%;
    }
}
@media (min-width: 992px) {
    .tiktokSwiper .swiper-wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 20px;
    }
    .wrapper-tiktok-iframe {
        position: relative;
        width: 100%;
        padding-top: 180%;
    }
    .item-tiktok {
        width: calc(16% - 20px);
    }
    .wrapper-tiktok-iframe iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
}	
	.print-content{
	width: 100%; margin-left: 0; padding-left: 0;padding-top: 0
	}
	.bp-section{padding: 0 !important}
	.bp-container{padding:0; margin: 0}
	.bp-section-pagetitle{display: none}
</style>

<section class="landing" style="background: #0037cc url(https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/img/grid-background.svg) no-repeat center;width:100vw;">
    <div class='container-fluid'>
        <div class='row'>
            <div class='col-12'>
                <div class="content-landing">
                    <img src="https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/img/logo-landing.svg" alt="logo" class="logo-landing">
                    <div class="desc-landing">
                        <article>
                            <p>Step into your future and take a glimpse of Singapore in the next 50 years. While we cannot be sure what exactly is to come, there is certainty that our climate will require us to adapt. What will our everyday lives look like? How will it change and how will we evolve with the times?</p>
                            <p>You can have a part to play. </p>
                        </article>
                        <div class="button-landing">
                            <div class="item__button-landing">
                                <div class="item-button-truck">
                                    <a href="<?= site_url('truck') ?>">
                                        <span>
                                            <img src="https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/img/icon-truck.svg" alt="truck">
                                        </span>
                                    </a>
                                    <h4>Spot our Truck!</h4>                                    
                                </div>
                                <div class="item-button-find-out-more">
                                    <a href="<?= site_url( 'home' ) ?>">
                                        <div class="container-caret">
                                            <svg width="20" height="27" viewBox="0 0 20 27" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path d="M0.193848 27V0L20.0001 13.5022L0.193848 27Z" fill="white"/>
                                            </svg>
                                            <svg width="20" height="27" viewBox="0 0 20 27" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path d="M0.193848 27V0L20.0001 13.5022L0.193848 27Z" fill="white"/>
                                            </svg>
                                            <svg width="20" height="27" viewBox="0 0 20 27" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path d="M0.193848 27V0L20.0001 13.5022L0.193848 27Z" fill="white"/>
                                            </svg>
                                        </div>
                                    </a>
                                    <h4>Find Out More</h4>                                    
                                </div>
                            </div>
                        </div>
<div class="logo-footer-landing">
                            <img src="https://dstnct-dev.com/ctrl-shift/wp-content/themes/ctrlshift/img/logo-footer-landing.png" alt="logo footer" class="img-full">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>