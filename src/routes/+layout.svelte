<script>
    import { goto } from "$app/navigation";
    import Profile from "../lib/nav/Profile.svelte";
    import Search from "../lib/nav/Search.svelte";
</script>

<nav>
    <div style="flex: 1; display: flex; align-items: center;">
        <!-- svelte-ignore a11y_click_events_have_key_events -->
        <!-- svelte-ignore a11y_no_static_element_interactions -->
        <div style="display: flex; align-items: center; margin-left: 10vw;">
            <img src="homebetter.png" alt="" height="50px" style="border-radius: 5px;">
            <div class="web-name" on:click={()=>goto('/')}>ripbroker</div>
        </div>
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
        width: 400px;
        margin: 0 10px;
    }
    .web-name {
        font-size: 22px;
        margin-left: 10px;
        font-weight: bold;
        cursor: pointer;
        display: flex;
        align-items: flex-end; /* Align items to the bottom */
        height: 40px;
    }
</style>