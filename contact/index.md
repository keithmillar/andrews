---
layout: default
---

<!-- a helper script for vaidating the form-->
<script language="JavaScript" src="scripts/gen_validatorv31.js" type="text/javascript"></script>
</head>	
</head>

<body>
<h1>Contact us</h1>
<form method="POST" name="contactform" action="contact-form-handler.php"> 
<p>
<label for='name'>Your Name:</label> <br>
<input type="text" name="name">
</p>
<p>
<label for='email'>Email Address:</label> <br>
<input type="text" name="email"> <br>
</p>
<p>
<label for='message'>Message:</label> <br>
<textarea name="message"></textarea>
</p>
<p>
<input type="submit" value="Submit"><br>
</form></p>

<script language="JavaScript">
// Code for validating the form
// Visit http://www.javascript-coder.com/html-form/javascript-form-validation.phtml
// for details
var frmvalidator  = new Validator("contactform");
frmvalidator.addValidation("name","req","Please provide your name"); 
frmvalidator.addValidation("email","req","Please provide your email"); 
frmvalidator.addValidation("email","email","Please enter a valid email address"); 
</script>


Ciaran Andrews Bsc Hons MRICS MCIAT 
 
RICS Accredited Building Conservation Surveyor  
Chartered Building Surveyor  
Chartered Architectural Technologist  
Assigned Certifier (ROI)  

CA Architectural Address:  

117 Donaghadee Road  
Groomsport  
Orlock  
Co. Down  
BT19 6LT  

E-mail: 	<ciaran@caarchitectural.com>  
Telephone: 	07803 166653  
Web Site:	[www.caarchitectural.com](http://www.caarchitectural.com)  
