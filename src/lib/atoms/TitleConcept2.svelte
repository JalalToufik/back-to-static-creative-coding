<script>

</script>


<section>
    <div class="buildings" aria-label="building illustration">
        <h1>
            <div class="title-where word">
                <span>W</span>
                <span>H</span>
                <span>E</span>
                <span>R</span>
                <span>E</span>
            </div>
            <div class="title-the-real word">
                <div>
                    <span>T</span>
                    <span>H</span>
                    <span>E</span>
                </div>
                <div>
                    <span>R</span>
                    <span>E</span>
                    <span>A</span>
                    <span>L</span>
                </div>
            </div>
            <div class="title-legends word">
                <span>L</span>
                <span>E</span>
                <span>G</span>
                <span>E</span>
                <span>N</span>
                <span>D</span>
                <span>S</span>
            </div>
            <div class="title-begin word">
                <span>B</span>
                <span>E</span>
                <span>G</span>
                <span>I</span>
                <span>N.</span>
            </div>
        </h1>
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

    .buildings::before{
        content: "";
        position: absolute;
        width: clamp(10em, 40vw, 35em);
        height: clamp(10em, 40vw, 35em);
        border-radius: 50%;
        background-color: #0B3A35;
    }

    h1 {
        position: absolute;
        display: flex;
        flex-direction: column;
        color: var(--White);
        font-family: var(--Header-Font);
    }

    section span {
        font-size: clamp(36px, 9vw, 128px);
        font-family: var(--Header-Font);
        text-transform: uppercase;
        display: flex;
        height: fit-content;
        line-height: 62%;
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