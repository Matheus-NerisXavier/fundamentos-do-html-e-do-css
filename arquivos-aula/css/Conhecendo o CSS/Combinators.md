Combinators

- Descendent
- List
- Next sibling
- Child

`<article>`
`<h2>The Lorem Ipsum Dolor ...</h1>`

`<p>`
	`**Lorem Ipsum** is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a <span>galley of type and scrambled</span> it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. <mark>It was popularised</mark> in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.`
`</p>`

`</article>`

Descendent

article p {
	color: red;
}

List 

span, mark {
	color: red;
}

Next sibling (irmão proximo)

p + p {
	color: red;
}

Child

`<aside>`
	`<ul>`
	`<li> One`
		`<ul>`
			`<li>item 1 </li>`
			`<li>item 2</li>`
		`</ul>`
	`</li>`
			`<li>Two</li>`
			`<li>Three</li>`
		`</ul>`
`<aside>`

aside > ul {
	margin-top: 20px;
}