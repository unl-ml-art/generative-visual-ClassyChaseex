# Project 3 Generative Visual

Karston Chase, kchase4@huskers.unl.edu

## Abstract

My idea is for a user to input text that describes a room in their house. This would describe things such as wall color, furniture color, accent colors, artificial or natural lighting, etc. Then this description would be translated into keywords for BigGAN to then turn into a painting or artwork that would compliment said room if hung up on the wall. Whether a picture of a landscape or an abstract painting, BigGAN can create a perfectly matching image for your room!

## Model/Data

- BigGAN
- StyleGAN (Potentially)
- The default traing data for BigGAN would be used, but categorized based on color. Color's relationships with one another would determine which category BigGAN would look into to correctly match a given interior space.

## Code

- This project is mostly conceptual so no code has been done for it yet. If this idea were to be realized down the line, external code would be needed to categorize more, if not all, of BigGAN's training data into these color categories.
- More external code would also be needed to get BigGAN to successfully pull data out from these categories correctly to generate the images.
- To make room descriptions simple and not through code input, a user interface would need to be made to input these descriptions such as color and lighting.
- As a future possibility, codes to implement and use StyleGAN in the finalization process could be used.

## Results

- Project 3 - P(AI)nting Picker.pdf is the completed slides file showing the full conceptualization of this project. NOTE - There are more in depth comments and further details witten in the 'Speaker Notes' section on a few of the slides. Here is the URL for the slides as well: https://docs.google.com/presentation/d/10KDPYAGC_L8GuXNLg3-djRU7NnlsOoEa-K6_FVLCLBI/edit?usp=sharing
- The full resolution images used in the Google Slides presentaion are provided in this repository and labeled below.
- googlesheets-screenshot.png is the image taken of the data categorization I completed from BigGAN's training data.
- biggan-screenshot.png is the image taken from some image generation and interpolation I was messing around with. The corner images represent some photographic images that could be produced from a color pallet selcted from the options: [White] [Pink] [Natural Lighting]
- samoyed-image.jpg is an image of a Samoyed before being processed by StyleGAN.
- stylization-test.png is an image generated after applying a style transfer from StyleGAN. This is a proof of concept for the future implementations of this project and could've been generation from a selection of [Neutral Colors] and/or [Artificial Lighting] or even just a product of the user's own stylistic preferences.

## Technical Notes

- StyleGAN could be used for future implementation of the project and could be used to add user customization of image styles from photographic to painted and even draw these styles from the user's choice of artist as well.

## Reference

- BigGAN
- StyleGAN
