# 7 Advanced Markdown Tips!

Step up your Markdown game with useful and practical tips.


![Women Typing](https://raw.githubusercontent.com/6aravind/tidbits/main/assets/images/markdown_cover.jpg)


Photo by [Suzy Hazelwood](https://www.pexels.com/photo/black-typewriter-machine-typing-on-white-printer-paper-1303835/) from Pexels 


# 1. Align Images Horizontally

Want to display images side by side for comparison? Easiest way to do is place the images inside a table and have image caption as the title.

## Markdown

```
|First Image|Second Image|
|:-:|:-:|
|![First Image](https://images.pexels.com/photos/585759/pexels-photo-585759.jpeg?h=750&w=1260)|![Second Image](https://images.pexels.com/photos/1335115/pexels-photo-1335115.jpeg?h=750&w=1260)|
```

## Rendered Output

|First Image|Second Image|
|:-:|:-:|
|![First Image](https://images.pexels.com/photos/585759/pexels-photo-585759.jpeg?h=750&w=1260)|![Second Image](https://images.pexels.com/photos/1335115/pexels-photo-1335115.jpeg?h=750&w=1260)|

[Image Source](https://pexels.com)

---

# 2. Using Reference for Links

Don't repeat yourself by typing the URL multiple times in the same Markdown file. With the help of reference, we can define the link once and reuse it as many times as required.


## Markdown

https://gist.github.com/6aravind/07df0443300b1f83e0423200ef3979df.js?file=02_Markdown.md

```
1. Check out my [Github Profile][github]
2. Don't forget star [Repo][github]

[github]: https://github.com/6aravind "Github Profile"
```

## Rendered Output

1. Check out my [Github Profile][github]
2. Don't forget star [Repo][github]

[github]: https://github.com/6aravind "Github Profile"

---

# 3. Comment

You can add comments by wrapping the comment inside `[]` and following it with `#`. If you are familiar with HTML then go with `<!--Comment Here-->`

## Markdown

```
[Comment Here]: # 
blah blah blah
<!--Comment Here-->
```

## Rendered Output

[Comment Here]: # 
blah blah blah
<!--Comment Here-->

---

# 4. Embed Video with Thumbnail

Let the reader know that this is a video by having the screenshot (with video control buttons) as the thumbnail. By using the nested `[]` , we can make a picture point to video URL.

## Markdown

```
### Youtube Video: Life as an Engineer - WFH

[![][thumbnail]](https://youtu.be/Rgx8dpiPwpA "Life as an Engineer - WFH")

[thumbnail]: https://raw.githubusercontent.com/6aravind/tidbits/main/assets/images/markdown_Life%20as%20Engineer.png
```

## Rendered Output

### Youtube Video: Life as an Engineer - WFH

[![][thumbnail]](https://youtu.be/Rgx8dpiPwpA "Life as an Engineer - WFH")

[thumbnail]: https://raw.githubusercontent.com/6aravind/tidbits/main/assets/images/markdown_Life%20as%20Engineer.png

[Credit](https://stackoverflow.com/a/29862696)

---

> **For rest of the tips, we are going to use HTML.**

# 5. Wrapping Text Around Image

Place the image in either side of the text by changing `align` value to `left|right`. Yes, this requires bit of HTML, but works on most platforms like GitHub and Reddit. 

## Markdown

```
### You're Breathtaking

<img align="right" width="100" height="100" src="https://media.tenor.com/images/6a136e1c2d7b30298a5b657348097a60/tenor.gif">

At the 2019 rendition of E3, an eccentric gamer in attendance interrupted Keanu Reeves' presentation of the role-playing game (RPG) Cyberpunk 2077, loudly claiming, “"You're breathtaking,"” which was directed at the actor-cum-presenter. The image macro used to build the "You're Breathtaking" meme generally features a still of Keanu Reeves pointing at someone in the audience in front of him - that someone is Peter Sark, though there are no images from Keanu's point of view that have since been used as part of the "You're Breathtaking" meme.
```

## Rendered Output

### You're Breathtaking

<img align="right" width="100" height="100" src="https://media.tenor.com/images/6a136e1c2d7b30298a5b657348097a60/tenor.gif">

At the 2019 rendition of E3, an eccentric gamer in attendance interrupted Keanu Reeves' presentation of the role-playing game (RPG) Cyberpunk 2077, loudly claiming, “"You're breathtaking,"” which was directed at the actor-cum-presenter. The image macro used to build the "You're Breathtaking" meme generally features a still of Keanu Reeves pointing at someone in the audience in front of him - that someone is Peter Sark, though there are no images from Keanu's point of view that have since been used as part of the "You're Breathtaking" meme.


[Credit](https://github.com/DavidWells/advanced-markdown/blob/master/README.md#advanced-formatting-tips)

---


# 6. Toggle Bar

Replicate [Toggles from Notion](https://www.notion.so/Toggles-c720af26b4bd4789b736c140b2dc73fe) using HTML. You can add `open`  option to `details` tag to set the default behaviour of the toggle/dropdown as opened. Header text is to be placed inside the `summary` tag. 
Since Github supports this functionality, try to make most out of your [README](https://github.com/6aravind/tidbits).

## Markdown

```
<details open> 
    <summary> 
      What is Lorem Ipsum?
    </summary>
      Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</details>

<details> 
    <summary> 
      Why do we use it?
    </summary>
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).
</details>
```

## Rendered Output

<details open> 
    <summary> 
      What is Lorem Ipsum?
    </summary>
      Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</details>

<details> 
    <summary> 
      Why do we use it?
    </summary>
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).
</details>

---

# 7. Line Breaks

Use `br` HTML tag. Can't beleive that Markdown doesn't support this natively 🙄

## Markdown
```
Hey! <br> How You Doin'?
```

## Rendered Output

Hey! <br> How You Doin'?


---
