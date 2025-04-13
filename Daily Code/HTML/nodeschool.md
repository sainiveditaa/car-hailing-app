
## Challenge 1: Hello World
Through this excercise from **learnyouhtml** from *Nodeschool*, Boilerplate for an HTML document was learnt.

```
<!DOCTYPE html>
     <html>
       <head>
         <meta charset="utf-8">
         <title>Hello, world!</title>
       </head>
       <body>
         here is a body
       </body>
     </html>
```

## Challenge 2: Tags
This exercise was an intorduction to basic HTML tags such as **p** - *paragraph tag* & **hr** - *Horizontal rule tag*.
```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
	<p>
		Here i put down a body text that includes a paragraph to check the p tag</p>
	<hr>
	<p>	
		Here i put down a body text that includes a paragraph to check the p tag</p>

	</body>
</html>
```

## Challenge 3: Attributes

This exercise was an intorduction to adding an image to a HTML document using img tag and control it using tag attributes.
```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
	<img 
    	src="https://example.com/image.jpg" 
    	alt="A beautiful scenery with mountains and a lake"
    	width="400" 
    	height="300"
  	>

	</body>
</html>
```
## Challenge 4: Inline Tags
This exercise put use the following tags *strong, em, sup, sub
  and span* to use.
```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
	<p> The sky is<strong>as blue as</strong> the sea.</p>
	<p> The sky is<em>as blue as</em>the sea.</p>
	<p> blue<sup>sky</sup>and the blue sea</p>
	<p> blue<sub>sky</sub>and the blue sea</p>
	<p> here we use<span>span that is used to hold some texts</span> okay we need some text here as well</p> 

	</body>
</html>
```

## Challenge 5: Headings
This challenge teaches how to use the six levels of headings with the heading tag. 
```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
	<h1> Heading elements </h1>
	<h2>Summary</h2>
	<p>
		Here i put down a body text that includes a paragraph
which is supposed to be the summary to check the p tag</p>
	<h2>Examples</h2>
	<h3>Example 1</h3>
	<p>	
		Here i put down a body text that includes a paragraph to check the p tag</p>
	<h3>Example 2</h3>
	<p>	
		Here i put down a body text that includes a paragraph to check the p tag</p>
	<h2>See also</h2>
	<p>Here i put some links to be opened when see also is clicked</p>
	</body>
</html>
```

## Challenge 6: Lists
This challenge was an introduction to lists. It included three types of lists to practice : *ordered,unordered and definition lists*.

```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
       <p>Ordered list </p>
	<ol>
		<li>One</li>
		<li>Two</li>
		<li>Three</li>
	</ol>
       <p>Unordered list </p>
	<ul>
		<li>One</li>
		<li>Two</li>
		<li>Three</li>
	</ul>
       <p>Definition list </p>
	<dl>
		<dt>Definiton term 1</dt>
			<dd>Here comes the definition of the given term.</dd>
		<dt>Definition term 2</dt>
			<dd>Here comes the definition of the given term.</dd>
		</dl>
	</body>
</html>
```
## Challenge 7: Tables
This challenge briefed about making tables in HTML using the tags - *table*, *tr* - table row, *th* - table heading, *td* - table data.

```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
	<table>
		<tr>
			<th>Europe</th>
			<th>Asia</th>
			<th>Africa</th>
		</tr>
		<tr>
			<td>Ukraine</td>
			<td>China</td>
			<td>Eygpt</td>
		</tr>
		<tr>
			<td>Poland</td>
			<td>India</td>
			<td>Kenya</td>
		</tr>
		<tr>
			<td>Italy</td>
			<td>Thailand</td>
			<td>Sudan</td>
		</tr>
	</table>
	</body>
</html>
```

## Challenge 8: Blocks

```
<!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <title>Block</title>
      </head>
      <body>

        <header>
          <nav>
            <ul>
              <li>Item 1</li>
              <li>Item 2</li>
              <li>Item 3</li>
            </ul>
          </nav>
        </header>

        <main>
          <article>
            <section>
              <h1>Heading 1</h1>
              <p>A paragraph of text</p>
            </section>
            <section>
              <h1>Heading 2</h1>
              <p>A paragraph of text</p>
            </section>
          </article>
          <aside>
            <ul>
              <li>Item 1</li>
              <li>Item 2</li>
              <li>Item 3</li>
            </ul>
          </aside>
        </main>

        <footer>
          <p>Copyright message</p>
        </footer>
      </body>
    </html>
```

## Challenge 9: Links and References
This challenge taught how to make links and clickable images.
```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
		<a href="https://google.com">
			<img 
    			src="data:image/png;base64,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" 
    			alt="An example image"
    			width="400" 
    			height="300"
  			> 
  		</a>

	</body>
</html>
```
## Challenge 10: Forms
This challenge was an introduction to **forms** in HTML.
```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Hello, world!</title>
	</head>
	<body>
		<form >
  			<input type="text">
                        <input type="password">
                        <input type="submit">
		</form>

	</body>
</html>
```
## Challenge 11: Styles and scripts
```
<!DOCTYPE html>
<html>
       <head>
        	<meta charset="utf-8">
        	<title>Links</title>
	
		<style>
     		body {
       	background: blue;
     		}
     		</style>
	 	<link href="style.css" rel="stylesheet">
     		</head>

     	<body>

        <script>
       		console.log('Hello, world!');
     		</script>
	</body>
</html>
```
