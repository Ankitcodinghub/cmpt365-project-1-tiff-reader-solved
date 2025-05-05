# cmpt365-project-1-tiff-reader-solved
**TO GET THIS SOLUTION VISIT:** [CMPT365 Project 1-TIFF Reader Solved](https://www.ankitcodinghub.com/product/cmpt365-project-1-tiff-reader-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95226&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT365 Project 1-TIFF Reader Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Create a program that reads an uncompressed TIFF image file and display it on the screen. A brief introduction and historical review of TIFF can be found at https://en.wikipedia.org/wiki/TIFF

Details about the TIFF 6.0 format can be found in TIFF6.pdf as well as many other places online.

Only the 24-bit RGB full color uncompressed mode in TIFF will be considered (see Section 6: RGB Full Color Images in TIFF6.pdf). You can assume that the image is no bigger than the 4*CIF size (i.e., 704*576). You can ignore header tags that are not used in this project.

Your program should first show an open file dialog box for the user to select the TIFF file. It should then work as follows:

1. Displays the original colored image;

2. Refreshes by the corresponding grayscale image of the original image;

3. Refreshes by applying ordered dithering on the grayscale image;

4. Refreshes by making the brighter part of the image darker and the darker part brighter, which is known as “adjusting the dynamic range” in photo editing.

To move to the next step, your can either place a “next” button on screen, or pause until any key is pressed. Go back to step 1 after step 4. There should also be a “quit” button.

We will not specify any dither matrix. You can experiment different ones and choose a good one. You need to discuss your choice of the dither matrix in the report. For adjustment of dynamic range, you should experiment different ways/thresholds and discuss the effects, too.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Rationale of doing this project:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Learn a media file format and how is it specified. You will find that there are so many fine details. There are so many different formats in industry (see for example Murray, James D.; vanRyper, William (April 1996). “Encyclopedia of Graphics File Formats” (Second ed.). O’Reilly. ISBN 1-56592-161-5. ) Yet as long as you have experience with one format, you’ll find that you can easily hack most others. In fact, TIFF is known as the “base” or “origin” of many other formats.</li>
<li>Have some inside knowledge about some Photoshop operations, e.g., remove color, adjust dynamic range. We will see more in next project. You will then find that you know Photoshop (or other similar tools) much better, and you can indeed write your own.</li>
<li>Have some taste about research. Say for the choice of dither matrix and dynamic range adjustment, we expect that you find a good one (or the best trade-off) through your own design/experiments, while not simply and passively look for an answer from textbook. The discussion part will be the highlight of your report, which will showcase your own hard works and distinguish yourself from others. (same for Programming assignment)</li>
</ol>
</div>
</div>
<div class="layoutArea"></div>
</div>
