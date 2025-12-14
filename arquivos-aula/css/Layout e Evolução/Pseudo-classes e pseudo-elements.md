
 Pseudo-classes e pseudo-elements

hover 
passar o mouse em cima
div:hover{
	background-color: blue;
}

functional

not () -> não
div:not(.nao){
	background-color:blue
}

has() -> tem
section:has(div:hover) {
	border: 2px solid red;
}

structural 

root
:root {

}

nth-child(n)

div:nth-child(2) {
	background-color: red;
}


pseudo-elements 

first-letter
div::first-letter {
	font-size: 40px
}

before / after

div{ 
	position: relative;
}

div::before {
	content: "";
	height: 6px;
	width: 2px;
	background-color: red;
	position: absolute;
	top: 0;
	left: 0;
}
