<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inventory Management System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        ul {
            padding: 0;
            list-style: none;
        }
        .main {
            padding: 20px;
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            max-width: 100%;
            background: #000;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Inventory Management System</h1>
        </div>
    </header>
    <div class="container main">
        <section id="project-details">
            <h2>Project Details</h2>
            <p>This PHP-based Inventory Management System handles product sales and information. It features three user roles: Admin, Special User, and User, with the admin having full control.</p>
            <h3>Key Features</h3>
            <ul>
                <li>User Management: Admin can manage users and assign roles.</li>
                <li>Product and Category Management: Admin can add, update, and delete products and categories.</li>
                <li>Sales Management: Admin can record sales details, including product name, quantity, and date.</li>
                <li>Sales Reports: Generate sales reports daily, weekly, and monthly.</li>
                <li>Media Attachment: Users can upload and attach images to products.</li>
                <li>Dashboard: Displays recent product sales with the highest quantities.</li>
                <li>The system systematically organizes records by category and provides detailed sales information, including buying and selling prices, total cost, date, quantities, and profit margins.</li>
            </ul>
        </section>
        
        <section id="slide">
            <h2>Slide</h2>
            <p>For more details, visit the <a href="https://gamma.app/docs/Inventory-Management-System-ssv9pivp27zr3fc" target="_blank">Inventory Management System Documentation</a>.</p>
        </section>
        
        <section id="video">
            <h2>Video Overview</h2>
            <div class="video-container">
                <iframe src="YOUR_YOUTUBE_VIDEO_LINK" frameborder="0" allowfullscreen></iframe>
            </div>
        </section>
        
        <section id="features">
            <h2>Available Features</h2>
            <ul>
                <li>Admin panel</li>
                <li>Employee panel</li>
                <li>Special user panel</li>
                <li>Manage user groups</li>
                <li>User management system</li>
                <li>Account settings</li>
                <li>Arrange categories</li>
                <li>Product management system</li>
                <li>Upload media files</li>
                <li>Sales management system</li>
                <li>Generate monthly, weekly, and daily sales reports</li>
                <li>Top latest sale items</li>
                <li>Highest selling products</li>
            </ul>
        </section>
        
        <section id="er-diagram">
            <h2>ER Diagram Model</h2>
            <div class="image-container">
                <img src="https://postimg.cc/zVxYBMmY" alt="ER Diagram for Inventory Management System">
            </div>
        </section>
    </div>
</body>
</html>

