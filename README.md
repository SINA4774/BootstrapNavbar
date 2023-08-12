# BootstrapNavbar
im planing to make a recreate this navbar which is made by figma i made 2 version of it and want to make them responsive but all my attemps has been futill! i will upload the other version plus a picture of the target project if possible!
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <style>
        @font-face {
            font-family: estedad;
            src: url(../fonts/Estedad-v5.0-Fontjo.com/ttf/Estedad-SemiBold.ttf);
        }
        
        .nav {
            font-family: estedad;
        }
        
        .nav.navbar-nav li a {
            color: white;
        }
        
        .navbar-header a {
            color: white;
        }
    </style>
</head>

<body>

    <nav class="navbar navbar-light" style="background-color: #45b1ff">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="#">امروز دوشنبه 1402/04/31 monday 22 june 2023</a>
            </div>
            <ul class="nav navbar-nav">
                <li><a href="#">امور قراردادها<img src="../pictures/ICONS/Clipboard Check.png" alt="" style="width: 40px;" class="justify-content-center"></a></li>
                <li><a href="#">اداری<img src="../pictures/ICONS/Folder Open.png" alt="" style="width: 40px;"></a></li>
                <li><a href="#">وب<img src="../pictures/ICONS/Notebook Minimalistic.png" alt="" style="width: 40px;"></a></li>
                <li><a href="#">تضمین کیفیت<img src="../pictures/ICONS/patch-check-fill.png" alt="" style="width: 40px;"></a></li>
                <li><a href="#">دسترسی فرم ها<img src="../pictures/ICONS/stack.png" alt="" style="width: 40px;"></a></li>
                <li><a href="#">گزارشات<img src="../pictures/ICONS/pie_chart.png" alt="" style="width: 40px;"></a></li>
                <li><a href="#">تعریف اولیه<img src="../pictures/ICONS/Frame 59.png" alt="" style="width: 40px;"></a></li>
                <li><a href="#">عملیات<img src="../pictures/ICONS/settings.png" alt="" style="width: 40px;"></a></li>
                <li class="active"><a href="#">مرضیه سیف اللهی راد کارشناس استقرار و تولید<img src="../pictures/ICONS/person.png"  alt="" style="width: 70px;"></a></li>
            </ul>
        </div>
    </nav>

    <div class="container">
        <h3>Inverted Navbar</h3>
        <p>An inverted navbar is black instead of gray.</p>
    </div>

</body>

</html>



/*HTML, CSS version*/


<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="../bootstrap.css">
    <link rel="stylesheet" href="../bootstrap.js">
    <link rel="stylesheet" href="../jquery.js">
    <style>
        body {
            margin: 0;
            font-family: estedad;
            font-weight: bold;
        }
        
        .topnav {
            overflow: hidden;
            background-color: #45b1ff;
        }
        
        .topnav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 14px;
        }
        
        a {
            margin-top: 30px;
            margin-left: 25px;
            margin-right: 25px;
        }
        
        .topnav a:hover {
            color: black;
        }
        
        .topnav a.active {
            background-color: #45b1ff;
            color: white;
        }
        
        .topnav .icon {
            display: none;
        }
        
        @media screen and (max-width: 600px) {
            .topnav a:not(:first-child) {
                display: none;
            }
            .topnav a.icon {
                float: right;
                display: block;
            }
        }
        
        @media screen and (max-width: 600px) {
            .topnav.responsive {
                position: relative;
            }
            .topnav.responsive .icon {
                position: absolute;
                right: 0;
                top: 0;
            }
            .topnav.responsive a {
                float: none;
                display: block;
                text-align: left;
            }
            @font-face {
                font-family: estedad;
                src: url(../fonts/Estedad-v5.0-Fontjo.com/ttf/Estedad-SemiBold.ttf);
            }
        }
    </style>
</head>

<body>

    <div class="topnav" id="myTopnav">
        <a href="#home" class="active" style="border-right-style: solid;border-width: 1px;line-height: 70px;position: relative;top: -20px;border-right-color: #FFFFFF;">امروز دوشنبه 1402/04/31 <a style="position: absolute;top: 25px;left: 10px;">monday 22 june 2023</a></a>
        <a href="#امور قراردادها">امور قراردادها<img src="../pictures/ICONS/Clipboard Check.png" alt="" style="width: 40px;position: relative;top: -30px;right: 56px;"></a>
        <a href="#اداری">اداری<img src="../pictures/ICONS/Folder Open.png" alt="" style="width: 40px;position: relative;top: -30px;right: 34px;"></a>
        <a href="#وب">وب<img src="../pictures/ICONS/Notebook Minimalistic.png" alt="" style="width: 40px;position: relative;top: -30px;right: 29px;"></a>
        <a href="#تضمین کیفیت">تضمین کیفیت<img src="../pictures/ICONS/patch-check-fill.png" alt="" style="width: 40px;position: relative;top: -30px;right: 60px;"></a>
        <a href="#دسترسی فرم ها">دسترسی فرم ها<img src="../pictures/ICONS/stack.png" alt="" style="width: 40px;position: relative;top: -30px;right: 65px;"></a>
        <a href="#گزارشات">گزارشات<img src="../pictures/ICONS/pie_chart.png" alt="" style="width: 40px;position: relative;top: -30px;right: 42px;"></a>
        <a href="#تعریف اولیه">تعریف اولیه<img src="../pictures/ICONS/Frame 59.png" alt="" style="width: 40px;position: relative;top: -30px;right: 50px;"></a>
        <a href="#عملیات">عملیات<img src="../pictures/ICONS/settings.png" alt="" style="width: 40px;position: relative;top: -30px;right: 40px;"></a>
        <a href="#نام کاربری" style="position: relative;top: -20px;border-left-style: solid;border-width: 1px;border-left-color: #FFFFFF;">نام کاربری<img src="../pictures/ICONS/person.png"  alt="" style="width: 70px;position: relative;"></a>
        <a href="javascript:void(0);" class="icon" onclick="myFunction()">
            <i class="fa fa-bars"></i>
        </a>
    </div>


    <script>
        function myFunction() {
            var x = document.getElementById("myTopnav");
            if (x.className === "topnav") {
                x.className += " responsive";
            } else {
                x.className = "topnav";
            }
        }
    </script>

</body>

</html>
