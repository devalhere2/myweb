<section class="sponsor">
    <div class="content">
        <div style="width: 20%;">
            <div style="height: 100%; width: 100%; display: flex; align-items: center; justify-content: end;">
                <img src="bird.png" alt="" height="90%" style="border-radius: 10px;">
            </div>
        </div>
        <div style="width: 4%;"></div>
        <div style="width: 76%; display: flex; align-items: center;">
            <div style="display: flex; flex-direction: column;">
                <div class="text">
                    This platform will remain free for individual users. As developers, our priority is creating value, not maximizing profits.
                </div>
                <a href="/" class="works">Find out how do we manage it.</a>
                <div style="padding: 10px 0px; display: flex; justify-content: center; gap: 20px;">
                    <button class="sponsor-button">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart-handshake"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"/><path d="M12 5 9.04 7.96a2.17 2.17 0 0 0 0 3.08c.82.82 2.13.85 3 .07l2.07-1.9a2.82 2.82 0 0 1 3.79 0l2.96 2.66"/><path d="m18 15-2-2"/><path d="m15 18-2-2"/></svg>
                        Sponsor Us
                    </button>
                    <button class="contact-button">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-pen"><path d="M12.5 22H18a2 2 0 0 0 2-2V7l-5-5H6a2 2 0 0 0-2 2v9.5"/><path d="M14 2v4a2 2 0 0 0 2 2h4"/><path d="M13.378 15.626a1 1 0 1 0-3.004-3.004l-5.01 5.012a2 2 0 0 0-.506.854l-.837 2.87a.5.5 0 0 0 .62.62l2.87-.837a2 2 0 0 0 .854-.506z"/></svg>
                        Contact Us
                    </button>
                </div>
                
            </div>
        </div>
        
    </div>
</section>

<style>
    .sponsor{
        height: 40vh;
        display: flex;
        justify-content: center;
    }
    .sponsor .content {
        display: flex;
        width: 90%;
        height: 100%;
    }
    .text {
        font-size: 18px; 
        padding: 10px 0px; 
        display: inline; 
        font-weight: bold; 
        color:darkgreen
    }
    .sponsor-button {
        background-color: rgb(255, 215, 252,0.1);
        width: 200px; 
        font-size: 16px;
        font-weight: bold;
        color: rgb(255, 69, 100);
        height: 36px; 
        border-radius: 18px; 
        border: 2px solid rgb(255, 69, 100);
        display: flex; /* Use flexbox */
        align-items: center;
        justify-content: center; /* Vertically center the content */
        gap: 8px;
        cursor: pointer;
    }
    .sponsor-button:hover{
        background-color: white;
    }

    .contact-button {
        background-color: rgb(255, 251, 190,0.1);
        width: 200px; 
        font-size: 16px;
        font-weight: bold;
        color: rgb(148, 146, 22);
        height: 36px; 
        border-radius: 18px; 
        border: 2px solid rgb(148, 146, 22);
        display: flex; /* Use flexbox */
        align-items: center;
        justify-content: center; /* Vertically center the content */
        gap: 8px;
        cursor: pointer;
    }
    .contact-button:hover{
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