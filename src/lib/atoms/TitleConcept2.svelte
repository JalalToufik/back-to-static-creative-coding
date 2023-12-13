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
        flex-direction: row;
        width: 40%;
        transform: rotate(-2deg);
    }

    h1 {
        display: flex;
        flex-direction: column;
        color: var(--White);
        font-family: var(--Header-Font);
    }

    .container span {
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

    h1 > div{
        padding: .1em;
    }

    
</style>