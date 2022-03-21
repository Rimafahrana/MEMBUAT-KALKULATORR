# MEMBUAT-KALKULATORR
*{
	margin: 0;
	padding: 0;
	font-family: 'montserrat',sans-serif;
	box-sizing: border-box;
}
body{
	display: flex;
	align-items: center;
	justify-content: center;
	min-height: 100vh;
	background: #091921;
}
.kalkulator{
	position: relative;
	display: grid;
}
.kalkulator .value{
	grid-column: span 4;
	height: 80px;
	width: 240px;
	text-align: right;
	border: none;
	outline: none;
	padding: 10px;
	font-size: 18px;
}
.kalkulator span{
	display: grid;
	width: 60px;
	height: 60px;
	color: #fff;
	background: #0c2835;
	place-items: center;
	border: 1px solid rgba(0, 0,0,.1)
}
.kalkulator span:active{
	background: #74ff3b;
	color: #111;
}
.kalkulator span:clear{
	grid-column: span 2;
	width: 120px;
	background: #ff3077;
}
.kalkulator span:plus{
	grid-row: span 2;
	height: 120px;
}
.kalkulator span.equal{
	background: #03b1ff;
