<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&family=Ubuntu:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&family=Roboto&family=Ubuntu:wght@300&display=swap" rel="stylesheet">
    <title>Простые вещи из бумаги</title>
</head>
    <style>
        body {
    margin: 0;
    box-sizing: border-box;
}
        
a { 
    text-decoration: none;
}
        
header {
    display:flex;
}
        
.conteiner-header{
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    padding: 30px 0px 30px 100px;
    border-bottom:#b1afaf solid 1px;
}
        
.info{
    display: flex;
    width: 100%;
    justify-content: space-evenly;
}

.info>a{
    font-family: "Roboto", sans-serif;
    color: #85859B;
    text-decoration: none;
}

.logo{
    display: flex;
    width: 100%;

}

div > .logo-part1 {
    border: 1px solid black;
    width: 17px;
    height: 17px;
    border-radius: 50%;
    margin-right: 5px;

}

div > .logo-text {
    color: #333;
    font-family: "Ubuntu", sans-serif;
    font-weight: 300;
    font-style: normal;
    font-size: 20px;
    line-height: 23px;
    margin-right: 5px;
    }
      
div > .logo-part2 {
    border: 1px solid black;
    width: 32px;
    height: 17px;
    border-radius: 11px;
    margin-right: 5px;
}
div > .logo-part3 {
    border: 1px solid black;
    width: 17px;
    height: 17px;
    border-radius: 50%;
}

a > .text1, a > .text2, a > .text3, a > .text4 {
        font-family: "Roboto", sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: 20px;
        line-height: 23,5px;
        margin-right: 60px;
        text-decoration: none;
        color: #4C5866;
}

.str1 {
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
}
.str1 > h1 {
    color: #4C5866;
    font-size: 60px;
    margin-left: 165px;
    margin-top: 130px;
    line-height: 60px;
}
.str1 > p {
    color: #85859B;
    margin-top: 30px;
    margin-left: 165px;
    font-size: 18px;
    line-height: 27px;

}
.katalog {
    display: grid;
    border: 1px solid #7875FE;
    width: 255px;
    height: 70px;
    margin-left: 165px;
    margin-top: 30px;
}
.katalog > a {
    color: #7875FE;
    margin: auto;
    text-decoration: none;
}
.str1 > .str1-img {
    position: absolute;
    right: 165px;
    top: 15%;
}
.str2 {
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
    width: 100%;
    height: 973px;
    background: #d7d7d7;
    position: absolute;
    top:73%;
    box-sizing: border-box;
}
.line {
    display:flex;
    position: absolute;
}
.line1 {
    margin-top: 50px;
    margin-left: 165px;
    width: 350px;
    height: 1px;
    opacity: 0.5;
}
.img-head {
    display: flex;
    margin-left: 165px;
    margin-top: 90px;
}
.text-v1 > h1 {
    color: #666;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    margin-left:60px;
}
.text-v1 > p {
    margin-left:60px;
    font-size: 18px;
    line-height: 27px;
    color: #85859B;
}
.line2 {
    margin-top: 50px;
    margin-left: 80px;
    width: 350px;
    height: 1px;
    opacity: 0.5;
}
.img-v2 {
    margin-left: 80px;
}
.text-v2 > h1 {
    color: #666;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    margin-left:60px;
}
.text-v2 > p {
    color:#85859B;
    margin-left:60px;
    font-size: 18px;
    line-height: 27px;
}
.line3 {
    margin-top: 50px;
    margin-left: 80px;
    width: 350px;
    height: 1px;
    opacity: 0.5;
}
.img-v3 {
    margin-left: 80px;
}
.text-v3 > h1 {
    color: #666;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    margin-left:60px;
}
.text-v3 > p {
    color:#85859B;
    margin-left:60px;
    font-size: 18px;
    line-height: 27px;
}
.content {
    display: flex;
    margin-left: 165px;
}
.img-content {
    margin-top: 90px;
}
.text-content {
    margin-top: 149px;
    margin-left: 30px;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
}
.text-content > h1 {
    color: #666;
    font-size:40px;
    line-height: 40px;
}
.text-content > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}
.product {
    background: #fff;;
    width: 100%;
    height: 645px;
    position: absolute;
    top: 175%;
}
.product {
    display: flex;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
}
.content-product1 {
    margin-left: 165px;
    margin-top: 90px;
}
.text-cp1 > h1 {
    font-size: 30px;
    line-height: 35px;
}
.text-cp1 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}
.text-bottom {
    display: grid;
    width: 140px;
    height: 40px;
    display:flex;
    color: #7875FE;
    font-size: 20px;
    line-height: 23.5px;
}
.text-bottom > a {
    margin-right: 5px;
    margin: auto;
    color:#7875FE
}
.text-bottom > img {
    margin: auto;
}
.content-product2 {
    margin-top: 90px;
    margin-left: 80px;
}
.text-cp2 > h1 {
    font-size: 30px;
    line-height: 35px;
}
.text-cp2 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}
.content-product3 {
    margin-top: 90px;
    margin-left: 80px;
}
.text-cp3 > h1 {
    font-size: 30px;
    line-height: 35px;
}
.text-cp3 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}
.content-product4 {
    margin-top: 90px;
    margin-left: 80px;
}
.text-cp4 > h1 {
    font-size: 30px;
    line-height: 35px;
}
.text-cp4 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}
.portner {
    display: flex;
    background: #d7d7d7;
    width: 100%;
    height: 315px;
    position: absolute;
    top:250%;
}
.portner1 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 165px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;
}
.portner2 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 80px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;
}
.portner3 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 80px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;
}
.portner4 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 80px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;
}
footer > .content-end {
    display: flex;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
    width: 100%;
    height: 500px;
    position: absolute;
    top: 283%;
}
.text-content {
    margin-top: 90px;
    margin-left: 165px;
}
.content-end > h1 {
    font-size: 40px;
    line-height: 40px;
}
.content-end > p {
    font-size: 18px;
    line-height: 30.5px;
}
.buy {
    display: grid;
    border: 1px solid #7875FE;
    width: 255px;
    height: 70px;
    justify-content: center;
    align-items: center;
    margin-top: 30px;
}
.buy > a {
    font-size: 20px;
    line-height: 23.5px;
    color: #7875FE;
}
.img-tc {
    position: absolute;
    left: 45%;
    top: 15%;
}
.footer {
    background: #4C5866;
    width: 100%;
    height: 80px;
    position: absolute;
    top: 336%;
}
.logof {
    display: flex;
    padding-left:165px;
    padding-top: 29px;
}
.logof > .logo-part1 {
    border: 1px solid #fff;
    width: 17px;
    height: 17px;
    border-radius: 50%;
    margin-right: 5px;

}
.logof > .logo-text {
    color: #fff;
    font-family: "Ubuntu", sans-serif;
    font-weight: 300;
    font-style: normal;
    font-size: 20px;
    line-height: 23px;
    margin-right: 5px;
    }
      
.logof > .logo-part2 {
    border: 1px solid #fff;
    width: 32px;
    height: 17px;
    border-radius: 11px;
    margin-right: 5px;
}
.logof > .logo-part3 {
    border: 1px solid #fff;
    width: 17px;
    height: 17px;
    border-radius: 50%;
}
.contact {
    position: absolute;
    top: 35%;
    left: 78%;
    
}
.contact > img {
    margin-right: 30px;
}
.katalog:hover  > a {
    color: #fff;
}
.katalog:hover {
    background: #7875FE;
    color: #fff;
}
a:focus .katalog > p {
    color: #7875FE;
}
a:focus .katalog {
    background: #DAD9FB;
}
a:active .katalog > p {
    color: #fff;
}
a:active .katalog {
    background: #4946B4;
    transition: 1s;
}
.info>a:hover{
    color: #7875FE;
}
.prod:hover p {
    color: #4946B4;
}
.prod:focus p {
    background: #DAD9FB;
    color: #7875FE;
}
.prod:active p {
    color: #4946B4;
    transition: 1s;
}
.text1:hover > a {
    color: #7875FE;
} 
a:focus .text1 {
    background: #DAD9FB;
    color: #4C5866; 
}
.text2:hover > a {
    color: #7875FE;
} 
.text3:hover > a {
    color: #7875FE;
} 
.text4:hover > a {
    color: #7875FE;
} 
a:focus .text1 {
    background: #DAD9FB;
    color: #4C5866;
}
a:focus .text2 {
    background: #DAD9FB;
    color: #4C5866;
}
a:focus .text3 {
    background: #DAD9FB;
    color: #4C5866;
}
a:focus .text4 {
    background: #DAD9FB;
    color: #4C5866;
}
a:active .text1 {
    color: #4946B4;
    transition: 1s;
}
a:active .text2 {
    color: #4946B4;
    transition: 1s;
}
a:active .text3 {
    color: #4946B4;
    transition: 1s;
}
a:active .text4 {
    color: #4946B4;
    transition: 1s;
}
.text-bottom:hover > a {
    color: #fff;
}
.text-bottom:hover {
    background: #4946B4;
    color: #fff;
}
a:focus .text-bottom > p {
    color: #7875FE;
}
a:focus .text-bottom {
    background: #DAD9FB;
}
a:active .text-bottom > p {
    color: #fff;
}
a:active .text-bottom {
    background: #4946B4;
    transition: 1s;
}
.buy:hover  > a {
    color: #fff;
}
.buy:hover {
    background: #7875FE;
}
a:focus .buy > p {
    color: #7875FE;
}
a:focus .buy {
    background: #DAD9FB;
}
a:active .buy > p {
    color: #fff;
}
a:active .buy {
    background: #4946B4;
    transition: 1s;
}


@media (max-width:320px)  {

/*Header*/

header {
    display:flex;
}

/*conteiner-header*/

.conteiner-header{
    display: flex;
    width: 320px;
    height: 105px;
    justify-content: space-between;
    align-items: center;
    padding: 0px 0px 0px 0px;
    border-bottom:#cacaca solid 1px;
}

.cap{
    display: flex;
    width: 100%;
    height: 79px;
}

.menu{
    display: flex;
    width: 320px;
    height: 105px;
    justify-content: space-between;
    align-items: center;
    padding: 0px 0px 0px 0px;
    border-bottom:#cacaca solid 1px;
}

/*logo*/

.logo{
    display: flex;
    width: 140px;
    height: 22px;
    padding: 0px 0px 0px 90px;
}

div > .logo-part1 {
    border: 1px solid black;
    width: 17px;
    height: 17px;
    border-radius: 50%;
    margin-right: 5px;
}

div > .logo-text {
    color: #333;
    font-family: "Ubuntu", sans-serif;
    font-weight: 300;
    font-style: normal;
    font-size: 20px;
    line-height: 23px;
    margin-right: 5px;
}
      
div > .logo-part2 {
    border: 1px solid black;
    width: 32px;
    height: 17px;
    border-radius: 11px;
    margin-right: 5px;
}

div > .logo-part3 {
    border: 1px solid black;
    width: 17px;
    height: 17px;
    border-radius: 50%;
}

/*info*/

.info{
    display: flex;
    width: 100%;
    justify-content: space-evenly;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.info>a{
    font-family: "Roboto", sans-serif;
    color: #85859B;
    text-decoration: none;
}

.info>a:hover{
    color: #7875FE;
}

/*main*/

/*str1*/

.str1 {
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
    
    width:0px;
    height:0px;
    overflow-x: auto;
}

.str1 > h1 {
    color: #4C5866;
    font-size: 60px;
    margin-left: 165px;
    margin-top: 130px;
    line-height: 60px;
}

.str1 > p {
    color: #85859B;
    margin-top: 30px;
    margin-left: 165px;
    font-size: 18px;
    line-height: 27px;

}

/*katalog*/

.katalog {
    display: grid;
    border: 1px solid #7875FE;
    width: 255px;
    height: 70px;
    margin-left: 165px;
    margin-top: 30px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.katalog > a {
    color: #7875FE;
    margin: auto;
    text-decoration: none;
}

.katalog:hover  > a {
    color: #fff;
}

.katalog:hover {
    background: #7875FE;
    color: #fff;
}

a:focus .katalog > p {
    color: #7875FE;
}

a:focus .katalog {
    background: #DAD9FB;
}

a:active .katalog > p {
    color: #fff;
}

a:active .katalog {
    background: #4946B4;
    transition: 1s;
}

/*str1-img*/

.str1 > .str1-img {
    position: absolute;
    right: 165px;
    top: 15%;

    width:0px;
    height:0px;
    overflow-x: auto;
}

/*str2*/

.str2 {
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
    width: 100%;
    height: 973px;
    background: #d7d7d7;
    position: absolute;
    top:73%;
    box-sizing: border-box;

    width:0px;
    height:0px;
    overflow-x: auto;
}

/*line*/

.line {
    display:flex;
    position: absolute;
    
    width:0px;
    height:0px;
    overflow-x: auto;
}

.line1 {
    margin-top: 50px;
    margin-left: 165px;
    width: 350px;
    height: 1px;
    opacity: 0.5;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.line2 {
    margin-top: 50px;
    margin-left: 80px;
    width: 350px;
    height: 1px;
    opacity: 0.5;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.line3 {
    margin-top: 50px;
    margin-left: 80px;
    width: 350px;
    height: 1px;
    opacity: 0.5;

    width:0px;
    height:0px;
    overflow-x: auto;
}

/*img-head*/

.img-head {
    display: flex;
    margin-left: 165px;
    margin-top: 90px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

/*1*/

.text-v1 > h1 {
    color: #666;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    margin-left:60px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-v1 > p {
    margin-left:60px;
    font-size: 18px;
    line-height: 27px;
    color: #85859B;
}

/*2*/

.img-v2 {
    margin-left: 80px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-v2 > h1 {
    color: #666;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    margin-left:60px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-v2 > p {
    color:#85859B;
    margin-left:60px;
    font-size: 18px;
    line-height: 27px;
}

/*3*/

.img-v3 {
    margin-left: 80px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-v3 > h1 {
    color: #666;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    margin-left:60px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-v3 > p {
    color:#85859B;
    margin-left:60px;
    font-size: 18px;
    line-height: 27px;
}

/*content*/

.content {
    display: flex;
    margin-left: 165px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.img-content {
    margin-top: 90px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-content {
    margin-top: 149px;
    margin-left: 30px;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-content > h1 {
    color: #666;
    font-size:40px;
    line-height: 40px;
}

.text-content > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}

.text-content {
    margin-top: 90px;
    margin-left: 165px;
}

/*str3*/

.product {
    background: #fff;;
    width: 100%;
    height: 645px;
    position: absolute;
    top: 175%;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.product {
    display: flex;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
}

/*text-bottom*/

.text-bottom {
    display: grid;
    width: 140px;
    height: 40px;
    display:flex;
    color: #7875FE;
    font-size: 20px;
    line-height: 23.5px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-bottom > a {
    margin-right: 5px;
    margin: auto;
    color:#7875FE
}

.text-bottom > img {
    margin: auto;
}

.text-bottom:hover > a {
    color: #fff;
}

.text-bottom:hover {
    background: #4946B4;
    color: #fff;
}

a:focus .text-bottom > p {
    color: #7875FE;
}

a:focus .text-bottom {
    background: #DAD9FB;
}

a:active .text-bottom > p {
    color: #fff;
}

a:active .text-bottom {
    background: #4946B4;
    transition: 1s;
}

/*content-product1*/

.content-product1 {
    margin-left: 165px;
    margin-top: 90px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp1 > h1 {
    font-size: 30px;
    line-height: 35px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp1 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}

/*content-product2*/

.content-product2 {
    margin-top: 90px;
    margin-left: 80px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp2 > h1 {
    font-size: 30px;
    line-height: 35px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp2 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}

/*content-product3*/

.content-product3 {
    margin-top: 90px;
    margin-left: 80px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp3 > h1 {
    font-size: 30px;
    line-height: 35px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp3 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}

/*content-product4*/

.content-product4 {
    margin-top: 90px;
    margin-left: 80px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp4 > h1 {
    font-size: 30px;
    line-height: 35px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.text-cp4 > p {
    color: #85859B;
    font-size: 18px;
    line-height: 30.5px;
}

/*str4*/

/*porter*/

.portner {
    display: flex;
    background: #d7d7d7;
    width: 100%;
    height: 315px;
    position: absolute;
    top:250%;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.portner1 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 165px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.portner2 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 80px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.portner3 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 80px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.portner4 {
    display: grid;
    border: 1px solid #c0c0c0;
    width: 255px;
    height: 135px;
    margin-left: 80px;
    margin-top: 90px;
    justify-content: center;
    align-items: center;

    width:0px;
    height:0px;
    overflow-x: auto;
}

/*content-end*/

footer > .content-end {
    display: flex;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
    width: 100%;
    height: 500px;
    position: absolute;
    top: 283%;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.content-end > h1 {
    font-size: 40px;
    line-height: 40px;
}

.content-end > p {
    font-size: 18px;
    line-height: 30.5px;
}

/*buy*/

.buy {
    display: grid;
    border: 1px solid #7875FE;
    width: 255px;
    height: 70px;
    justify-content: center;
    align-items: center;
    margin-top: 30px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.buy > a {
    font-size: 20px;
    line-height: 23.5px;
    color: #7875FE;
}

.buy:hover  > a {
    color: #fff;
}

.buy:hover {
    background: #7875FE;
}

a:focus .buy > p {
    color: #7875FE;
}

a:focus .buy {
    background: #DAD9FB;
}

a:active .buy > p {
    color: #fff;
}

a:active .buy {
    background: #4946B4;
    transition: 1s;
}

/*img-tc*/

.img-tc {
    position: absolute;
    left: 45%;
    top: 15%;

    width:0px;
    height:0px;
    overflow-x: auto;
}

/*footer*/

.footer {
    background: #4C5866;
    width: 100%;
    height: 80px;
    position: absolute;
    top: 336%;

    width:0px;
    height:0px;
    overflow-x: auto;
}

/*logof*/

.logof {
    display: flex;
    padding-left:165px;
    padding-top: 29px;

    width:0px;
    height:0px;
    overflow-x: auto;
}

.logof > .logo-part1 {
    border: 1px solid #fff;
    width: 17px;
    height: 17px;
    border-radius: 50%;
    margin-right: 5px;

}

.logof > .logo-text {
    color: #fff;
    font-family: "Ubuntu", sans-serif;
    font-weight: 300;
    font-style: normal;
    font-size: 20px;
    line-height: 23px;
    margin-right: 5px;
}
      
.logof > .logo-part2 {
    border: 1px solid #fff;
    width: 32px;
    height: 17px;
    border-radius: 11px;
    margin-right: 5px;
}

.logof > .logo-part3 {
    border: 1px solid #fff;
    width: 17px;
    height: 17px;
    border-radius: 50%;
}

/*contact*/

.contact {
    position: absolute;
    top: 35%;
    left: 78%;
    
    width:0px;
    height:0px;
    overflow-x: auto;
}
.contact > img {
    margin-right: 30px;
}

}
    </style>
<body>
    <header>
        <div class = "conteiner-header">
            <div class="cap">
                <div class="menu">    
                    <div class = "logo">
                        <div class = "logo-part1"></div>
                        <div class = "logo-text">simple</div>
                        <div class = "logo-part2"></div>
                        <div class = "logo-part3"></div>
                    </div>
                </div>
            </div>    
            <div class = "info">
                <a href = "#">Продукция</a>
                <a href = "#">Mатериалы</a>
                <a href = "#">О нас</a>
                <a href = "#">Контакты</a>
                <div class = "icon1"><img  src = "1.svg" width="24" height="24"></div>
                <div class = "icon2"><img  src = "2.svg" width="24" height="24"></div>
            </div>
        </div>
    </header>
    <main>
        <div class = "str1">
            <h1>Простые вещи.<br>Из бумаги</h1>
            <p>Бума́га (предположительно от итал. bombagia,<br>первоисточником же считается иранский) — <br>волокнистый материал с минеральными<br> добавками.</p>
            <div class = "katalog">
                <a href="#" style= "text-decoration: none;">Каталог</a>
            </div>
            <div class = "str1-img">
                <img src = "фото1.png">
            </div>
        </div>
        <div class = "str2">
            <div class = "line">
                <div class = "line1"><hr noshade></div>
                <div class = "line2"><hr noshade></div>
                <div class = "line3"><hr noshade></div>
            </div>
            <div class = img-head>
                <div class = "img-v1">
                    <img src = "фото2.png" width="160" height="118">
                </div>
                <div class = "text-v1">
                    <h1>V.1</h1>
                    <p>Результат вашего<br>обучения</p>
                </div>
                <div class = "img-v2">
                    <img src = "фото3.png" width="160" height="118">
                </div>
                <div class = "text-v2">
                    <h1>V.2</h1>
                    <p>Результат вашего<br>обучения</p>
                </div>
                <div class = "img-v3">
                    <img src = "фото4.png" width="160" height="118">
                </div>
                <div class = "text-v3">
                    <h1>V.3</h1>
                    <p>Результат вашего<br>обучения</p>
                </div>
            </div>
            <div class = "content">
                <div class = "img-content">
                    <img src = "фото5.png">
                </div>
                <div class = "text-content">
                    <h1>Максимальная<br>белизна</h1>
                    <p>Для повышения белизны, гладкости<br>и мягкости в состав бумажной массы<br>вводят белые минеральные вещества:<br>мел, тальк, каолин и др. Эта операция<br>называется наполнением.
                    </p>
                    <p>Отлив бумажного листа осуществляют<br>на бумагоделательной машине,<br>важнейшей частью которой является<br>непрерывно движущаяся (как<br>транспортер) металлическая или<br>капроновая сетка.</p>
                </div>
            </div>
        </div>
        <div class = "str3">
            <div class = "product">
                <div class = "content-product1">
                    <div class = "img-cp1">
                        <img src = "фото6.png">
                    </div>
                    <div class = "text-cp1">
                        <h1>Упаковка</h1>
                        <p>Сделано из крафт-бумаги или<br>плотного картона.Упаковки<br>имеют различные формы<br>и расцветки, изготовим<br>форму под заказ.</p>
                            <div class = "text-bottom">
                                <a href="#" style= "text-decoration: none;">Подробнее</a>
                                    <img src = "3.svg" width="20" height="15">
                            </div>
                    </div>
                </div>
                <div class = "content-product2">
                        <div class = "img-cp2">
                            <img src = "фото7.png">
                        </div>
                        <div class = "text-cp2">
                            <h1>Пакеты</h1>
                            <p>С прямоугольным дном.<br>От 10 см до 60 см по высоте.<br>Материалы: картон,<br>крафт-бумага. Различные<br>расцветки и дизайн.</p>
                            <a href = "#">   
                                <div class = "text-bottom">
                                    <a href="#" style= "text-decoration: none;">Подробнее</a>
                                        <img src = "3.svg" width="20" height="15">
                                </div>
                            </a>
                        </div>
                </div>
                <div class = "content-product3">
                    <div class = "img-cp3">
                        <img src = "фото8.png">
                    </div>
                    <div class = "text-cp3">
                        <h1>Кейсы</h1>
                        <p>Подойдет для документов<br>и других бумаг. Различные<br>расцветки, размеры<br>и плотность. Материал:<br>прессованная бумага.</p>
                        <a href = "#">  
                            <div class = "text-bottom">
                                <a href="#" style= "text-decoration: none;">Подробнее</a>
                                    <img src = "3.svg" width="20" height="15">
                            </div>
                        </a>
                    </div>
                </div>
                <div class = "content-product4">
                    <div class = "img-cp4">
                        <img src = "фото9.png">
                    </div>
                    <div class = "text-cp4">
                        <h1>Другие изделия</h1>
                        <p>Нестандартные упаковки,<br>кейсы и другие изделия<br>различных размеров<br>и конфигураций. Изготовим<br>в кратчайшие сроки.</p>
                        <a href = "#">
                            <div class = "text-bottom">
                                <a href="#" style= "text-decoration: none;">Подробнее</a>
                                    <img src = "3.svg" width="20" height="15">
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div class = "str4">
            <div class = "portner">
                <div class = "portner1"> 
                    <img src="фото10.png">
                </div>
                <div class = "portner2">
                    <img src = "фото11.png">
                </div>
                <div class = "portner3">
                    <img src = "фото12.png">
                </div>
                <div class = "portner4">
                    <img src = "фото13.png">
                </div>
            </div>
        </div>
        </div>
    </main>
    <footer>
        <div class = "content-end">
            <div class = "text-content">
                <h1>Simple скетчбук</h1>
                <p>80 листов, твердая обложка, бумага<br>Fabriano 200 г/м2. Подойдет и для графики и для<br>акварели. Для самых<br>смелых творческих замыслов!</p>
                <div class = "buy">
                                <a href="#" style= "text-decoration: none;">Купить</a>     
                            </div>
                <div class = "img-tc">
                    <img src = "фото14.png"  width="730" height="410">
                </div>
            </div>
        </div>
        <div class = "footer">
            <div class = "logof">
                <div class = "logo-part1"></div>
                <div class = "logo-text">simple</div>
                <div class = "logo-part2"></div>
                <div class = "logo-part3"></div>
            </div>
            <div class = "contact">
                <img src="фото15.png">
                <img src="4.svg">
                <img src="5.svg">
                <img src="6.svg">
            </div>
        </div>
    </footer>
</body>
</html>
