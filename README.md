# Responsive Embed
This a simple CSS style that to embed iframe or any object in a window. The size of the object is responsive and adjusts proportionally to its container.
You can use it for iframes, flash files (swf) or video embeds like youtube iframe.
We used this CSS Style on <a href="https://www.casin.co.uk/">Casin.co.uk</a>, mostly for youtube and game embeds like [Halloween Slot Machine](https://www.casin.co.uk/halloween.html).

[Halloween Slot Machine](https://www.casin.co.uk/halloween.html)


## Usage Examples: 

## Iframe Game Embed
  
  ```
  <div class="iframe-container iframe-container-for-wxh-75">
    <iframe src="{add link here to source}" allowfullscreen frameborder="0"></iframe> 
   </div>
   
  ```
## Flash Game Embed
  
  ```
  <div class="iframe-container iframe-container-for-wxh-75">
          <embed src="{swf file source}" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="#ffffff" wmode="direct" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer" align="middle" height="100%" width="100%">
   </div>   
   
   ```
   
You Can Create more aspect ratios by updating iframe-container-for-wxh-75.
