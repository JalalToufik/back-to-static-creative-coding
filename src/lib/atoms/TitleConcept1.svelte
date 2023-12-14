<script>

</script>

<div class="container">
    <h1>
        <div class="title-post word">
            <span>P</span>
            <span>O</span>
            <span>S</span>
            <span>T</span>
        </div>
        <div class="title-apocalyptic word">
            <span>A</span>
            <span>P</span>
            <span>O</span>
            <span>C</span>
            <span>A</span>
            <span>L</span>
            <span>Y</span>
            <span>P</span>
            <span>T</span>
            <span>I</span>
            <span>C</span>
        </div>
    </h1>
</div>


<style>

@import url('https://fonts.googleapis.com/css2?family=Black+Ops+One&display=swap');

    .container {
        display: flex;
        flex-direction: column;
        width: 40%;
        transform: rotate(-2deg);
    }

    h1 {
        color: var(--White);
        font-family: var(--Header-Font2);
        font-family: 'BlackOpsOne';
    }

    .container span {
        font-size: clamp(36px, 9vw, 128px);
        font-family: var(--Header-Font2);
        text-transform: uppercase;
        display: flex;
        height: fit-content;
        line-height: 62%;
    }

    .title-post, .title-apocalyptic {
        display: flex;
        align-items: flex-end;
    }

    span{
        transform:translateY(-100vh);
        animation: drop 3.1s linear forwards;
    }

    .title-post{
        color: var(--Yellow-Primary);
    }

    .title-post span:nth-child(1){
        animation-delay: 0.1s;
    }
    .title-post span:nth-child(2){
        animation-delay: 0.2s;
    }
    .title-post span:nth-child(3){
        animation-delay: 0.3s;
    }
    .title-post span:nth-child(4){
        animation-delay: 0.4s;
    }

    /* ====================== */

    .title-apocalyptic span:nth-child(1){
        animation-delay: 0.5s;
    }
    .title-apocalyptic span:nth-child(2){
        animation-delay: 0.6s;
    }
    .title-apocalyptic span:nth-child(3){
        animation-delay: 0.7s;
    }
    .title-apocalyptic span:nth-child(4){
        animation-delay: 0.8s;
    }
    .title-apocalyptic span:nth-child(5){
        animation-delay: 0.9s;
    }
    .title-apocalyptic span:nth-child(6){
        animation-delay: 1.0s;
    }
    .title-apocalyptic span:nth-child(7){
        animation-delay: 1.1s;
    }
    .title-apocalyptic span:nth-child(8){
        animation-delay: 1.2s;
    }
    .title-apocalyptic span:nth-child(9){
        animation-delay: 1.3s;
    }
    .title-apocalyptic span:nth-child(10){
        animation-delay: 1.4s;
    }
    .title-apocalyptic span:nth-child(11){
        animation-delay: 1.5s;
    }


    h1 > div{
        padding: .1em;
    }



    @keyframes drop {
        0% {
            transform: translateY(-100vh);
            animation-timing-function: ease-in; 
        }
        40% {
            transform: translateY(-30vh);
            animation-timing-function: ease-in; 
        }
        65% {
            transform: translateY(-20vh);
            animation-timing-function: ease-in; 
        }
        82% {
            transform: translateY(-10vh);
            animation-timing-function: ease-in; 
        }
        92% {
            transform: translateY(-5vh);
            animation-timing-function: ease-in; 
        }
        25%, 55%, 75%, 87%, 97%, 100% {
            transform: translateY(0);
            animation-timing-function: ease-out; 
        }
    }

    
</style>