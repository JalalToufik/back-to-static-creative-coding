<script>
        import { BtnSecondary } from '$lib/index.js';
</script>

    <section>
        <div class="intro">
            <p class="intro-text" > 
                We are dedicated to providing these children with a second chance in life, 
                ensuring they have access to education, shelter, nutrition, and an opportunity 
                to pursue their dreams of becoming top football players.
            </p>
            <BtnSecondary href="/about" title="About Us"> </BtnSecondary>
        </div>
    </section>

<style>

    section{
        position: absolute;
        top: 15em;
        z-index: 5;
        width: 100vw;
    }

    /* ============== INTRO ABOUT - SECTION START ==============*/

    .intro {
        width: 100%;
        height: clamp(25em, 80vw, 80em);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;

        background-image: url(/assets/intro-mask.svg);
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center center;

        padding: 0 14vw;
    }

    .intro-text {
        display: flex;
        flex-direction: column;
        color: var(--Black);
        font-family: var(--Paragraph-Font);
        font-size: clamp(2vw, 4vw, 57px);
        line-height: 96%;
    }

    @media (min-width: 350px) {

        section{
            top: 20em;
        }
    }

    @media (min-width: 410px) {

        section{
            top: 25em;
        }
    }

    @media (min-width: 430px) {

        section{
            top: 27em;
        }
    }

    @media (min-width: 520px) {

        section{
            top: 33em;
        }
    }

    @media (min-width: 700px) {

        section{
            top: 36em;
        }
    }

    @media (min-width: 768px) {

        section{
            top: 41em;
        }
    }

    @media (min-width: 820px) {

        section{
            top: 53em;
        }
    }

    @media (min-width: 1000px) {

        section{
            top: 62em;
        }
    }


</style>
