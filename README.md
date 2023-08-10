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
