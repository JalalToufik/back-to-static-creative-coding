<script>
    import '../lib/styles/fonts.css';

</script>


<slot />


<style>

    :global(*){
        box-sizing: border-box;
        text-decoration: none;
        list-style: none;
        margin: 0;
        padding: 0;
        font-family: var(--Apercu-font);
    }

    /* Color variable */

    :global(:root){

        --Bg-Dark-Blue: #051d1d;

        --Yellow-Primary: #FFDA1D;
        --Blue-Secondary: #3DBAE1;

        --White: #FFFFFF;
        --Black: #000;

        --Apercu-Font: 'Apercu pro', sans-serif;
        --Paragraph-Font: 'Jubilat', serif;
        --Header-Font: 'Kirang Haerang', sans-serif;

        --Header-Font2: 'Scorched Earth', sans-serif;

    }
    :global(html) {
        scroll-behavior: smooth;
    }

    :global(body) {
        background-color: var(--Bg-Dark-Blue);
        color: var(--White);
        width: 100%;
        height: 100vh;
        overflow: hidden;
        overflow-y: scroll;
    }


</style>