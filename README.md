<!DOCTYPE html>
<html>
<head>
   <title>ZAHIA</title>
   <link rel="stylesheet" type="text/css" href="mama.css">
   <meta name="viewport" content="width=device-width , initial-scale=1.0">
   <link href="https://fonts.googleapis.com/css?family=Aref+Ruqaa&display=swap" rel="stylesheet">
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



</head>





<body>

    <header>
           <nav>
                 <div class="row clearfix">
               	  <img src="abstract-vector-human-1.png" class="logo">

               	 <ul class="main-nav animated slideInDown" id="check-class">
               	 	<li><a href="#"> الرئيسة  </a></li>
               	 	<li><a href="#"> الحلويات  </a></li>
               	 	<li><a href="#">سلطات     </a></li>
               	 	<li><a href="#">أطباق      </a></li>

               		
               	 </ul>

               	 <a href="#" class="mobile-icon" id="check-class" onclick="slideshow()"><i class="fa fa-bars" aria-hidden="true"></i></a>
               	
               </div>

           </nav>

           <div class="main-contain">


           <h1>مرحبا في  <span class="colorchange">مطبخ زهية</span>.<br>
                مطبخ  مختلف محبي الطبخ الجزائري</h1>
                <a href="#" class="btn btn-full"> click to order</a>
                <a href="#" class="btn btn-nav"> show more</a>
            </div>    



    </header>
    <script type="text/javascript">
    	function slideshow(){ 
    		var x = document . getElementById('check-class');
    		if (x.style.display  === "none"){
    		x.style.display  ="block" }else{ x.style.display="none"}

    	}
    </script>

</body>

</html>
