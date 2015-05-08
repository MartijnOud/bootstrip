# Bootstrip

The popular [Bootstrap framework](https://github.com/twbs/bootstrap) with almost all componest stripped leaving the **responsive** and **grid** components. Generated with Bootstrap Customizer. 

This allows you to integrate the responsive framework in your website without messing up your current stylesheet.

## Your current stylesheet
    <style>
    #wrapper { width:960px; margin:0px auto; }
    #sidebar { width:320px; background-color:blue; color:white; }
    #content { width:640px; text-decoration:blink; }
    </style>
    <div id="wrapper">
        <div id="sidebar">
            - sidebar content-
        </div>
        <div id="body">
            - body content-
        </div>
    </div>

## Your new stylesheet    
    <style>
    @import url("bootstrip.min.css");
    #sidebar { background-color:blue; color:white; }
    #content { text-decoration:blink; }
    </style>
    <div class="col-xs-12" id="wrapper">
        <div class="col-xs-4" id="sidebar">
            - sidebar content-
        </div>
        <div class="col-xs-8" id="body">
            - body content-
        </div>
    </div>