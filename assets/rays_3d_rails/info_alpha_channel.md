[Reddit](https://www.reddit.com/r/GIMP/comments/19cjub/pasting_into_an_alpha_channel/)

 I followed u/clgonsal steps but I found them not much clear, so I am writing a step by step guide here. The guide assumes the alpha channel is to be found as a component of another image. First let's copy the alpha channel to use later with the following steps:

Open the image you want to use as an alpha channel, or that it contains the alpha channel you want to use later;
From the menu, select "Color -> Components -> Decompose";

From the popup window, select the color model (RGB or RGBA), ensure "Decompose as layers" is checked, and "Foreground as registration color" is unchecked;

A new image is created, from the layers window, delete or hide the unwanted layers;

From the menu, select "Edit -> Copy Visible"

Then paste the copied alpha channel to the desired image with the following steps:

    Open the image you want to add an alpha channel to;

    In the layers window, select the sole layer, right click "Add Alpha Channel";

    In the layers window, select the sole layer, right click "Add Layer Mask". Initialize the layer mask to "White (full opacity)", click "Add";

    In the layers window, select the sole layer, right click "Show Layer Mask";

    Paste the previously copied channel into the active context (CTRL+V) and anchor it (CTRL+H);

    In the layers window, select the sole layer, right click "Apply Layer Mask";

    Save the project or export the image to a format supporting transparencies. 