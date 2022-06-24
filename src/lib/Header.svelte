<script lang="ts">
    import FlyingCloud from '../assets/transparent.svg';
</script>

<header>
    <div class="brand">
        <h1>Soundly<sup>&copy;</sup></h1>
        <div class="sub-text">
            <h3>Select and</h3> 
            <div>
                <span class="hidden">Chill</span>
                <span class="mid-opacity">Study</span>
                <span>Chill</span>
                <span class="mid-opacity">Sleep</span>
                <span class="hidden">Chill</span>
            </div>
        </div>
    </div>
    <div class="clouds">
        <object data={FlyingCloud} title=""></object>
        <object data={FlyingCloud} title=""></object>
        <object data={FlyingCloud} title=""></object>
    </div>
    <object class="cloud" title="" data="clouds.svg"></object>
</header>

<style lang="scss">
    header {
        background: linear-gradient(180deg,#4EA1EA 20%, #BDD5EA 100%);
        width: 100%;
        padding: 5em 0 10em;
        display: flex;
        position: relative;
        overflow: hidden;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    header .clouds {
        position: absolute;
        width: 100%;
        top: 0;
        left: 0;
    }
    header .cloud {
        position: absolute;
        width: 140%;
        bottom: -.1em;
        user-select: none;
        height: auto;
    }
    header .brand {
        position: relative;
    }
    header .brand .sub-text {
        display: flex;
        position: absolute;
        top: 2.5em;
        font-size: .75rem;
        right: 0;
        flex-direction: row;
        color: #FFFFFF;
        align-items: center;
        justify-content: flex-end;
    }
    header .brand .sub-text h3 {
        margin-right: .5em;
        word-spacing: .5em;
        font-weight: 400;
    }
    header .brand .sub-text div span:not(:last-child) {
        margin-bottom: .5em;
    }
    header .brand .sub-text div span {
        transition: opacity .3s;
    }
    header .brand .sub-text div .mid-opacity {
        opacity: .5;
    }
    header .brand .sub-text div .hidden {
        opacity: 0;
    }
    header .brand .sub-text h3 {
        color: #FFFFFF;
    }
    header .brand .sub-text div {
        display: flex;
        user-select: none;
        align-items: center;
        flex-direction: column;
    }
    header .brand h1 {
        margin: 0;
        padding: 0;
        font-size: 3rem;
        text-transform: uppercase;
        color: #FFFFFF;
        position: relative;
        font-weight: 400;
    }
    header .brand h1 sup {
        font-size: 1rem;
        position: absolute;
        top: -.25em;
        margin-left: .25em;
        font-weight: 500;
    }
</style>