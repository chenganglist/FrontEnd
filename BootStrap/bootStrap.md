##bootStrap是一套前端开发UI库
使用方式为：先引用bootStrap，然后再具体使用其中的漂亮控件和方法


###1、引用BootStrap库

base.html

    <!DOCTYPE html>
    <html lang="zh-CN">
      <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <!-- 上述3个meta标签*必须*放在最前面，任何其他内容都*必须*跟随其后！ -->
        <title>Bootstrap 101 Template</title>

        <!-- Bootstrap -->
        <link rel="stylesheet" href="http://cdn.bootcss.com/bootstrap/3.3.4/css/bootstrap.min.css">
        
      </head>
      <body>
        <h1>你好，bootstrap！</h1>

        <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
        <script src="http://cdn.bootcss.com/jquery/1.11.2/jquery.min.js"></script>
        <!-- Include all compiled plugins (below), or include individual files as needed -->
        <script src="http://cdn.bootcss.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
      </body>
    </html>

 base.html中已经引入了bootstrap，将其保存，我们就可以使用bootstrap提供的样式了。


###2、使用库中的图标

bootstrap默认提供了二百多个图标。我们可以通过span标签来使用这些图标：
只需按照bootStrap中的class选择器，指定样式，就可以开发各种风格的控件：


    <h3>图标</h3>   
    <span class="glyphicon glyphicon-home"></span>
    <span class="glyphicon glyphicon-signal"></span>
    <span class="glyphicon glyphicon-cog"></span>
    <span class="glyphicon glyphicon-apple"></span>
    <span class="glyphicon glyphicon-trash"></span>
    <span class="glyphicon glyphicon-play-circle"></span>
    <span class="glyphicon glyphicon-headphones"></span>

###3、按钮

　　<button></button>标签用于创建按钮，bootstrap提供了丰富的按钮样式。
通过class选择器可以具体选择按钮的风格。

    <h3>按钮</h3>
    <button type="button" class="btn btn-default">按钮</button>
    <button type="button" class="btn btn-primary">primary</button>
    <button type="button" class="btn btn-success">success</button>
    <button type="button" class="btn btn-info">info</button>
    <button type="button" class="btn btn-warning">warning</button>
    <button type="button" class="btn btn-danger">danger</button>
    
    <h3>按钮尺寸</h3>
    <button type="button" class="btn btn-default">按钮</button>
    <button type="button" class="btn btn-primary btn-lg">primary</button>
    <button type="button" class="btn btn-success btn-sm">success</button>
    <button type="button" class="btn btn-info btn-xs">info</button>

    <h3>把图标显示在按钮里</h3>
    <button type="button" class="btn btn-default"><span class="glyphicon glyphicon-home"></span>&nbsp;&nbsp;按钮</button> 　　


按钮除了有默认的大小外，bootstrap还提供三个参数来调整按钮的大小，分别是：btn-lg、btn-sm和btn-xs。


###4、下拉菜单

　　下拉菜单是最常见的交互之一，bootstrap提供了漂亮的样式。
通过classs选择器和id选择器选取bootstrap的控件。


     <h3>下拉菜单</h3>
    <div class="dropdown">
      <button class="btn btn-primary dropdown-toggle" type="button" id="dropdownMenu1" data-toggle="dropdown" aria-expanded="true">
        Dropdown
        <span class="caret"></span>
      </button>
      <ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Action</a></li>
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Another action</a></li>
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Something else here</a></li>
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Separated link</a></li>
      </ul>
    </div>





