<script lang="ts">
 
</script>

<ul>
    <li><button>Rhythm</button></li>
    <li><button>Melody</button></li>
    <li><button>Harmony</button></li>
    <li><button>Atmospheric</button></li>
</ul>

<style>
    ul {
        list-style: none;
        padding-top: 2em;
        display: grid;
        grid-template-columns: repeat(2, 120px);
        gap: 1em;
        margin-block-start: 0;
        place-content: center;
        padding-inline-start: 0;
    }
    ul li button {
        width: 100%;
        text-align: center;
        text-transform: uppercase;
        background-color: #FFFFFF;
        border-radius: 3em;
        font-weight: 400;
        font-size: 0.625rem;
        cursor: pointer;
        color: #D7D7D7;
        border: 2px solid #D7D7D7;
        padding: .75em 2em;
        -webkit-tap-highlight-color: rgba(0,0,0,0);
    }
    ul li button:active {
        border-color: #77B6EE;
        color: #FFFFFF;
        background-color: #77B6EE;
    }
</style>