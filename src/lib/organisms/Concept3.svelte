<script>

    // import {  } from '$lib/index.js';

</script>

<section>
    <div>
        <h1>
            Brutalist
        </h1>
        <div class="kader">
            <div class="box">
                <div class="box-inner">
                    <h2>Wave</h2>
                </div>
                <div class="twisted-lines"></div>
                <p>
                    Brutalist: Is a graphic design that uses large, simple shapes. 
                    It is also common to use colors that are strong and striking. 
                    That ultimately gives a rough appearance of brutalism.
                </p>
            </div>
        </div>
        <h1>
            Brutalist
        </h1>
    </div>
</section>

<style>

    @import url('https://fonts.googleapis.com/css2?family=Dela+Gothic+One&display=swap');

    :root{
        --dark-blue: lch(6 10 223);
        --regular-blue: lch(54 30 216);
        --light-blue: lch(93 22.34 211.51);
    }

    section {
        background-image: url(/assets/ocean.avif);
        background-size: cover;
        background-repeat: no-repeat;
        padding-top: 5em;
        height: 100vh;
    }

    section::before{
        content: '';
        display: block;
        height: 100vh;
        position: absolute;
        z-index: 0;
        width: 100%;
        bottom: 0;
        background-color: rgb(2 10 11 / 84%);
        backdrop-filter: invert(70%);
        backdrop-filter: blur(20px);
        -webkit-backdrop-filter: blur(25px);
    }

    section > div {
        margin: 1em 4em;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    h1{
        display: inline-block;
        font-size: 3.6em;
        text-transform: uppercase;
        font-family: Dela Gothic One;
        text-align: center;
        height: 1.5em;
        margin: 0 auto;
        color: #ffffff;
        width: fit-content;
        border-bottom: solid 4px var(--regular-blue);
        position: relative;
    }

    h1:nth-of-type(2){
        transform: rotateX(180deg);
    }

    h2{
        text-transform: uppercase;
        text-align: right;
        padding: .25em .5em;
        font-size: 2.5em;
        font-family: Dela Gothic One;
        -webkit-text-stroke: 2px var(--regular-blue); 
        color: #001A26;
    }

    .kader{
        margin: 0 auto;
        height: 26em;
        width: 28em;
    }

    .box {
        position: relative;
        width: 28em;
        height: 22em;
        padding-top: 1em;
        padding-bottom: 3.5em;
    }

    .box:before {
        position: absolute;
        content: '';
        top: 50%; left: 50%;
        transform: translate(-50%, -50%) scale(.7);
        filter: blur(0);
        opacity: 1;
        transition: all 450ms cubic-bezier(0.23, 1, 0.32, 1);
    }

    
    .box-inner {
        display: flex;
        flex-direction: column-reverse;
        position: relative;
        width: 100%;
        height: 100%;
    }

    .box-inner::before{
        content: '';
        background-image: url(/assets/arrows.svg);
        background-size: cover;
        background-repeat: no-repeat;
        width: 1em;
        height: 4em;
        position: absolute;
        bottom: 0.5em;
        left: 0.5em;
        transform: rotate(180deg);
    }

    .box-inner::after{
        content: '';
        background-image: url(/assets/arrows.svg);
        background-size: cover;
        background-repeat: no-repeat;
        width: 1em;
        height: 4em;
        position: absolute;
        top: 0.5em;
        right: 0.5em;
    }


    .box:before,
    .box-inner {
        background-color: var(--regular-blue);
        
        background-image: 
            url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' width='1600' height='198'%3e%3cdefs%3e%3clinearGradient id='a' x1='50%25' x2='50%25' y1='-10.959%25' y2='100%25'%3e%3cstop stop-color='%3DBAE1' stop-opacity='.25' offset='0%25'/%3e%3cstop stop-color='%3DBAE1' offset='100%25'/%3e%3c/linearGradient%3e%3c/defs%3e%3cpath fill='url(%23a)' fill-rule='evenodd' d='M.005 121C311 121 409.898-.25 811 0c400 0 500 121 789 121v77H0s.005-48 .005-77z'/%3e%3c/svg%3e"),
            url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' width='1600' height='198'%3e%3cdefs%3e%3clinearGradient id='a' x1='50%25' x2='50%25' y1='-10.959%25' y2='100%25'%3e%3cstop stop-color='%70E7FF' stop-opacity='.25' offset='0%25'/%3e%3cstop stop-color='%3DBAE1' offset='100%25'/%3e%3c/linearGradient%3e%3c/defs%3e%3cpath fill='url(%23a)' fill-rule='evenodd' d='M.005 121C311 121 409.898-.25 811 0c400 0 500 121 789 121v77H0s.005-48 .005-77z'/%3e%3c/svg%3e"),
            url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' width='1600' height='198'%3e%3cdefs%3e%3clinearGradient id='a' x1='50%25' x2='50%25' y1='-10.959%25' y2='100%25'%3e%3cstop stop-color='%70E7FF' stop-opacity='.25' offset='0%25'/%3e%3cstop stop-color='%3DBAE1' offset='100%25'/%3e%3c/linearGradient%3e%3c/defs%3e%3cpath fill='url(%23a)' fill-rule='evenodd' d='M.005 121C311 121 409.898-.25 811 0c400 0 500 121 789 121v77H0s.005-48 .005-77z'/%3e%3c/svg%3e"),
            url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' width='1600' height='198'%3e%3cdefs%3e%3clinearGradient id='a' x1='50%25' x2='50%25' y1='-10.959%25' y2='100%25'%3e%3cstop stop-color='%D7F0F3' stop-opacity='.25' offset='0%25'/%3e%3cstop stop-color='%3DBAE1' offset='100%25'/%3e%3c/linearGradient%3e%3c/defs%3e%3cpath fill='url(%23a)' fill-rule='evenodd' d='M.005 121C311 121 409.898-.25 811 0c400 0 500 121 789 121v77H0s.005-48 .005-77z'/%3e%3c/svg%3e");
        background-repeat: repeat-x;
        background-size: 1400px 80%;
        background-position: 0 130%, -50px 130%, 500px 130%;
        
        animation: 50s waves linear infinite forwards;
    }

    @keyframes waves {
        to {
            background-position: 1600px 130%, 3150px 130%, 5300px 130%;
        }
    }

    .twisted-lines{
        background-image: url(/assets/twisted-line.svg);
        background-repeat: no-repeat;
        background-size: cover;
        width: 100%;
        margin: 0 0 1em 0;
        height: .7em;
    }

    p{
        font-family: var(--Apercu-Font);
        font-size: .85em;
        padding: .5em;
    }

    /* 48em = 768px */

    @media (min-width: 48em) {

        h1{
            font-size: 5em;
        }

        .kader, .box{
            width: 38.8em;
            height: 28em
        }

        .box{
            padding-top: 3em;
            padding-bottom: 7.5em;
        }

        .box-inner::before{
            width: 2em;
            height: 7em;
            bottom: 1.5em;
            left: 1.5em;
        }

        .box-inner::after{
            width: 2em;
            height: 7em;
            top: 1.5em;
            right: 1.5em;
        }

        h2{
            font-size: 3.5em;
        }

        p{
            font-size: 1em;
            margin-bottom: 5em;
        }

    }

</style>





