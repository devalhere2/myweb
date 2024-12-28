<script>
    import Profile from "../lib/nav/Profile.svelte";
    import Search from "../lib/nav/Search.svelte";
</script>

<nav>
    <div style="flex: 1; display: flex; align-items: center;">
        <div class="web-name">ripbroker</div>
    </div>
    <div style="display: flex; margin: 0 10vw; align-items: center;">
        <div class="search-bar" >
            <Search />
        </div>
        <div class="profile">
            <Profile />
        </div>
    </div>
    
</nav>
<slot />

<style>
    nav{
        display: flex;
        height: 50px;
        box-sizing: border-box;
        border-bottom: 1px solid #80808080;
    }
    div {
        font-size: 16px;
    }

    .search-bar {
        width: 300px;
        margin: 0 10px;
    }
    .web-name{
        font-size: 20px;
        font-weight: bold;
        margin: 0 10vw;
    }
</style>