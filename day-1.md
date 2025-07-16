# Daily Learning
## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="middle">

- [x] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```

you can play around with these:

This is *italic* text.
This is also _italic_ text.

This is **bold** text.
This is also __bold__ text.

_This is **italic and bold** text_ using a single underscore for italic and double asterisks for bold.
__This is bold and *italic* text__ using double underscores for bold and single asterisks for italic.

To use a literal asterisk, precede it with an escape character; in GFM, that's a backslash (\). This example results in the underscores and asterisks being shown in the output.
\_This is all \*\*plain\*\* text\_.

1. First
1. Second
1. Third

- First
  - Nested
- Second
- Third


First|Second
-|- 
1|2
3|4

**Note:** the "- | -" make the line above the header of the table







> This is quoted text.


This is `code`.



```javascript
var first = 1;
var second = 2;
var sum = first + second;
```

Typing an @ symbol followed by a GitHub username sends a notification to that person about the comment. This is called an "@mention", because you're mentioning the individual. You can also @mention teams within an organization.
@githubteacher


