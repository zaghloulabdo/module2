*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
}
h1{
    font-size: 50px;
    text-align: center;
}

section{
    background-color: rgb(129, 128, 128);
    position: relative;
    border: 2px solid black;
    margin: 30px;
    height: 240px;
}

.row {
    width: 100%;
}

@media (min-width:992px) {
    .col-lg-4 , .col-lg-6 , .col-lg-12 {
        float: left; 
    }
    .col-lg-4{
        width: 33%;
    }
    .col-lg-6{
        width: 50%;
    }
    .col-lg-12{
        width: 100%;
    }
    
}

@media (min-width:768px) and (max-width:991px) {
    .col-md-4 , .col-md-6 , .col-md-12 {
        float: left; 
    }
    .col-md-4{
        width: 33%;
    }
    .col-md-6{
        width: 50%;
    }
    .col-md-12{
        width: 100%;
    }
   

    
}

@media (max-width:767) {
    .col-sm-4 , .col-sm-6 , .col-sm-12 {
        float: left; 
    }
    .col-sm-4{
        width: 33%;
    }
    .col-sm-6{
        width: 50%;
    }
    .col-sm-12{
        width: 100%;
    }
    
}



  

    



div>#sec1 >h2{
    position: absolute;
    right:0;
    margin-top: 0;
    border: 1px solid black;
    width: 150px;
    text-align: center;
    background-color: rgba(204, 41, 29, 0.671);
}
div>#sec2 >h2{
    position: absolute;
    right:0;
    margin-top: 0;
    border: 1px solid black;
    width: 150px;
    text-align: center;
    background-color: rgb(175, 64, 120);
}
div>#sec3>h2{
    position: absolute;
    right:0;
    margin-top: 0;
    border: 1px solid black;
    width: 150px;
    text-align: center;
    background-color: rgb(192, 191, 108);
}
p{
    margin-top: 40px;
    margin-left: 5px;
}
