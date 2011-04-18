jQuery.color
=======
New API
-------------
Check out [Color Library on jQuery UI Planning Wiki](http://wiki.jqueryui.com/w/page/12137744/Color-Library) for more information about the new API in this branch

This plugin adds the ability to animate color properties on elements using jQuery's [`.animate()`](http://api.jquery.com/animate)

Supported Properties
-------
`backgroundColor`, `borderBottomColor`, `borderLeftColor`, `borderRightColor`, `borderTopColor`, `color`, `outlineColor`

Example Use
-------

    <!DOCTYPE html>
    <html>
    <head>
      <style>
    div {
    background-color:#bca;
    width:100px;
    border:1px solid green;
    }
    </style>
    <script src="http://code.jquery.com/jquery-1.5.min.js"></script>
    <script src="jquery.color.min.js"></script>
    </head>
    <body>
      <button id="go">Run</button>
      <div id="block">Hello!</div>
    <script>
    $("#go").click(function(){
      $("#block").animate({
          backgroundColor: "#abcdef"
      }, 1500 );
    });
    </script>
    </body>
    </html>
