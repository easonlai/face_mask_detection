# Power App sample for Face Mask Detection

Given that COVID-19 (Omicron variation) situation is still not yet controlled, the confirmed cases keep rising in some countries and cities. It's important to make sure people wear a face mask to prevent a potential COVID-19 spread out. Most indoor areas are still required (compulsory required) to wear the face mask before entering. I am delighted to announce this Power App (Canvas App) template to help corporations, enterprises, schools, and universities check are wearing a face mask before entering a venue.

This app is an infused AI model trained with a tool called ["Lobe"](https://www.lobe.ai/). It used a camera to take an image (every 2 seconds, it can be further tuned down) and perform AI model scoring to identify/classify continuously (every 1 second, it can be further tuned down) is that person is wearing a face mask or not. If it detects people's face mask is off, it will give the block sign and make an error sound. In reverse, it will give a green sign and make a welcome sound.

The template is under [/power-app-template/FaceMaskDetection_20220310072308.zip](https://github.com/easonlai/face_mask_detection/blob/main/power-app-template/FaceMaskDetection_20220310072308.zip).

You can also refer to Power App Community's [Emergency Response Gallery for more details](https://powerusers.microsoft.com/t5/Emergency-Response-Gallery/Face-Mask-Detection/td-p/1495016).

With my [previous template of "Leave Office/Campus Safe" for tracking](https://powerusers.microsoft.com/t5/Emergency-Response-Gallery/Leave-Office-Campus-Safe/td-p/1491813), we should make a more safe environment for people using a digital solution with Power Platform (Power App).

For how to import this template into your environment, please refer to this [official article](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/export-import-app#importing-a-canvas-app-package).
For more details on how to use an image classification model by Lobe in Power Apps, please refer to this [official article](https://docs.microsoft.com/en-us/ai-builder/image-classification-component-in-powerapps).

I hope you enjoy it. And god bless, COVID-19 will be gone soon.

Below is a screenshot for reference.

![alt text](https://github.com/easonlai/face_mask_detection/blob/main/screenshots-from-power-app/power-app-screenshot-all.png)