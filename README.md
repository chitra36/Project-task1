# Project-task1
Project/task1
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <Style>
        font{
           font-size: 30px;
        }
        Div{
            padding-left: 30px;
            padding-top: 12px;
        }
        .Container{
            display: flex;
           
            margin-left: 10px;
            width: 1400px;
        }
       
        .box{
            height: 55px;
            width: 711px;
            border-radius:8px;
        }
        .search{
            margin: 15px;
            height: 55px;
            width: 500px;
            border-radius:8px;
           
        }
        /* .img{
            height: 20px;
            gap: 1px;
        } */
        .box2{
            height: 197px;
            width: 711px;
            border-radius:8px;
        }
        .box3{
            padding-left: 60px;
            padding-top: 30px;
        }
        .checkbox{
            padding-top: 200px;
            margin: 20px;
        }
        .radio{
            padding-top: 200px;
            margin: 20px;
        }
        .switch {
  position: relative;
  display: inline-block;
  width: 60px;
  height: 34px;
}


    </Style>
</head>
<body>
    <Div class="Container">
 <div > 
    <div><p><font>Text Field *</font></p>
  <input type="Input" class="box" placeholder="Input Text"></input>
  <input type="search"    class="search" placeholder="Search" >
  <!-- <img   class="img"   src="https://cdn-icons-png.flaticon.com/128/54/54481.png" alt=""></img>--></input> 
  
</div>


  <div><p><font>Select Field </font></p> 
    <input type="Input" class="box" placeholder="Select"></input>
    <input type="checkbox" class="checkbox" name="checkbox" value="checkbox">
  <label for="checkbox"> checkbox</label><br>
</div>
  <div><p><font>Text Area </font></p> 
    <input type="Input" class="box2" placeholder="Text Area" ></input>
    <input type="radio" class="radio" name="radio" value="radio">
  <label for="radio">radio</label><br>
</div>
    <div >
     <p><font>Text Field with ad-ons *</font></p> 
        
        <input type="Input" class="box" placeholder="Input Text"></input>
        
    </div>
</div>
</Div>


</body>
</html>
