# 7 Advanced Markdown Tips!

Step up your Markdown game with useful and practical tips.


![Women Typing](https://raw.githubusercontent.com/6aravind/tidbits/main/assets/images/markdown_cover.jpg)


Photo by [Suzy Hazelwood](https://www.pexels.com/photo/black-typewriter-machine-typing-on-white-printer-paper-1303835/) from Pexels 


# 1. Align Images Horizontally

Want to display images side by side for comparison? Easiest way to do is place the images inside a table and have image caption as the title.


<script src="https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=01_Markdown.md"> </script>


[Image Source](https://pexels.com)

---

# 2. Using Reference for Links

Don't repeat yourself by typing the URL multiple times in the same Markdown file. With the help of reference, we can define the link once and reuse it as many times as required.


<script src="https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=02_Markdown.md"> </script>

---

# 3. Comment

You can add comments by wrapping the comment inside `[]` and following it with `#`. If you are familiar with HTML then go with `<!--Comment Here-->`


<script src="https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=03_Markdown.md"> </script>

---

# 4. Embed Video with Thumbnail

Let the reader know that this is a video by having the screenshot (with video control buttons) as the thumbnail. By using the nested `[]` , we can make a picture point to video URL.


<script src="https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=04_Markdown.md"> </script>

[Credit](https://stackoverflow.com/a/29862696)

---

> **For rest of the tips, we are going to use HTML.**

# 5. Wrapping Text Around Image

Place the image in either side of the text by changing `align` value to `left|right`. Yes, this requires bit of HTML, but works on most platforms like GitHub and Reddit. 


<script src="https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=05_Markdown.md"> </script>

[Credit](https://github.com/DavidWells/advanced-markdown/blob/master/README.md#advanced-formatting-tips)

---


# 6. Toggle Bar

Replicate [Toggles from Notion](https://www.notion.so/Toggles-c720af26b4bd4789b736c140b2dc73fe) using HTML. You can add `open`  option to `details` tag to set the default behaviour of the toggle/dropdown as opened. Header text is to be placed inside the `summary` tag. 
Since Github supports this functionality, try to make most out of your [README](https://github.com/6aravind/tidbits).


<script src="https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=06_Markdown.md"> </script>

---

# 7. Line Breaks

Use `br` HTML tag. Can't beleive that Markdown doesn't support this natively 🙄


<script src="https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=07_Markdown.md"> </script>

---
