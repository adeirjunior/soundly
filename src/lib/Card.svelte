<div class="card">
    <div class="top">
        <h3>Calm Mind</h3>
    </div>
    <div class="clouds">
        <object class="left" title="" data="left-cloud.svg">
        <object class="right" title="" data="rigth-cloud.svg">
    </div>
</div>

<style>
    .card {
        width: 250px;
        overflow: hidden;
        background: linear-gradient(180deg,#4EA1EA 20%, #BDD5EA 100%);
    }
    .card .top h3 {
        text-align: center;
        color: #FFFFFF;
    }
    .card .clouds {
        display: flex;
        width: 100%;
        justify-content: space-between;
        position: relative;
        flex-direction: row;
    }
    .card .clouds .left, .card .clouds .right {
        position: absolute;
        bottom: -.1em;
        user-select: none;
    }
    .card .clouds .left { 
        left: -.1em;
    } 
    .card .clouds .right {
        right: -.1em;
    }
</style>