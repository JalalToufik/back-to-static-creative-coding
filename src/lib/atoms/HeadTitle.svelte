<script>

</script>

<div class="container">
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


<style>

    .container {
        display: flex;
        flex-direction: column;
        width: 40%;
        transform: rotate(-2deg);
    }

    h1 {
        font-weight: normal;
        color: var(--White);
    }

    .container span {
        font-size: clamp(36px, 9vw, 128px);
        font-family: 'Kirang Haerang';
        text-transform: uppercase;
        display: flex;
        height: fit-content;
        line-height: 62%;
    }

    .title-where, .title-the-real, .title-the-real div, .title-legends, .title-begin {
        display: flex;
        align-items: flex-end;
    }

    .title-where{
        animation-delay:0.1s;
    }

    .title-the-real{
        gap: .4em;
        animation-delay:0.3s;
    }

    .title-legends{
        color: var(--Yellow-Primary);
        animation-delay:0.5s;
    }

    h1 > div{
        padding: .1em;
    }

    .word{
        
        transform:translateY(-100vh);
        animation:drop 3.5s cubic-bezier(0, 0, 0.35, 1) infinite;  
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