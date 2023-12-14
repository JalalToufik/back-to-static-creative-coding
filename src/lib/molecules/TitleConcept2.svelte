<script>

</script>


<section>
    <div class="buildings" aria-label="building illustration">
        <div class="circle">
            <h1>
                <div class="title-where word">
                    <span style="--i:1">W</span>
                    <span style="--i:2">H</span>
                    <span style="--i:3">E</span>
                    <span style="--i:4">R</span>
                    <span style="--i:5">E</span>
                </div>
                <div class="title-the-real word">
                    <div>
                        <span style="--i:6">T</span>
                        <span style="--i:7">H</span>
                        <span style="--i:8">E</span>
                    </div>
                    <div>
                        <span style="--i:9">R</span>
                        <span style="--i:10">E</span>
                        <span style="--i:11">A</span>
                        <span style="--i:12">L</span>
                    </div>
                </div>
                <div class="title-legends word">
                    <span style="--i:13">L</span>
                    <span style="--i:14">E</span>
                    <span style="--i:15">G</span>
                    <span style="--i:16">E</span>
                    <span style="--i:17">N</span>
                    <span style="--i:18">D</span>
                    <span style="--i:19">S</span>
                </div>
                <div class="title-begin word">
                    <span style="--i:20">B</span>
                    <span style="--i:22">E</span>
                    <span style="--i:23">G</span>
                    <span style="--i:24">I</span>
                    <span style="--i:25">N</span>
                </div>
            </h1>
            <a href="#about-section"> 
                <svg class="arrow" xmlns="http://www.w3.org/2000/svg" fill="Yellow" height="50" viewBox="0 -960 960 960" width="50">
                    <path 
                        d="m480-320 160-160-56-56-64 64v-168h-80v168l-64-64-56 56 160 160Zm0 240q-83 
                        0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 
                        0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Zm0-80q134 
                        0 227-93t93-227q0-134-93-227t-227-93q-134 0-227 93t-93 227q0 134 93 227t227 93Zm0-320Z"
                    />
                </svg>
            </a>
        </div>
    </div>
</section>


<style>

    section {
        background-image: url(/assets/bg-brazillian-kids.jpg);
        background-repeat: no-repeat;
        background-position: center;
        background-position-y: 0em;
        background-size: cover;
        overflow: hidden;
        height: clamp(16em, 120vw, 90em);
        padding-top: 5em;
        display: flex;
        justify-content: center;
        align-items: top;
    }

    .buildings{
        position: relative;
        z-index: 3;

        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        background-image: url(/assets/building.svg);
        background-position-x: -1.5em;
        background-repeat: no-repeat;
        background-size: cover;
        width: clamp(14em, 70vw, 60em);
        height: clamp(14em, 70vw, 60em);
    }

    .circle{
        position: absolute;
        width: clamp(10em, 40vw, 35em);
        height: clamp(10em, 40vw, 35em);
        border-radius: 50%;
        background-color: #0B3A35;

        display: flex;
        justify-content: center;
        flex-wrap: wrap-reverse;
        align-content: flex-start;
    }

    .circle > a{
        position: inherit;
        z-index: 12;

        display: flex;
        align-items: end;
        padding: 1em;

    }

    .arrow{
        fill: var(--Yellow-Primary);
    }


    h1 {
        padding: 1.5em;
        position: relative;
        display: flex;
        flex-direction: column;
        color: var(--White);
        font-family: var(--Header-Font);
    }

    h1 span {
        position: relative;
        display: inline-flex;
        font-size: clamp(36px, 9vw, 128px);
        font-family: var(--Header-Font);
        text-transform: uppercase;
        display: flex;
        height: fit-content;
        line-height: 62%;

        animation: flip 6s infinite;
        animation-delay: calc(.2s * var(--i));
    }

    @keyframes flip {
        80%,0% {
            transform: rotateY(-360deg);
        }
    }

    .title-where,
    .title-the-real,
    .title-the-real div,
    .title-legends,
    .title-begin {
        display: flex;
        align-items: flex-end;
    }

    .title-legends{
        color: var(--Yellow-Primary);
        margin: 0 0 0 auto;
        width: fit-content;
    }

    .title-the-real {
        width: fit-content;
        margin: 0 0 0 auto;
        gap: 2vw;
    }

    .title-where span:nth-of-type(1),
    .title-where span:nth-of-type(2),
    .title-the-real>div:nth-of-type(2) span:nth-of-type(2) {
        font-size: clamp(2rem, 11.5vw, 168px);
    }


    .title-legends span {
        font-size: clamp(40px, 10vw, 144px);
    }

    .title-legends span:nth-of-type(1),
    .title-legends span:nth-of-type(7) {
        font-size: clamp(36px, 9vw, 128px);
    }


    .title-legends span:nth-of-type(4) {
        font-size: clamp(29px, 7.2vw, 104px);
    }

    .title-begin {
        width: fit-content;
        margin: 0 auto;
    }

    .title-begin span:nth-of-type(2),
    .title-begin span:nth-of-type(3) {
        font-size: clamp(32px, 7.8vw, 112px);
    }

    h1 > div{
        padding: .1em;
    }

    /* 1000px */
    @media (min-width: 62.5em)  {

        .buildings{
            background-position-x: -2em;
        }
    }

    /* 1400px */
    @media (min-width: 87.5em)  {

        .buildings{
            background-position-x: -3em;
        }
    }

    /* 1600px */
    @media (min-width: 100em)  {

        .buildings{
            background-position-x: -4em;
        }
    }

    
</style>