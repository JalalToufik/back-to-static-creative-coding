<script>
	export let href, title;
</script>


    <a class="nav-link" {href}>{title}</a>


<style>

    a {
        color: var(--White);
        font-family: var(--Apercu-Font);
        text-transform: uppercase ;
        font-size: 2em;
        display: inline-block;

        padding: 1.2em 2em;
        text-decoration: none;
        text-align: center;
    }

    a:hover {
        color: var(--light-blue);
    }

    /* a::after{
        content: '';
        width: 0;
        height: 3px;
        position: absolute;
        bottom: -5px;
        left: 50%;
        transform: translateX(-50%);
        background-color: blue;
        transition: width 0.4s ;
        z-index: 20;
    }

    a:hover::after{
        width: 100%;
    } */

    @media (min-width: 48em) {


        a {
            font-size: 1em;
        }

    }


</style>