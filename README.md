# OBS Goldeneye Filter

![Final Image](./images/7.png)


## Requirements:
1. Screen Recording Software/Application with PIP and Image-Mask capabilities. (I use OBS)
    - [OBS Studio](https://obsproject.com/)
2. Powerpoint Slide Template ([goldeney.pptx](./goldeneye.pptx))
3. Simple Paint App (I use paint.net as well as MS paint)


## Step 1:
Reduce the size of your video capture device screen by:
1. `right clicking` on video preview screen.
2. select `Transform`
3. select `Edit Transform`

![stepa](./images/a.png)

## Step 2:
1. Mess around with the crop settings until you've centered the filed of view on the outline of your shoulders. 
2. Click `close`

![stepb](./images/b.png)

## Step 3:
1. Add a filter to your video capture device by clicking on the name of your video capture device (default name is `video capture device` but could name it differently) in the `sources` section, and then selecting `filters` right under the video screen.

![Step1](./images/1.png)

## Step 4:
1. Under `Effect Filters` choose `Image Mask/Blend`

![Step3](./images/3.png)

## Step 5:
1. Keep all of the default values.
2. Select browse and find the location of `OBS-MASK.png`
3. Select `close`

![Step4](./images/4.png)

## Step 6:
1. Ensure that your camera is centered on your face, or the exact frame that you want to show up in the circle.
2. If your image is centered skip to Final Step
3. If you image is not centered:
    1. Go back to step `step 2` and mess around with the cropping to see if you can fix it that way.
    2. If you're not able to fix your image that way you'll have to edit the image mask itself. Shown in the next step.

![Step5](./images/5.png)

## Step 7: (troubleshooting cropped image mask)
1. Simply play around with the location and/or size of the white circle until you've centered your circle in OBS.
    1. If it's slightly cropped like shown in step 6 you should be able to take care of it in the edit transform, but if not you'll want to move it slightly to the opposite side of where the circle is being cut off from.

![Step6](./images/6.png)


## Final Step:
1. Open UP your powerpoint template slide
2. Add powerpoint to your `sources` section:
    1. `click` the `+` in `sources`
    2. select `windowed capture`
    3. find select the `powerpoint.exe` choice from the source.

![Step7](./images/7.png)

