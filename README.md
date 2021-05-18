# orginalbyme*{
    margin: 0;
    padding: 0;
}

.container{
    
    background: url(rainbow.jpg);
    height: 100vh;
    background-size: 100% 100%;
    
}

.container .navbar{
    
    width: 100%;
    height: 100px;
    background: rgba(11,8,8,0.15);
    
    
}

.navbar ul{
    
    float: right;
    margin-right: 20px;
}

.navbar ul li{
    list-style: none;
    display: inline-block;
    margin: 0 15px;
    line-height: 100px;
    
    
}


.navbar ul li a{
    color: #F1D908 ;
    font-size: 20px;
    text-decoration: none;
    font-family:Berlin Sans FB ;
    
}

.navbar ul li a.active,
.navbar ul li a:hover{
    
    background: whitesmoke;
    border-radius: 2px;
}


.navbar .logo{
    display: inline-block;
    margin-left: 50px;
    margin-top: 20px;
    
    
}

.navbar .logo a{
    
    text-decoration: none;
    font-size: 50px;
    font-family: Berlin Sans FB;
    margin-left: 20px;
    color: #F1D908;
    
}

.container .center{
    position: absolute;
    top: 50%;
    left:50%;
    transform: translate(-50%,-50%);
    font-family: Berlin Sans FB;
    
}

.center h1{
    
    color: black;
    font-size: 70px;
    font-weight: bold;
    text-align: center;
}

.center h2{
    
    color: white;
    font-size: 50px;
    font-weight: bold;
    text-align: center;
    width:885px;
    margin-top: 10px;
}

.center .buttons{
    
    margin: 35px 280px;
    
}

.buttons button{
    
    height: 40px;
    width:150px;
    font-size: 20px;
    font-family:Berlin Sans FB ;
    font-weight: bold;
    color: #2f9dfc;
    background: transparent;
    border: solid 3px lavender;
    cursor: pointer;
    border-radius: 25px;
    
}


.buttons button:hover{
    background: aliceblue;
}


















