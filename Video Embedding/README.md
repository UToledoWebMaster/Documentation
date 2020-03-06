# Instructions

1. Copy the HTML from the text file into the source code of your page.
2. Replace the placeholder URL in the src attribute of the iframe with the embed-style URL of the video you want to embed. (Finding the embed-style URL of a video might take some digging. If you can't find it through a "Share" or "Embed" button on the page of the video, you might have to do some Google searching to find an embed-style URL template for that particular video host.)

Note: This code assumes that the video being embedded is of 16:9 aspect ratio. That is almost always the case. If it is not the case for a particular video, the padding-top property of the fullWidthVideo class will need to be overridden with a value that matches the source aspect ratio. (value = video height / video width * 100%)