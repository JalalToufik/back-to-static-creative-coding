<script>
	export let href, title;
</script>

    <a {href}> 
        {title}
    </a>

<style>

    a{
        display: inline-block;
        margin: 0 auto;
        border: none;
        border-radius: 3em;
        padding: 1em 2em;
        background-color: #2A8193;
        color: var(--JustWhite);
        font-weight: bold;
        font-family: var(--Apercu-Font);
        text-transform: uppercase;
        transition: .2s ease-in-out;
    }

    a:hover{
        background-color: var(--White);
        color: var(--Bg-Dark-Blue);
    }



</style>
