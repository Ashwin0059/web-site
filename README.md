t{
    --main-color:#6200ea;
    --accrent-color:#03dac6;
    --font-main:'Segoe UI',sans-serif;
}
body{
    font-family: var(--font-main);
    margin: 0;
    padding: 0;
    -box-sizing:border-box;
    background: linear-gradient(to right,#f0f0f0,#ffff);
    color: #333;
}
.main-header{
    background-color: var(--main-color);
    color:white;
    padding: 1rem;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,1);


}
.nav a{
    margin: 0 10px;
    color: white;
    text-decoration: none;
    transition: color 0.3s;
}
.nav a:hover{
    color: var(--accrent-color);
}
/* Hera section */
.hero{
    padding: 2rem;
    text-align: center;
    background-color: #fff;
    border-bottom: 2px solid#eee;
    }
.btn{
    padding: 0.5rem 1rem;
    background-color:var(--main-color) ;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: transform 0.3s;
}
.btn:hover{
    transform: scale(1.1);
}
/* features grids */
.features-grid{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
    gap: 1rem;
    padding: 2rem;
}
.feature{
    background-color: var(--accrent-color);
    padding: 1rem;
    border-radius: 8px;
    color: #fff;
    position: relative;
}
.feature::before{
    content: "⁎";
    position: absolute;
    top:10px;
    left: 10px;


}
/* form */
.form{
    margin: 2rem;
    display:flex ;
    flex-direction: column;
    gap: 0.5rem;
    max-width: 300px;
    margin-left: auto;
    margin-right: auto;
}
input[type="text"]{
    padding: 0.5rem;
    border: 1px solid#ccc;
    border-radius: 4px;
}
input:focus{
    border-color: var(--main-color);
    outline: none;
}
/* footer */
.footer{
    text-align: center;
    padding: 1rem;
    background-color: #eee;
    font-size: 0.9rem;
}
/* media */
@media(max-width:600px){
    .hero h2{
        font-size: 1.5rem;
    }
    .btn{
        width: 100%;
    }
}
