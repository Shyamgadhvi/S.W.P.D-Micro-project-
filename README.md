HTML CODE:-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> 
    <link rel="stylesheet" href="style.css">
</head>
<body>
  <div id="container">
   
    <div class="mybox" id="morroco">
          
      <div class="morco"></div>
      <img id="morco" src="image/Morocco_star.png" height="75px" width="75px" alt="">
      
       <h3 class="name">1.morroco</h3>

      </div>
    
 
      <div class="mybox" id="gabon">
          
        <div class="upper"></div>
        <div class="middle"></div>
         <div class="down"></div>
          <h3 class="name">2.gabon</h3>
         </div>
    
    <div class="mybox" id="martius">
     <div class="upper"></div>
     <div class="middle"></div>
     <div class="center"></div>
     <div class="down"></div>
      <h3 class="name">3.mauritius</h3>
    </div>
    
    <div class="mybox" id="salvador">
      <div class="upper"></div>
      <div class="center"> <img src="image/El Salvador_Coat_of_arms.png" height="70px"
        width="70px"></div>
      <div class="down"></div>
       
       <h3 class="name">4.EL Salvador</h3>
      </div>
 

     <div class="mybox" id="malta">
      <div class="rhs">
      </div>
      <img src="image/Malta_Coat_of_arm.png" height="50px" width="50px">
      <div class="lhs"></div>
      <h3 class="name">5.Malta</h3>
     </div>


     <div class="mybox" id="serbia">
      <div class="upper"></div>
      <div class="middle"></div>
      <div class="down"></div>
      <img id="Serbia" src="image/Serbia_Coat_of_arms.png" height="150px" width="75px" alt="">
      <h3 class="name">6.Serbia</h3>
     </div>


     <div class="mybox" id="san">
      <div class="rhs"></div>
      <div class="lhs"></div>
      <img id="marino" src="image/San Marino_crown.png"  height="130px" width="110px">
      <h3 class="name">7.San-Marino</h3>
      </div>


      <div class="mybox" id="ghana">
        <div class="top"></div>
        <div class="middle"></div>
        <div class="down"></div>
        <img id="ghanaimg" src="image/ghana_star.png" height="70px" width="70px" alt="">
        <h3 class="name">8.Ghana</h3>
      </div>

      
      <div class="mybox" id="greenland">
        <div class="upper"></div> 
        <div class="middle"></div>
        <div class="center"></div>
        <div class="down"></div>
        <h3 class="name">9.greenland</h3>
      </div>

      
      
  </div>
</body>
</html>

CSS:-
CSS:-
#container{
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  background-color: #d3d3d3;

}

.mybox{
  width: 350px;
  height: 350px;
  border: 1px solid black;
  margin: 5px;
  display:flex;
  align-items: center;
  justify-content: center;
  flex-direction:column;
}

.name{
  position: absolute;
  margin-top: 300px;

}

/*MORROCO*/


#morroco>div{
  display: flex;
  width: 300px;
  height: 200px;
}
#morroco>.morco{
background-color: #C1272D;
}


#morco{
  position: absolute;

}

/*GABON*/

#gabon>div{

width:300px;
height:65px;

}
#gabon>.upper{
background-color:#009E60;
}

#gabon>.middle{
background-color:#FCD116;
}

#gabon>.down{
background-color:#4664B2;
}

/*MARTIUS*/


#martius>div{
width:300px;
height:50px;
}

#martius>.upper{
background-color:#EA2839;
}
#martius>.middle{
background-color:#1A206D;
}
#martius>.center{
background-color:#FFD500;
}
#martius>.down{
background-color:#00A551;
}


/*EL SALVADOR*/



#salvador>div{
width:300px;
height:67px;

}
#salvador>.upper{
 background-color:#0047AB;
}
#salvador>.center{

background-color:#FFFFFF;
display: flex;
justify-content: center;
align-items: center;
}
#salvador>.down{
 background-color:#0047AB;
}
.img{
  height: 70px;
  width: 70px;
}
#salvador>.name{
  display: contents;
}

/*MALTA*/

#malta{
  flex-direction: row;
}

#malta>div{
  width: 150px;
  height: 210px;
  
}
#malta>.rhs{
background-color:#FFFFFF;

}
#malta>.lhs{
background-color:#C01B22;
}
#malta img{
position: absolute;
margin-top: -150px; 
margin-left: -240px;
}

/*SERBIA*/

#serbia>div{
  width: 300px;
  height: 67px;
}
#serbia>.upper{
  background-color:#C6363c;
}
#serbia>.middle{
  background-color:#0C4076;
  display: flex;
  align-items: center;
  justify-content: center;   
}
#serbia>.down{
  background-color:#FFFFFF;
}
#Serbia{
  position: absolute;
  margin-left: -150px;
  margin-bottom: 16px;
}


/*SAN MARIO*/

#san>div{
  width: 300px;
  height: 100px;
  display:flex;
  flex-direction:column;
  position: relative;
  flex-wrap:wrap-reverse;
}
#san>.rhs{
background-color:#FFFFFF;
}
#san>.lhs{
background-color:#62B5E5;
}
#marino{
  position: absolute;
  margin-bottom:20px;
}

/*GHANA*/

#ghana>div{
  width: 300px;
  height: 70px;
}
#ghana>.top{
  background-color:#EF3340;
}
#ghana>.middle{
  background-color:#FFD100;
}
#ghana>.down{
  background-color:#009739;
}
#ghanaimg{
  position: absolute;
  
}

/*GREENLAND*/

#greenland>div{
  width: 300px;
  height:90px;
}
#greenland>.upper{
  background-color:#FFFFFF;
}
#greenland>.middle{
  width: 70px;
  height: 35px;
  background-color: #D00C33;
  border-top-left-radius: 35px;
  border-top-right-radius: 35px;
  position: absolute;
  margin-top: -35px;
  margin-left: -100px;
  
}
#greenland>.center{
  width: 70px;
  height: 35px;
  background-color: #FFFFFF;
  border-bottom-left-radius: 35px;
  border-bottom-right-radius: 35px;
  position: absolute;
  margin-bottom: -35px;
  margin-left: -100px;
  
}
#greenland>.down{
  background-color: #D00C33;
}
