# html
LEARN HTML

## HTML Tutorial

## HTML Basic (for the Beginners)

HTML is Hypertext Markup Language. It is used to build websites. Anyone who wants to learn to build websites, learning HTML is a must. 
A single HTML web page has mainly some essential parts- `html, head, body`. Here is a basic formation of HTML pages to understand at the starting level.
```
<!DOCTYPE html>
<html>
  <body>
  
    Web contents will go here inside the body
    Web contents will go here inside the body
    Web contents will go here inside the body    
  
  
  </body>  
</html>
```
An HTML page must start with `<!DOCTYPE html>` <br/>
Then the document must start with `<html>` tag and end with `</html>` tag. </br>
Then all the contents will be placed inside `<body> and </body>` tag.</br>



HTML elements are wrapped in some specific tags. Every tag has an opening and a closing tag except only a few of them, at the same time this type of tag is self closing tag. <br/>
`<>` this is an opening tag mark and `</>` this is a closing tag mark. <br/>
So if we want to use the html tag in our page we need to use it in such way <br/>
```
<html>

  Above is with the opening tag
  And below is with the closing tag

</html>
```

We'll discuss more about the tags later. Now let's see some most common used tags for displaying the elements <br/>

`<div> </div>` This div (division) tag is used to wrap a bunch of code, or a part of the page to make it separate/devide from other contents.<br/>
`<h1> </h1>` This h1 (Header 1) tag is used to make a Heading text of some specified contents. <br/>
There are also some other Header tags, `h2, h3, h4, h5 and h6`. All it's just text size matter. Let's see how they look like<br/>
# This is the text size of h1 header
## This is the text size of h2 header
### This is the text size of h3 header
#### This is the text size of h4 header
##### This is the text size of h5 header
###### This is the text size of h6 header
`<p> </p>` This p (paragraph) tag is used to write some content as in paragraph. <br/>
`<button> </button>` This button tag creates a button.<br/>

Now let's build our first HTML page with the above knowledge. Here is the code
```
<!DOCTYPE html>
<html>
  <body>
  
    <div>
        <h1>It's Awesome!</h1>
        <p>We have learnt the basic HTML and we are now able to build an HTML page.</p>
        <button>First Button</button>
    </div>  
    
    
    <div>
        <h2>It's very interesting!</h2>
        <p>We are making it more.</p>
        <p>more and more.</p>
        <button>Next Button</button>
    </div> 
  
  
  </body>  
</html>
```
Here is the output <br/>
`-------------------------------------------------------------------------------`
# It's Awesome!
We have learnt the basic HTML and we are now able to build an HTML page.<br/>
[First Button](#)

## It's very interesting!
We are making it more. <br/>
more and more.<br/>
[Next Button](#)

`-------------------------------------------------------------------------------` 

So, now you can build a web page with a large content by adding some more `div` and then other necessary elements. Try yourself to create a large page with your own contents. <br/>

## Let's move forward
Now we'll learn about some HTML attributes.<br/>
If you look at the above codes, you'll find there are two `<div>`. In a real web page you'll find there many `div` many `p` and so on. Now, think if I tell you to work on a `div`, how will you find that specific `div` or other elements? Any idea? Yes, there is a way! We need some reference, right? So, we can do this by giving an identity to every `div` so that we can refer it easily. In HTML identity is defined by an `id` attribute. Let's see how to add it<br/>

```
<div id="home">          </div>

<div id="learn">          </div>

<div id="earn">      </div>
```
That `id` inside the opening `div` tag separated by a space is an HTML attribute and the names inside that quote marks are the `value` of the attributes. Remember, you must put the `name value` for `id` attribute starting with an alphabet, never with a number.<br/>
This way, inside an opening tag of every element different HTML attributes are to set for different requirements. Now let's add an id attribute to the `p` element.<br/>
`<p id="my-first-paragraph">      </p>`<br/>
Hope it makes sense about HTML attributes. <br/>

Okay, now to see how we can add an image in our web page:<br/>
An image is to put in a web page with `img` tag with a `src` attribute ( (image source / path)). Here's an example <br/>
`<img src="put the image source url here" />` <br/>

We are going to place an image here with a valid url, look at this code <br/>
`<img src="https://github.com/tradecoder/html/blob/main/images/tradecoder.png" />`<br/>
An the output is: <br/>
<img src="https://github.com/tradecoder/html/blob/main/images/tradecoder.png" width="200px"/> <br/>

So, now, we are able to build a web page with some contents, buttons and images. And before we move forward, we'll learn to apply some styles in our page. There are different ways to do it, but for this time we'll learn it with `style` attribute. Here is an example:<br/>
`<div style="background-color:red">     </div>`<br/>
As we can see, here we applied `style` attribute and the background color of the div set to red, that means it will make a red color div. <br/> 
`<div style="background-color:blue">     </div>`<br/>
Here the div will be blue color. You also can make it `black, white, orange, tomato, silver, gray` and so on. <br/>
Now let's add some more value to the `sytle` attribute to make more sense,
`<div style="background-color:blue; width:500px; height:300px;">     </div>`<br/>
This `div` will be a blue color div, its width will be 500px and height will be 300px. We can make different size of div in this way by changing its value as our own.  <br/>
Let's learn one more style, when you say `color` it applies for text/font color, and when you say `background-color` it applies for the background. Let's see an example: <br/>
```
<div style="background-color:blue; width:500px; height:300px;">     
<h1 style="color:white"> Hello </h1>
</div>
```
Gues the output. The div will be blue color but the text will be white color. Interesting? Yes, now we need to make well designed web page. First we need to make a plan how our page will look like. Here is a pattern, we'll work on it. <br/>
<img src="https://github.com/tradecoder/html/blob/main/images/webpage-pattern.jpg" > <br/>
 
Now, let's build a page following this pattern. We'll put all the necessary codes inside the `body` tag. Then we'll use a `header` tag for header contents, `div` tag for body contents and `footer` tag for footer contents. We also could use `div` tag for header and footer section, that's ok. But fortunately we have also a `header` and a `footer` tag in HTML for doing this. So, we'll use `header` and `footer` tag here:  <br/>

```
<body>

  <header style="background-color:blue; width:100%; height:80px;">
      <h1>Our first web page</h1>
  </header>

  <div style="background-color:white; width:100%;">
      <p>Here will go our text contents</p>
      <p>More contents here</p>
      <p>More topics here</p>
  </div>


  <footer style="width:100%; background-color:red;">
      <p>By : your name here</p>
  </footer>

</body>
```
Well, so far we've learnt the basic HTML code writing system. Now we are going to explain more about it but before that we'll learn some basic styles of HTML with stylesheet called CSS or Cascading Style Sheets. 

