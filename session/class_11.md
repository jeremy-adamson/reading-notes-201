# Readings: Audio, Video, Images

## Video and Audio

* Explain how the ability to use video and audio on the web has evolved since the early 2000s.
  * Earlier versions of the web relied upon Flash and Silverlight plugins for video or audio files while most of that functionality as been included into HTML since those times.
* Describe the use of the `src` and `controls` attributes in the `<video>` element.
  * `src` defines where the file actually at (the source) and `controls` tells the browser to use the standard built-in audio-visual controls for playback
* Why is it important to have fallback content inside the `<video>` element?
  * Sometimes the video may not load on its own and sometimes codecs are incompatible such as with older browsers.
* Write a very short story where `<audio>` and `<video>` are characters.
  * Not too sure about a story but both the audio and video components are on separate (but parallel) tracks in a very similar manner as "talkies" in the movie buisness.

## Grid

* How does grid layout differ from flex?
  * Flex is a way to display things in 1-D while Grid is setup mostly for 2-D implimentation.
* Grid container, grid item, and grid line are a gew important terms to understand when using Grid. Please describe these terms in a few sentences.
  * Grid container is the space/section in which the grid fomat lives
  * Grid item is a direct descendant of the container
  * Grid lines are what separate the cells within a grid

## Responsive Images

* Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  * Saves bandwidth for mobile devices, typically.
* Define the following `<img>` attributes `srcset` and `sizes`. Write and example of how they are used.
  * `srcset` defines the pool of available images to choose from
  * `sizes` defines the size conditions for which image from the pool to choose
* How is `srcset` more helpful for responsive images than CSS or JavaScript?
  * CSS and JavaScript would have to load the full image first and then figure out what to do with it while `srcset` defines which image to load in the first place

## Readings

* [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
* [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
* [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
* [Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
