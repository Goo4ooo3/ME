
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نص في منتصف الصفحة</title>
</head>
<body>
    <table width="100%" height="10%" style="border: none;">
        <tr>
            <td align="center" valign="middle">
                
            </td>
        </tr>
    </table>
</body>
</html>
  <!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة ويب فخمة</title>
    <style>
        /* إعدادات الصفحة الأساسية */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: 'Arial', sans-serif;
            background-color: #111;
            color: #fff;
        }

        /* تنسيق الهيدر */
        header {
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            padding: 50px 0;
            text-align: center;
            color: #fff;
        }

        header h1 {
            font-size: 50px;
            margin: 0;
            text-transform: uppercase;
        }

        header p {
            font-size: 20px;
            margin-top: 10px;
            font-weight: 300;
        }

        /* تصميم القسم الرئيسي */
        .main-content {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 80vh;
            background: url('https://source.unsplash.com/1600x900/?luxury,night') center/cover no-repeat;
            background-size: cover;
        }

        .main-content .text {
            color: #fff;
            text-align: center;
            max-width: 600px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 30px;
            border-radius: 10px;
        }

        .main-content h2 {
            font-size: 35px;
            margin-bottom: 20px;
        }

        .main-content p {
            font-size: 18px;
            line-height: 1.5;
        }

        /* تصميم الأزرار */
        .btn {
            display: inline-block;
            padding: 15px 30px;
            font-size: 16px;
            color: #fff;
            background-color: #2575fc;
            text-decoration: none;
            border-radius: 50px;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #6a11cb;
        }

        /* تصميم الفوتر */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #111;
            color: #888;
            font-size: 14px;
        }

        footer a {
            color: #2575fc;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* تأثيرات التمرير */
        .fade-in {
            opacity: 0;
            animation: fadeIn 2s forwards;
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>

    <!-- الهيدر -->
    <header>
        <h1>Go!</h1>
        <p>Hello in my wep</p>
    </header>

    <!-- القسم الرئيسي -->
    <div class="main-content">
        
         <div class="text fade-in">            
            <h2>Log in</h2>
     <p>  Sellect your accont in theWep </p>
                         <a href="#" class="btn">Login</a> 

        </div>
    </div>

    <!-- الفوتر -->
    <footer>
        <p>حقوق الطبع والنشر © 2024 <a href="#">اسم شركتك</a>. جميع الحقوق محفوظة.</p>
    </footer> 

</body>
</html>
