/* Form Styles */
form {
	background-color: #b0b0bd;
	padding: 20px 30px;
}

input, 
select {
	font-family: Verdana, Geneva, Tahoma, sans-serif;
	font-size: 100%;
}

input[type="email"],
input[type="password"],
input[type="text"],
input[type="number"],
input[type="tel"],
select
 {
	width: 100%;
	display: block;
	box-sizing: border-box;
	padding: 0 20px;
	height: 40px;
	font-family: Verdana, Geneva, Tahoma, sans-serif;
	font-size: 100%;
	margin-bottom: 15px;
	border: 1px solid #CDCDCD;
}
input[type="email"]:focus,
input[type="password"]:focus,
input[type="text"]:focus,
input[type="number"]:focus,
input[type="tel"]:focus 
{
	
	outline: none;
	border: 1px solid  #869960;
	box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.46) inset;
}
input[type="submit"] {
	width: 100%;
	display: block;
	box-sizing: border-box;
	background-color: #869960;
	color: #FFF;
	padding: 10 px 0;
	border: 1px solid #798A56;
	border-radius: 3px;
	margin-bottom: 10px;
}
input[type="submit"]:hover,
input[type="submit"]:focus {
	 border: 1px solid #535E3B;
	 background-color: #798A56;

}
.hidden-label {
	position: absolute;
	height: 0;
	width: 0;
	overflow:hidden;
	visibility: hidden;
}
.checkbox-text {
	font-size: 85%;
	color: #777;
}
