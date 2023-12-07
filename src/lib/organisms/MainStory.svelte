<script>
</script>

<section>

    <div class="roll-container">
        <p class="roll-text">Where the real <span class="yellow">legends</span> begin</p>
    </div>

</section>


<style>

    section{
        padding: 4em 6em 10em 6em;
        overflow: hidden;
    }

    .yellow{
        color: var(--Yellow-Primary);
    }

    
    .roll-container {
        height: 15em;
    }

    .roll-text {
        width: 100vh;
        font-size: 6em;
        font-family: var(--Paragraph-Font);
        margin-bottom: 8em;
    
        -moz-transform: translateX(100%);
        -webkit-transform: translateX(100%);
        transform: translateX(100%);
        
        -moz-animation: my-animation 9s linear infinite;
        -webkit-animation: my-animation 9s linear infinite;
        animation: my-animation 9s linear infinite;
    }

    /* for Firefox */
    @-moz-keyframes my-animation {
        from { -moz-transform: translateX(-100%); }
        to { -moz-transform: translateX(100%); }
    }

    /* for Chrome */
    @keyframes my-animation {
        from { -webkit-transform: translateX(-100%); }
        to { -webkit-transform: translateX(100%); }
    }

    @media only screen and (max-width: 900px) {
        .roll-text {
        font-size: 4em;
        }

        .roll-container {
        height: 8em;
    }
    }

    @media only screen and (max-width: 600px) {
        
        section {
            padding: 2em;
        }

        .roll-text {
        font-size: 3em;
        }
    }


</style>
