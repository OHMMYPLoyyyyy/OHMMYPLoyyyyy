/* ======================== */
/* 
    Ignore the following styles. They are not important to achieve the effect.
    I'm only using them for looks (overall page background/font styles/centering content).
*/
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');

* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

body {
	font-family: 'Poppins', sans-serif;
	background-color: #1A1D24;
	display: grid;
	place-items: center;
	height: 100vh;
}

/* ======================== */
.icons {
	display: flex;
	column-gap: 25px;
}
.icon {
	display: inline-flex;
	width: 60px;
	height: 60px;
	text-decoration: none;
	font-size: 26px;
	color: #fff;
	border-radius: 50%;
	outline: 2px solid #fff;
	transition-property: outline-offset, outline-color, background-color;
	transition-duration: 0.25s;
}
.icon:hover {
	outline-offset: 4px;
}
.icon i {
	margin: auto;
}
.icon:hover i {
	animation: shake 0.25s;
}
.icon--instagram:hover {
	background-image: radial-gradient(
		circle at 30% 107%,
		#fdf497 0%,
		#fdf497 5%,
		#fd5949 45%,
		#d6249f 60%,
		#285aeb 90%
	);
	outline-color: #a02d76;
}
.icon--twitter:hover {
	background-color: #1da1f2;
	outline-color: #1da1f2;
}
.icon--linkedin:hover {
	background-color: #0077b5;
	outline-color: #0077b5;
}
.icon--github:hover {
	background-color: #2ea44f;
	outline-color: #2ea44f;
}
@keyframes shake {
	10% {
		transform: rotate(15deg);
	}
	20% {
		transform: rotate(-15deg);
	}
	30% {
		transform: rotate(15deg);
	}
	40% {
		transform: rotate(-15deg);
	}
}
