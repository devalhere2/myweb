<section class="explain">
    <div class="content">
        <div style="width: 48%;">
            <div style="height: 100%; width: 100%; display: flex; align-items: center;">
                <img src="map.png" alt="" width="100%" style="border-radius: 10px; border: 2px solid #80808080;">

            </div>
        </div>
        <div style="width: 4%;"></div>
        <div style="width: 48%; display: flex; align-items: center;">
            <div style="display: flex; flex-direction: column;">
                <div style="font-size: 18px; display: inline; font-weight: bold; color:darkslategrey">
                    Find Homes & Properties near you and that too Free for ever 
                </div>
                <div style="padding: 10px 0px;">
                    <button class="explore">
                        Explore Now
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                    </button>
                </div>
                <a href="/" class="works">Find how it works.</a>
            </div>
        </div>
        
    </div>
</section>


<style>
    .explain{
        height: 60vh;
        background-color: rgba(224, 255, 255, 0.25);
        display: flex;
        justify-content: center;
    }
    .explain .content {
        display: flex;
        width: 60%;
        height: 100%;
    }

    .explore {
        background-color: lightcyan;
        width: 200px; 
        font-size: 16px;
        font-weight: bold;
        color: green;
        height: 36px; 
        border-radius: 16px; 
        border: 2px solid green;
        display: flex; /* Use flexbox */
        align-items: center;
        justify-content: center; /* Vertically center the content */
        gap: 8px;
        cursor: pointer;
    }
    .explore:hover{
        background-color: white;
    }
    .works {
        font-size: 10px; 
        text-decoration: underline; 
    }
    .works:visited {
        color: black;
    }
    .works:hover {
        color: blue;
        cursor: pointer;
    }
</style>