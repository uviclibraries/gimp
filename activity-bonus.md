---
layout: default
title: Bonus-Changing Object Colors
nav_order: 6
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Bonus Activity: Changing Colours

In this activity we will be changing the colours of objects in a photo (note: this does not work on white or black objects). If you have any questions, please ask!

1.  Download [this image](https://unsplash.com/photos/qSXBBSFfxaM){:target="_blank"} for the exercise
2.  Open the photo in GIMP by going to **File -> Open** in the upper menu. Find where you saved the photo and open it. If your browser automatically saved it for you, it is probably in your **Downloads** folder. It may pop up with another window asking to **Convert to RGB Working Space**. (_Note: there are certain circumstances where you may need to convert an image to a different color profile, such as when importing from a scanner or camera. But in this case, it is not necessary._) Click on **Keep**. If you wanted to do this project using one of your own images, it would be best to create a duplicate first, as described in previous activities

    <img src="images\bonus-act\2-magnify.png" alt="magnify icon" style="float:right;width:60px;">

3.  Click on the **Zoom Tool** (magnifying glass) in the left toolbar to zoom in a bit on one of the apple halves so you can see it better
    
    <img src="images\bonus-act\2-another.png" alt="foreground select icon" style="float:right;width:60px;margin-left:10px;">
    
    <img src="images\bonus-act\2-freeselect.PNG" alt="free select icon" style="float:right;width:60px;margin-left:10px;">

4.  Click on the **Foreground Select Tool** (picture of a person with a square behind it) in the left toolbar. _Note: In newer versions of GIMP, the foreground select tool might not be automatically visible in the left toolbar. In this case you can access it by hovering over the **Free Select Tool** (picture of a lasso), clicking and holding the left mouse button such that a small menu appears, and then dragging your mouse while **still holding down the left mouse button** to the foreground select option, releasing over it to select._ Use the foreground select tool to click and drag a rough selection around one of the apple halves (see example). When you get around to the end of the selection, the end circle of the selection points will turn orange to indicate it is the end join

   <button onclick="toggle('gif1')">Show/Hide Animation</button>
<div id="gif1"> 
    <img src="images\bonus-act\gimp-bonus-1.gif" alt="tracing apple" style="width:720px;">
    </div>
    
<img src="images\bonus-act\5-foregroundselect-new.png" alt="foreground select" style="float:right;width:180px;margin-bottom:10px">

5.  Hit the **Enter** key. This will turn everything outside the selection blue and change your selection tool into a circle. Use this to **paint a selection over the inside of the apple slice** (you can adjust the **Stroke Width** to make it larger in the tool options on the left if needed). Don't worry about getting all the way over to the edge, just stay inside the outlines of the apple. When finished, click the **Select** button in the small **Foreground Select** box in the upper right corner
<button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images\bonus-act\gimp-bonus-2.gif" alt="selecting foreground" style="width:720px;"></div>

6.  You should now have a selection line around the edges of the apple. Click on **colors** in the upper menu and then click on **Hue-Saturation**. This will bring up a dialog box. Increasing **Hue** will bring the colour into the greens and blues, decreasing it will bring the colour into the orange, red, and purple range. You can increase the **Saturation** for more intense colour as well. Click **OK**
<button onclick="toggle('gif3')">Show/Hide Animation</button>
    <div id="gif3">
    <img src="images\bonus-act\gimp-bonus-3.gif" alt="changing hue" style="width:720px;">
</div>
7.  Click **Select** in the top menu and then click **None**, to release the selection around the apple. You can repeat these steps on the other apple slices with different (or the same) colours, as practice
    
<img src="images\bonus-act\8-blueapple-new.png" alt="final result" style="float:right;width:180px;">

8.  Note: If the selection you chose was not accurate enough in steps 5 and 6, you can use the different mode buttons in **Foreground Select** to practice adding and subtracting from current selection to fine tune
9.  **Save:** Click on **File -> Save As** in the upper left corner. We are going to save this in the GIMP .xcf format, which is the working format within GIMP that will preserve the layers. Choose where you would like to save the file, and give it a name you will remember. Click **Save**. You can export a JPG or PNG of the image using instructions from Activities #1 or #2

Bonus: Another image to practice with: [https://unsplash.com/photos/YDZbFOOnLsE](https://unsplash.com/photos/YDZbFOOnLsE){:target="_blank"}


<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>
[NEXT STEP: Earn a Workshop Badge](informal-credentials.html){: .btn .btn-blue }
