<script>
    let searchValue = '';
</script>

<div class="container">
    <input type="text" name="" id="searchInput" bind:value={searchValue} placeholder="Enter Locality / pincode here...">
    {#if searchValue != ''}
    <div class="recommendations" id="recommendList">
        <div class="recommendation-item">Mumbai, Maharashtra - 400001</div>
        <div class="recommendation-item">Delhi, New Delhi - 110001</div>
        <div class="recommendation-item">Bangalore, Karnataka - 560001</div>
        <div class="recommendation-item">Hyderabad, Telangana - 500001</div>
        <div class="recommendation-item">Chennai, Tamil Nadu - 600001</div>
    </div>
    {/if}
</div>

<style>
    .container {
        position: relative;
    }

    input {
        width: 100%;
        height: 30px;
        border: 1px solid #80808080;
        border-radius: 4px;
        padding-left: 10px;
        font-size: 14px;
        font-weight: bold;        
        box-sizing: border-box;
    }
    input:focus{
        border: 2px solid rgb(103, 49, 230);
        box-shadow: 0 0 2px rgba(142, 93, 255, 0.5);
        outline: none;
    }
    input::placeholder{
        font-weight: bold;
        font-size: 14px;
        color: gray;
    }

    .recommendations {
        position: absolute;
        width: 100%;
        margin-top: 5px;
        border: 1px solid #80808080;
        border-radius: 5px;
        box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        background-color: white;
        box-sizing: border-box;

    }

    .recommendation-item {
        padding: 10px;
        /* height: 30px; */
        font-weight: bold;
        color: rgb(53, 53, 53);
        cursor: pointer;
        font-size: 14px;
    }

    .recommendation-item:hover {
        background-color: #f5f5f5;
    }

    .recommendation-item:not(:last-child) {
        border-bottom: 1px solid #80808080;
    }
</style>