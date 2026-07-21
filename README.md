/* gobal */
*{
    margin: :0;
    padding:0;
    box-sizing:borde-box;
}
body{
    font-family: 'sego UI',sans-serif;
    background: #f4f6f8;
    color:#333 ;
    line-height: 1.6;
}
/* header an dnavigation */
header{
    background: #005f73;
    color: #FFF;
    padding: 20PX;
    text-align: center;
}
nav{
    background: #0a9396;
    display: flex;
    justify-content: center;
}
nav a{
    color: #FFF;
    padding: 15px 20px;
    text-decoration: none;
    transition: background 0.3;
}
nav a:hover{
    background-color: #94d2bd;
    color: #000;
}
/* main section */
.hero{
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(to right,#005f73,#0a9396);
    color: #FFF;
}
.content{
    padding: 40px 20px;
}
.content.box-wrap{
    display: flex;
    flex-wrap: wrap;
   


}
