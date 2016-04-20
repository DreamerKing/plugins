#  引入FontAwesome  
1. 直接引入  
```
<link rel="stylesheet" type="text/css" href="/path/font-awesome.min.css">
```
2. 使用Ruby包管理工具gem安装SASS or LESS版
    1. 添加Gemfile
    ```
    gem 'font-awesome-sass' or 'font-awesome-less'
    ```
    2. 执行    
    ```sh
    $ bundle  
    ```
    3. 安装
    ```
    gem install font-aswesome-sass  or font-aswesome-sass
    ```
    如果使用Rails，可以在项目中添加它。如在`application.less`or`application.less`天机如下变量：
    ```
    @import "font-awesome-sprockets";
    @inport "font-awesome"
    ```
3. 传统方法添加
   1. 复制`font-awesome/`到项目中;  
   2. 打开项目文件`font-awesome/less/variables.less`或`font-aswesome/sess/_variable.scss`编辑`@fa-font-path`或`$font-font-path`变量指向字体目录。
    ```
    @fa-font-path: "../font"
    ```

#  使用 
1. 基本用法  
    Font Awesome图标使用运用CSS类`fa`和图标名称将其放置在任何位置上，一般
    放置在内联元素中如`<i>`和`<span>`  
    ```html 
        <i class="fa fa-camera-retro" aria-hidden="true"></i>fa-camera-retor
    ```

2. 图标大小  
    可以使用类`fa-lg`,`fa-2x`,`fa-3x`,`fa-4x`,`fa-5x`来改变图标的大小。
    ```html 
    <i class="fa fa-camera-retro fa-lg"></i>fa-lg
    <i class="fa fa-camera-retro fa-5x"></i>fa-5x
    ```

3. 固定宽度的图标 
    可以使用`fa-fw`来固定图标的宽度。
    ```html 
    <div class="list-group">
        <a class="list-group-item" href="#"><i class="fa fa-home fa-fw" aria-hidden="true"></i>&nbsp;Home</a>
        <a class="list-group-item" href="#"><i class="fa fa-book fa-fw" aria-hidden="true"></i>&nbsp; Library</a>
        <a class="list-group-item" href="#"><i class="fa fa-pencil fa-fw" aria-hidden="true"></i>&nbsp; Applications</a>
        <a class="list-group-item" href="#"><i class="fa fa-cog fa-fw" aria-hidden="true"></i>&nbsp; Settings</a>
    </div>
    ```

4. 图标列表  
                



