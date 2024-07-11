## HTML & CSS from scratch 
- This repository covers all the concepts required for making a fully responsive website from scratch using plain HTML, CSS and little bit of Media Queries only.

#### 01 HTML Basics
- use [html entity](https://www.thoughtco.com/html-code-for-common-symbols-and-signs-2654021) for writing symbols(like currency symbols, etc) in html.
- to open link (`<a> tag`) in new tab use attribute `target="_blank"`.

#### 02 CSS Basics













###### refer [this](https://github.com/SuperSimpleDev/html-css-course-2022/tree/main/1-exercise-solutions) for assignments and there solutions.


#### Refer this site to escape characters in html: https://www.freeformatter.com/html-escape.html
#### How to show css and html code in website
```html
<pre><code class = "language-css">
<!-- Put CSS code here (as it is)-->
</code></pre>

<pre><code class = "language-markup">
<!-- Put HTML code here (after escaping HTML characters) refer website to do this: https://www.freeformatter.com/html-escape.html-->
</code></pre>
```
- Refer whole code here
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.28.0/themes/prism.min.css" rel="stylesheet" />
  <!-- Prism.js JavaScript -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.28.0/prism.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.28.0/components/prism-markup.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.28.0/components/prism-css.min.js"></script>
</head>

<body>
  
  <div style="display: flex; justify-content: space-around;">
    <div>
      <h2>CSS code</h2>
      <pre><code class="language-css">
      body{
        height: 3000px;
      }
      .header{
        position: fixed;
        top: 0px;
        left: 0px;
        right: 0px;
        height: 50px;
        background-color: black;
        color: white;
      }
      .sidebar{
        position: fixed;
        top: 50px;
        left: 0px;
        bottom: 0px;
        background-color: green;
        color: white;
        width: 72px;
      }
      .close-btn{
        background-color: red;
        color: white;
        position: absolute;
        
      }
    </code></pre>
    </div>

    <div>
      <h2>HTML Code</h2>
      <pre><code class="language-markup">
      &lt;!DOCTYPE html&gt;
      &lt;html lang=&quot;en&quot;&gt;
      &lt;head&gt;
        &lt;meta charset=&quot;UTF-8&quot;&gt;
        &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
        &lt;title&gt;Document&lt;/title&gt;
      &lt;/head&gt;
      &lt;body&gt;
        &lt;div class=&quot;header&quot;&gt;
          header
        &lt;/div&gt;
        &lt;div class=&quot;sidebar&quot;&gt;
          SideBar
          &lt;div class=&quot;close-btn&quot;&gt;
            X
          &lt;/div&gt;
        &lt;/div&gt;
      &lt;/body&gt;
      &lt;/html&gt;
    </code></pre>
    </div>
  </div>


</body>

</html>
```