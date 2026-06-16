# Ice Breaker: Simple Image Generation

## Time Required
10 minutes

## Overview
In this lab, you will use Gemini's image generation model to create a warm, professional, branded social media image for a Merck campaign. This is a quick, fun introduction to Gemini's image generation capabilities and a great way to kick off the course.

### You learn how to:
- Construct a visual prompt to evoke emotion and convey a campaign message.
- Upload an image file (Merck logo) as context for image generation.
- Generate a professional, brand-ready visual asset.

## Scenario

<p align="left">
  <img src="images/merck-logo.png" width="30%" alt="Merck Logo" />
</p>

Merck's Corporate Communications and Marketing teams are launching a social media campaign around cognitive health and the importance of preserving memories—aligning with Merck's pipeline of treatments for Alzheimer's disease. The team wants a heartwarming, high-quality visual showing stable cognitive health across generations: a grandfather teaching his two young grandchildren how to play chess.

## Lab Instructions

### Task 1: Generate the Campaign Image

1. Open **Gemini Enterprise** in your browser.

2. In the chat bar, select the **Tools** icon and choose **Create images**.

   <p align="left">
      <img src="images/generate-images.png" width="50%" alt="Create Images" />
      <br>
      <em>Create Images tool</em>
   </p>

3. Copy and paste the following prompt into the chat, then press **Enter**:

   ```text
   Create a high-quality, professional photograph for a healthcare social media post. A grandfather teaching his two grandchildren how to play chess. 
   ```

4. We want to add Merck's brand mark to the image. Copy the **Merck Logo** shown in the Scenario section above and paste it into your Gemini chat, and run the following follow-up prompt:

   ```text
   Adjust the image using the attached Merck logo. Place the Merck logo neatly and professionally as a small watermark in the bottom corner of the image.
   ```

5. Review the generated image. Notice how Gemini integrates the brand assets to create a ready-to-share social post.

### Task 2: Refine and Experiment

1. Try changing the artistic medium. Ask Gemini to regenerate the same scene but using a different style:

   ```text
   Regenerate this exact scene, but change the style to a soft, warm watercolor illustration.
   ```

2. Experiment by adding additional details to the prompt. Where are they sitting, how old are they, what do they look like, how many grandchildren are there? For example: 

   ```text
   Create a high-quality, professional photograph for a healthcare social media post. A  gray-haired, African-American grandfather with a beard is teaching his two grandchildren (a boy and a girl between 7 and 9) how to play chess. They are on the front porch of an older southern-style house. It is a beautiful summer evening. Warm light and cozy. Add the Merck logo in the bottom left corner.
   ```

   <p align="left">
      <img src="images/example-output.png" width="50%" alt="Example Output" />
      <br>
      <em>Example Output</em>
   </p>


## Congratulations

In this lab, you have:
- Created a heartwarming campaign visual built on real-world therapeutic context.
- Practiced uploading a brand logo as visual context for image generation.
- Explored fast style and setting refinements using Gemini.
