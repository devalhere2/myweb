<script lang="ts">
    function focusThings(theThing: string) {
        const element = document.getElementById(theThing);
        if (element) {
            element.focus();
        } else {
            console.error(`Element with ID ${theThing} not found.`);
        }
    }
</script>

<section class="explain">
    <div class="content">
        <div style="width: 48%;">
            <div
                style="height: 100%; width: 100%; display: flex; align-items: center;"
            >
                <img
                    src="map.png"
                    alt=""
                    width="100%"
                    style="border-radius: 10px; border: 2px solid #80808080;"
                />
            </div>
        </div>
        <div style="width: 4%;"></div>
        <div style="width: 48%; display: flex; align-items: center;">
            <div style="display: flex; flex-direction: column;">
                <div
                    style="font-size: 24px; padding: 10px 0px; display: inline; font-weight: bold; color:darkslategrey"
                >
                    Find Your Perfect Space
                </div>
                <div
                    style="font-size: 16px; display: inline; font-weight: bold; color:darkslategrey"
                >
                    Zero Fees, Zero Hassles, Zero Brokers
                </div>
                <div style="padding: 10px 0px;">
                    <button
                        class="explore"
                        on:click={() => focusThings("searchInput")}
                    >
                        Explore Now
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            width="16"
                            height="16"
                            viewBox="0 0 24 24"
                            fill="none"
                            stroke="currentColor"
                            stroke-width="3"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            class="lucide lucide-arrow-right"
                            ><path d="M5 12h14" /><path
                                d="m12 5 7 7-7 7"
                            /></svg
                        >
                    </button>
                </div>
                <a href="/" class="works">Find how it works.</a>
            </div>
        </div>
    </div>
</section>

<style>
    .explain {
        height: 60vh;
        background-color: rgba(153, 255, 255, 0.5);
        display: flex;
        justify-content: center;
    }
    .explain .content {
        display: flex;
        width: 60%;
        height: 100%;
    }

    .explore {
        background-color: rgba(224, 255, 255, 1);
        width: 200px;
        font-size: 16px;
        font-weight: bold;
        color: green;
        height: 36px;
        border-radius: 18px;
        border: 2px solid green;
        display: flex; /* Use flexbox */
        align-items: center;
        justify-content: center; /* Vertically center the content */
        gap: 8px;
        cursor: pointer;
    }
    .explore:hover {
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
