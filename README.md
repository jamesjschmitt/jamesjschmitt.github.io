<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- 
      This is an HTML comment
      You can write text in a comment and the content won't be visible in the page
    -->

    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="icon" href="https://glitch.com/favicon.ico" />

    <!--
      This is the page head - it contains info the browser uses
      Like the title, which appears on the browser tab but not inside the page
      Further down you'll see the content that displays in the page
    -->
    <title>About James</title>

    <!-- The website stylesheet -->
    <link rel="stylesheet" href="/style.css" />

    <!-- The website JavaScript file -->
    <script src="/script.js" defer></script>
  </head>
  <body>
    <!--
      The body includes the content you see in the page
      Each element is defined using tags, like this <div></div>
      The attributes like class="wrapper" let us style elements in the CSS
    -->
    <div class="wrapper">
      <div class="content" role="main">
        <h1 class="title">About James</h1>
        
        <img
          src="https://static.cdn.syr.edu/static/www/original_images/hall-of-languages.jpg"
          class="illustration"
          alt="Editor illustration"
          title="Click the image!"
        />
        <div class="instructions">
          <h2>Using this project</h2>
          <p>
            
          This is my webpage. I am a MND and International Relations dual major. I enjoy hanging out with my friends and playing basketball.
          </p>
          <!--  🚧 TODO: ADD BUTTON HERE -->

          <!-- Once you've added the button from TODO.md, click it in the page -->
          <!-- Check out the function in script.js to see how it works -->
        </div>
      </div>
    </div>
    <!-- The footer holds our remix button — you can keep or delete it ✂ -->
    <footer class="footer">
      <div class="links"></div>
      <a
        class="btn--remix"
        target="_top"
        href="https://glitch.com/edit/#!/remix/glitch-hello-website"
      >
        <img
          src="https://cdn.glitch.com/605e2a51-d45f-4d87-a285-9410ad350515%2FLogo_Color.svg?v=1618199565140"
          alt=""
        />
        Remix on Glitch
      </a>
    </footer>
  </body>
</html>
