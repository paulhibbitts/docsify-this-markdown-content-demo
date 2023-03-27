# Hello!

This is a sample Markdown file for display by Docsify-This.

## Markdown Javascript Code Block 
```javascript
<script>
  alert('Hello, World!');
</script>
```

## Markdown CSS Code Block 
```css
body {
  font-family: sans-serif;
}

h1 {
  color: darkred;
}
```

## Markdown Kotlin Code Block 
```kotlin
fun main(args: Array<String>) {
    println("Hello, World!")
}
```

## Markdown Image
![Octocat](https://octodex.github.com/images/original.png)

## Markdown Image (Styled with Docsify-This CSS Class `image-75`%)
![Octocat](https://octodex.github.com/images/original.png ':class=image-75')

## Markdown Button (Styled with Docsify-This CSS Class `button`)
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button')

<style>
.markdown-section .mybutton, .markdown-section .mybutton:hover {
  cursor: pointer;
  color: #CC0000;
  height: auto;
  display: inline-block;
  border: 2px solid #CC0000;
  border-radius: 4rem;
  margin: 2px 0px 2px 0px;
  padding: 8px 18px 8px 18px;
  line-height: 1.2rem;
  background-color: white;
  font-family: -apple-system, "Segoe UI", "Helvetica Neue", sans-serif;
  font-weight: bold;
  text-decoration: none;
}
</style>

## Markdown Button (Styled with custom CSS Class `mybutton`)
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=mybutton')

## Markdown Footnote
Here is a simple footnote[^1]. With some additional text after it.

## HTML iFrame (YouTube)
<iframe width="560" height="315" src="https://www.youtube.com/embed/lJIrF4YjHfQ">
</iframe>

## HTML iFrame (YouTube, Styled with Docsify-This CSS Class `video-container-16by9`)
<div class="video-container-16by9"><iframe width="560" height="315" src="https://www.youtube.com/embed/lJIrF4YjHfQ">
</iframe></div>

## HTML iFrame (Google Slides)
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRnnRFelgw1ksq_p8Eryg3dnyLCRRLPf5fBgdwdv9p-tCIwcxqWvzDGrGbjxGHL7HqEJVpmV26ntk3a/embed?start=false&loop=false&delayms=3000" frameborder="0" width=780" height="585" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## HTML iFrame (Google Slides, Styled with Docsify-This CSS Class `video-container-16by9`)
<div class="video-container-16by9"><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRnnRFelgw1ksq_p8Eryg3dnyLCRRLPf5fBgdwdv9p-tCIwcxqWvzDGrGbjxGHL7HqEJVpmV26ntk3a/embed?start=false&loop=false&delayms=3000" frameborder="0" width=780" height="585" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></div>

## HTML iFrame (H5P) 
<iframe src="https://h5p.org/h5p/embed/214115" width="778" height="279" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="User-Centered Design"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

## HTML Embed (using Embed.ly) 
<a class="embedly-card" data-card-controls="0" data-card-align="left" href="https://blog.prototypr.io/defining-usability-e7bf42e8abd0">Defining usability</a>

[^1]: My reference.
