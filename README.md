# TryalDou
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700;800&display=swap');


*{
    margin: 0;
    padding: 0;
}


body {
    font-family: 'Poppins', sans-serif;
    font-weight: 400;
    color: #fff;
    font-size: 16px;
}

a {
    text-decoration: none;
}

img{
    max-width: 60%;
}

.wrapper {
    /*background: linear-gradient(326deg, rgba(166,36,154,1) 10%, rgba(144,40,208,1) 51%, rgba(91,99,255,1) 78%, rgba(0,212,255,1) 100%);*/
    /* background: linear-gradient(158deg, rgba(0,0,0,1) 22%, rgba(44,30,10,1) 65%, rgba(91,61,21,1) 83%, rgba(108,80,31,1) 94%, rgba(143,115,35,1) 100%); */
    background-image: linear-gradient( 179deg,  rgba(0,0,0,1) 9.2%, rgba(127,16,16,1) 103.9% );
    width: 100%;
    height: auto;
}

.container {
    width: 1000px;
    margin: 0 auto;
}

header {
    padding: 50px 0;
}

header .logo,
footer .blocks .logo {
    text-transform: uppercase;
    font: 29px;
    font-weight: 800;
}

header nav {
    float: right;
    width: 50%;
}

header nav ul {
    list-style: none;
    display: flex;
    justify-content: space-between;
    z-index: 2;
    position: relative;
}

header nav ul li {
    display: inline-block;
}

header nav ul li a {
    color: #fff;
}

header nav ul li.active::after {
    content: '';
    display: block;
    width: 40px;
    height: 5px;
    background: aquamarine;
    border-radius: 10px;
    position: relative;
    top: 10%;
    left: -15px;
}

header nav ul li:not(.active):not(.btn) a:hover {
    border-bottom: 5px solid #dc7000;
}

header nav ul li.btn a, 
.email .block button {
    background: #fa9021;
    padding: 9px 17px;
    border-radius: 5px;
    transition: all 500ms ease;
}

header nav ul li.btn a:hover,
.email .block button:hover {
    background: #be0909;
}

.hero {
    padding-bottom: 100px;
    z-index: 1;
    position: relative;
}

.hero--info {
    width: 530px;
    padding-top: 70px;
}

.hero--info h2 {
    color: #e87d0e;
    font-size: 20px;
    font-weight: 600;
}

.hero--info h1 {
    font-size: 20px;
    font-weight: 600;
}

.hero--info p {
    font-weight: 500;
    line-height: 170%;
    margin: 30px 0;
}

.hero--info .btn {
    background: #fa8305;
    color: #fff;
    border-radius: 50px;
    padding: 15px 30px;
    border: 0;
    transition: all 500ms ease;
    font-size: 18px;
}

.hero--info .btn:hover {
    cursor: pointer;
    transform: scale(1.1);
}

.hero img {
    position: absolute;
    top: -150px;
    right: 0;
}

/* Секция с играми*/

.trending {
    padding-top: 50px;
}
.trending h3 {
    font-weight: 600;
    font-size: 31px;
}

.trending .see-all, .projects .see-all {
    color: #fff;
    background: #25211d;
    border-radius: 5px;
    padding: 12px 23px;
    float: right;
    display: block;
    transition: all 500ms ease;
}

.trending .see-all:hover, .projects .see-all:hover {
    transform: scale(1.1);
}

.trending .games {
    display: flex;
    justify-content: space-between;
    width: 100%;
    padding: 50px 0;
}

.trending .games span {
    display: block;
    text-align:center;
    margin-top: 20px;
}

.trending .games span img {
    position: relative;
    top: 5px;
    margin-right: 7px;
}

.big-text {
    padding: 50px 0;
    font-size: 35px;
    font-weight: 600;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
    width: 800px;
}

.banner h3 {
    font-size: 30px;
    font-weight: 600;
    margin-bottom: 30px;
}

.banner p {
    line-height: 170%;
    margin-bottom: 30px;
    width: 550px;
}

.banner img {
    width: 100%;
    margin-bottom: 30px;
}

/*Picture section*/

.feat {
    background: linear-gradient(158deg, rgba(0,0,0,1) 22%, rgba(44,30,10,1) 65%, rgba(91,61,21,1) 83%, rgba(108,80,31,1) 94%, rgba(143,115,35,1) 100%);
    /* background: url('img/Rectangle 5.png') no-repeat center center fixed; */
    background-size: cover;
    padding: 80px 0;
}

.feat h3, 
.feat p {
    margin-bottom: 20px;
    text-align: center;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;

}

.feat h3 {
    font-size: 30px;
}

.feat .info {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.feat .info .block {
    text-align: center;
    width: 20%;
    margin: 30px 2%;
}

.feat .info .block img {
    margin-bottom: 15px;
}

.projects {
    padding: 100px 0;
}

.projects h3 {
    margin: 30px 0;
    text-align: center;
}

.projects p {
    margin: 40px 0;
    text-align: center;
}

.projects .images {
    display: flex;
    justify-content: space-around;
    margin-bottom: 25px;
}

.projects .see-all {
    float: none;
    width: 60px;
    text-align: center;
    margin: 0 auto;
}

/* Bottom part */

.email {
    padding-bottom: 120px;
    
}

.email h3 {
    margin-top: 60px;
    font-size: 30px;
}

.email .block {
    background: #1C140F;
    margin-top: 30px;
    border-radius: 10px;
    padding: 40px 3%;
    width: 94%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.email .block h4 {
    font-size: 30px;
    font-weight: 500;
}

.email .block p {
    width: 500px;
}

.email .block input {
    background: #fff;
    outline: none;
    border: 0;
    border-radius: 5px;
    width: 300px;
    font-family: 'Poppins', sans-serif;
    font-weight: 400;
    padding: 20px 30px;
    color: green;
    position: relative;
    z-index: 1;
    padding-right: 120px;
}

.email .block input::placeholder {
    color: #898989;
}

.email .block button {
    cursor: pointer;
    border: 0;
    padding: 13px 17px;
    position: relative;
    z-index: 2;
    color: #fff;
}

/* footer */

footer {
    background: #000;
    padding: 50px 0;
}

footer .blocks {
    display: flex;
    justify-content: space-between;
}

footer .blocks p {
    width: 300px;
    margin: 15px 0;
}

footer .blocks h4 {
    font-weight: 500;
    font-size: 17px;
}

footer .blocks ul {
    list-style: none;
}

footer .blocks ul li {
    margin-top: 7px;
    opacity: 0.8;
}
