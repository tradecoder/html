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
        <button>Next Button</button>
    </div> 
  
  
  </body>  
</html>
```
Here is the output <br/>

# It's Awesome!
We have learnt the basic HTML and we are now able to build an HTML page.<br/>
[First Button](#)

## It's very interesting!
We are making it more. <br/>
[Next Button](#)


