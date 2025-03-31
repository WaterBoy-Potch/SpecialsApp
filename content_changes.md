# Changing Video and Current Month

This document explains how to change the video source and update the "Current Month" to the "Previous Month" on the web page.

## Changing the Video

1.  **Locate the Video Element:**
    * In your HTML file, find the `<video>` element. It will look something like this:

        ```html
        <video src="path/to/your/video.mp4" controls></video>
        ```

2.  **Replace the Video Source:**
    * Replace the `src` attribute value (`path/to/your/video.mp4`) with the path to your new video file.
    * Ensure that the new video file is in a supported format (e.g., MP4, WebM).
    * If you are loading the video from an external website, replace the path with the full URL to the video.

3.  **Update Video Controls and Attributes (Optional):**
    * You can customize the video controls and attributes as needed.
    * For example, you can add `autoplay`, `loop`, or `muted` attributes.
    * You can also change the video width and height.

## Changing "Current Month" to "Previous Month"

1.  **Locate the Relevant HTML Element:**
    * In your HTML file, find the element (e.g., `<h3>`, `<p>`) that displays the "Current Month" text.

2.  **Update the Text Content:**
    * Change the text content of the element to the "Previous Month" you want to display.
    * For example, if the current month is "June" and you want to change it to "May", replace "June Specials" with "May Specials".

3.  **Update Associated Data (If Applicable):**
    * If the "Current Month" is associated with any data or functionality (e.g., a dropdown menu, a list of specials), make sure to update that data as well.
    * If the data is in the HTML, change it there.
    * If the data is in a separate JavaScript file or database, update it there.

4.  **Update the dropdown readonly value:**
    * If the dropdown for the current month is set to readonly, make sure to change the value of the dropdown to reflect the previous month.

**Example HTML Change:**

```html
<h3>Current Month Specials</h3>
<p>Specials for June 2024...</p>

<h3>Previous Month Specials</h3>
<p>Specials for May 2024...</p>
