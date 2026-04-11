<h1># Daily Learning</h1>
<h2>## Morning Plan</h2>
<h2>## Review</h2>

- Item 1
- Item 2
- Item 3
  
1. Step 1
1. Step 2
1. Step 3


- [x] The task is complete
- [ ] The task is not complete




Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
