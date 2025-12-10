html

`<div class="padding">block</div>`
`<span class="padding">inline</span>`

css

div, span {
	width: 200px;
	height:200px;
	border: solid;
}

.padding {
	box-sizing: border-box;
	padding: 40px;
	%% 	padding: 20px 40px 0 10px; %%
}