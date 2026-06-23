# what is css   ?
1. css stands for cascading stylesheet 
2. css will be used to provides style in you webpage (html)
3. css file extension .css (style.css)

# what is cascading ?

1. step by step provides style on your web pages 
2. css provides step by step stylesheet on your webpages (html) 

# types of css 
 1. there are three of css 

   1. inline css
   2. internal css
   3. external css

# what is inline css ?
  1. inline css called inside of any html tags using <style> i.e called inline stylesheet 
  2. inline css priority is higher     

 **examples of inline css**

 ```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
</head>
<body style="background: rgba(5,0,0,0.2);">
<div style="width: 50%; height: auto; margin: auto; background-color: aquamarine; padding:25px">
<h1>Get your Name : </h1> 
<p><b style="color: blue;">Your name is :</b>Brijesh kumar pandey</p> 
<p><b style="color: blue;">Your details is :</b>
<details>
<summary>Click for more</summary>
<p> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nisi ad aperiam voluptates sapiente doloribus earum odio quaerat nemo ratione omnis repellendus deleniti ut harum, sunt non commodi maxime quos provident.

</p>
</details>
</p>   
</div>
</body>
</html>
 ```   


# what is internal css ?
  1. internal css called inside of  html <head> tags using <style> tag 
  2. internal style is used for single web pages 


 **examples of inline css**

 ```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
<style>
body 
{
background-color: aqua;    
}    
div 
{
width: 40%;
height: auto;
margin: auto;
padding: 25px;
background-color: white;    
}

b 
{
color: blue;    
}
div:hover 
{
background: rgba(255,0,0,0.7);
color: white;    
}
</style>
</head>
<body>
<div>
<h1>Get your Name : </h1> 
<p><b style="color:coral">Your name is :</b>Brijesh kumar pandey</p> 
<p><b style="color:coral">Your details is :</b>
<details>
<summary>Click for more</summary>
<p> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nisi ad aperiam voluptates sapiente doloribus earum odio quaerat nemo ratione omnis repellendus deleniti ut harum, sunt non commodi maxime quos provident.
</p>
</details>
</p>   
</div>
</body>
</html>
 ```   


# what is external css ?

  1. external css called inside of  html using <head> tags with <link> tag with style.css
  2. external style is used for provides style on multiple web pages 
  3. <head>
        <link rel="stylesheet" href="css/style.css" type="text/css">
      </head>

   4. external css will saved via style.css 

 **examples of external  css**

 ```
 ```   
