# Practice-HTML-CSS
A web page used to practice creating shadows and tiles and flex boxes.
```html
<!DOCTYPE html>
<head>
    <link rel="stylesheet" href="Practice2.css">
    <title>What's Up!</title>
</head>
<html style="background-color:rgb(80, 80, 80);">
<header>
    <h1 id="welcome" class="shadow">Welcome!</h1>
    <h3 id="about">About Me</h3>
</header>
    <body>
        <article id="hi" class="shadow">
            Hi! My name is Tyler Hayes. I'm a computer science major at Southern University.
            I have also studied some music. I sing bass in the Southern University Concert Choir.
            I worked two semesters in the Southern Digest writing articles, but more often making graphics
            for the newspaper. In addition, I have been working with a professor to practice some
            data analysis and working on a thesis.
            Between all those activities, I have been learning how to design a webpage on the SoloLearn website.
        </article>
    </body>
    <h3>Things I Like</h3>
    <div id="league">
    <h3>League of Legends</h3>
    </div>
    <div class="photos">        
        <img src="C:\Users\tyler\Desktop\Wallpapers\Mecha Zero Sion Wallpaper.jpg" class="tile"/>
        
        <img src="C:\Users\tyler\Desktop\Wallpapers\Sion_0.jpg" class="tile"/>
        
        <img src="C:\Users\tyler\Desktop\Wallpapers\wp-galio-enchanted-logo.jpg" class="tile"/>
        
        <img src="C:\Users\tyler\Desktop\Wallpapers\promo_11_col4.jpg" class="tile"/>

    </div>
    <div>
        <h3>Taking Photos</h3>
    </div>
    <div class="photos"> 
        <img src="C:\\Users\\tyler\\Pictures\\2018-07\\DSC00659.JPG" class="tile"/>

        <img src="C:\\Users\\tyler\\Pictures\\2018-07\\DSC00657.JPG" class="tile"/>
        
        <img src="C:\\Users\\tyler\\Pictures\\2018-07\\DSC00658.JPG" class="tile"/>
        
        <img src="C:\\Users\\tyler\\Pictures\\2018-07\\DSC00691.JPG" class="tile"/>

        <img src="C:\Users\tyler\Pictures\2018-06\DSC00450.JPG" class="tile"/>

        <img src="C:\Users\tyler\Pictures\2018-06\DSC00486.JPG" class="tile"/>

        <img src="C:\Users\tyler\Pictures\2018-07\DSC00580.JPG" class="tile"/>

        <img src="C:\Users\tyler\Pictures\2018-07\DSC00581.JPG" class="tile"/>

    </div>

</html>
```
Here is the CSS:

```CSS
html{
    background-image: url("C:\\Users\\tyler\\Desktop\\Wallpapers\\GALIO_TEASER_LOGO.jpg");
    background-color: rgb(80, 80, 80);
    background-size: cover;
    background-position: center;
}
h1{
    text-align: center;
    text-shadow: rgba(0, 0, 0, 0.281) 3px 1px;
    border-style: double;
    border-color: blue;
    border-width: 5px;
    border-radius: 20px;
    background-color: rgb(253, 249, 19);
    width: 300px;
    height: 40px;
    box-shadow: 0px 1px 0px 1px rgba(0, 0, 0, 0.281);
}
h3{
    text-align: center;
    text-shadow: rgba(0, 0, 0, 0.281) 1px 1px;
    margin-top: 20px;
    margin-bottom: 20px;
}
#welcome{
    margin: auto;
    margin-bottom: 20px;
}
#about{
    margin: auto;
    margin-top: 20px;
    margin-bottom: 20px;
}
#hi{
    margin: auto;
    margin-top: 5px;
    margin-bottom: 5px;
    padding: 5px;
}
#league{
    margin: auto;
    margin-bottom: none;
}
.shadow{
    box-shadow: 0 0 10px 5px rgba(0, 0, 0, 0.7);
}
article{
    text-align: center;
    word-wrap: break-word;
    border-style: double;
    border-color: blue;
    border-width: 5px;
    border-radius: 20px;
    background-color: rgb(253, 249, 19);
    margin: auto;
    width: 50%;
    left: 330px;
    box-shadow: 0px 1px 0px 1px rgba(0, 0, 0, 0.281);
}
div{
    background-color: rgb(253, 249, 19);
    border-style: double;
    border-width: 5px;
    border-radius: 12px;
    border-color: blue;
    margin: auto;
    width: 100%;
    height: 50%;
    box-shadow: 0 0 10px 5px rgba(0, 0, 0, 0.7);
}
.photos{
    align-items: center;
    border-style: solid;
    border-width: 5px;
    border-radius: 20px;
    border-color: rgba(0, 0, 0, 0.0);
    margin: none;
    width: 100%;
    height: 70%;
    box-shadow: none;
    background: -webkit-linear-gradient(left,
    rgba(0, 0, 0, 0) 0%,
    rgba(0, 0, 0, 0.8) 25%,
    rgba(0, 0, 0, 1) 50%,
    rgba(0, 0, 0, 0.8) 75%,
    rgba(0, 0, 0, 0) 100%); 
    display:flex;
    flex-direction: row;
    flex-wrap: wrap;  
}

.tile{
    border-style: solid;
    border-width: 5px;
    border-radius: 50px;
    border-color: rgba(0, 0, 0, 0.0);
    box-shadow: none;
    margin: auto;
    max-width: 300px;
    height: 200px;
    background: none;
    flex: 1;
}
```
