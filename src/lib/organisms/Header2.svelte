<script>
    import { NavLogo, NavLink, BtnPrimary2 } from '$lib/index.js';
</script>

<nav>

    <NavLogo href="/"></NavLogo>

    <input class="menu-btn" type="checkbox" id="menu-btn" aria-label="Navigation menu" />
    <label class="menu-icon" for="menu-btn">
        <span class="navicon"></span>
    </label>

    <ul>
        <li>
            <NavLink href="/concept1" title="Concept 1"></NavLink>
        </li>
        <li>
            <NavLink href="/concept2" title="Concept 2"></NavLink>
        </li>
        <li>
            <BtnPrimary2 href="/concept3" title="Concept 3"></BtnPrimary2>
        </li>
    </ul>

</nav>


<style>

    /* header */

    nav {
        display: block;
        position: fixed;
        width: 100%;
        padding-left: 1.5em;
        z-index: 1;
        background-color: transparent;
        height: 100vh;
        box-shadow: 0px 200px 186px -32px rgba(0, 0, 0, 0.16) inset;
        -webkit-box-shadow: 0px 200px 186px -32px rgba(0, 0, 0, 0.16) inset;
        -moz-box-shadow: 0px 200px 186px -32px rgba(0, 0, 0, 0.16) inset;
    }

    nav ul {
        margin: 0;
        padding: 0;
        list-style: none;
        overflow: hidden;

        clear: both;
        max-height: 0;
        transition: max-height .2s ease-out;
    }

    nav li{
        padding: 2em 0;
        display: flex;
        justify-content: center;
    }

    nav li:nth-last-child(1){
        display: flex;
        justify-content: center;
    }

    /* Hamburger Menu */

    nav .menu-icon {
        cursor: pointer;
        display: flex;
        align-items: center;
        justify-content: center;
        float: right;
        width: 2em;
        height: 2em;
        position: relative;
        top: 1.3em;
        right: 1em;
        user-select: none;
        background-color: #82C0CC;
        border-radius: 50%;
    }

    nav .menu-icon .navicon {
        background: var(--White);
        display: block;
        height: 3px;
        position: relative;
        transition: background .2s ease-out;
        width: 24px;
    }

    nav .menu-icon .navicon:before,
    nav .menu-icon .navicon:after {
        background: var(--White);
        content: '';
        display: block;
        height: 100%;
        position: absolute;
        transition: all .2s ease-out;
        width: 100%;
    }

    nav .menu-icon .navicon:before {
        top: 5px;
    }

    nav .menu-icon .navicon:after {
        top: -5px;
    }

    /* menu btn */

    nav .menu-btn {
        display: none;
    }

    nav .menu-btn:checked ~ ul {
        max-height: 60em;
    }

    nav .menu-btn:checked ~ .menu-icon .navicon {
        background: transparent;
    }

    nav .menu-btn:checked ~ .menu-icon .navicon:before {
        transform: rotate(-45deg);
    }

    nav .menu-btn:checked ~ .menu-icon .navicon:after {
        transform: rotate(45deg);
    }

    nav .menu-btn:checked ~ .menu-icon:not(.steps) .navicon:before,
    nav .menu-btn:checked ~ .menu-icon:not(.steps) .navicon:after {
        top: 0;
    }

    /* 48em = 768px */

    @media (min-width: 48em) {

        nav{
            padding-left: 2.5em;
            padding-top: 1em;
            position: absolute;
            z-index: 1;
            background-color: transparent;
            height: 100vh;
            box-shadow: 0px 200px 186px -32px rgba(0, 0, 0, 0.16) inset;
            -webkit-box-shadow: 0px 200px 186px -32px rgba(0,0,0,0.16) inset;
            -moz-box-shadow: 0px 200px 186px -32px rgba(0,0,0,0.16) inset;
        }

        nav ul{
            display: flex;
            align-items: center;
            padding: 0 3em;
            clear: none;
            float: right;
            max-height: none;
        }

        nav li {
            float: left;
            padding: 1em 0;
        }

        nav .menu-icon {
            display: none;
        }

        nav .menu-icon {
            width: 3em;
            height: 3em;
        }

    }


</style>