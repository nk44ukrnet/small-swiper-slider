# Basic dragable swiper

&gt;Styles in styles.css after comment __/* Necessary styles */__ are important

&gt;Styles in styles.css after comment __/* Style the navigation controls */__ are optional

item className is predefined in .js file ".slide" 

Function that need to be called `slide(wrapper, items, prev, next)`

markup example:



> &lt;div id="slider" class="slider"&gt; <br>
    &lt;div class="wrapper"&gt; <br>
        &lt;div id="items" class="items"&gt; <br>
            &lt;span class="slide"&gt;Slide 1&lt;/span&gt; <br>
            &lt;span class="slide"&gt;Slide 2&lt;/span&gt; <br>
           &lt;span class="slide"&gt;Slide 3&lt;/span&gt; <br>
            &lt;span class="slide"&gt;Slide 4&lt;/span&gt; <br>
            &lt;span class="slide"&gt;Slide 5&lt;/span&gt; <br>
        &lt;/div&gt; <br>
    &lt;/div&gt; <br>
    &lt;a id="prev" class="control prev"&gt;&larr;&lt;/a&gt; <br>
    &lt;a id="next" class="control next"&gt;&rarr;&lt;/a&gt; <br>
>&lt;/div&gt; <br>
