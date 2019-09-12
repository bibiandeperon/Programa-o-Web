# Programa-o-Web
Html página site
PART1  trata-se da primeira coluna da pagina.


<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">

<head>
    <style>
        .header {
            display:inline-block;
            margin: 0px;
            margin-left: 0px;
            margin-right: 10px;
            margin-bottom:0px;


        }
        .content {
        display: inline-block;
        text-align:center;
       
       
        }
            .mat {
                display:block;
            }
               
            .modern {
                display:block;
               
            }
            .but {
                display:block;
               
            }
            .link{
                display:block;
            }

        .search{
            border-color: none;
            text-decoration:none;
        }
          .menuLogo .version {
            list-style-type: none;
        }

        .menu ul li a {
            text-decoration: none;
            list-style-type: none;
            font-family: 'Segoe UI';
            font-size: 13px;
            line-height: 44px;
            height: 44px;
            padding: 0 30px;
            color: rgba(0,0,0,0.87);
            font-weight: 500;
            cursor: pointer;
        }
        .menu ul li a:hover {
            background-color:gainsboro;
       
        }

       
            .menu .button {
                background-color: #26a69a;
                color: #fff;
                border-radius: 2px;
                margin-top: calc(22px - 11px);
                font-weight: 300;
                font-size: 0.8rem;

                min-width: 3rem;
                padding: 0 6px;
                margin-left: 14px;
                text-align: center;
                line-height: 22px;
                height: 22px;
                box-sizing: border-box;
            }
       

        .button {
            background-color: #ee6e73;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-weight: 400;
            font-size: 18px;
            margin: 4px 2px;
            cursor: pointer;
        }

        .link a {
            color: rgba(0,0,0,0.53);
            text-decoration: none;
        }

        .mat h1 {
            font-weight: 300;
            color: #ee6e73;
            font-size: 4.2rem;
        }

        .modern h4 {
            color: rgba(0,0,0,0.87);
            font-weight: 300;
            font-size: 31.92px;
            font-family:'Segoe UI';

        }
     

 

    </style>

   

    <meta charset="utf-8" />
    <title>Documentatation - Materialize</title>
</head>
<body>
    <div class=" header">
        <div class="menuLogo">
            <ul>
                <li class=" logo"> Colocar logo aqui</li>

                <li class="version">1.0.0</li>
            </ul>
        </div>

        <div class="search">
            <input type="search" id="mySearch" placeholder="Search">

        </div>

        <div class="menu">
            <ul>
                <li>
                    <a href="https://materializecss.com/about.html">About</a>
                </li>

                <li>
                    <a href="https://materializecss.com/getting-started.html">Getting Started</a>
                </li>

                <li>
                    <a href="">CSS</a>
                </li>

                <li>
                    <a href="">Components</a>
                </li>

                <li>
                    <a href="">JavaScript</a>
                </li>

                <li>
                    <a href="">Forms</a>
                </li>

                <li>
                    <a href="https://materializecss.com/mobile.html">Mobile</a>
                </li>

                <li>
                    <a href="https://materializecss.com/showcase.html">Showcase</a>
                </li>

                <li>
                    <a href="https://materializecss.com/themes.html">Themes
                    <span class="button">update</span>

                    </a>
                </li>
            </ul>
        </div>
    </div>

    <div class="content">
        <div class=" mat">
            <h1> Materalize</h1>
        </div>

        <div class="modern">
            <h4> A modern responsive front-end framework based on Material Design </h4>
        </div>

        <div class="but">
            <a href="#" class="button">Get Started</a>
            <a href="#" class="button">Upgrade From 0.100.2</a>
        </div>

        <div class="link">

            <a href="https://github.com/Dogfalo/materialize">Release 1.0.0</a>
        </div>
    </div>

</body>
