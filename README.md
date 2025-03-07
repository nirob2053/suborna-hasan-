<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal website for [ suborna hasan ]">
    <title>[suborna hasan ] - Personal Details</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"> <!-- Link to Font Awesome -->
    <style>
        /* Global Body Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000000;
            color: #333;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;  /* Ensure the body stretches to full height */
            flex-direction: column;
        }

        /* Header Section Styling */
        .header-text {
            font-size: 16px;
            font-weight: bold;
            color: #b0a7a7;
            margin-top: 20px;
        }

        /* Styling for the Box (without 3D effect) */
        .social-box {
            width: 70%;  /* Adjusted width */
            max-width: 400px;  /* Adjusted max-width */
            padding: 50px;  /* Increased padding for thickness */
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0px 15px 30px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }

        /* Main Description Text */
        .social-box h5 {
            font-size: 16px; 
            margin-bottom: 20px;
        }

        .social-box p {
            font-size: 16px;
            line-height: 1.6;
            color: #333;
        }

        /* Styling for the Social Media Icons */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .social-links a {
            display: inline-block;
            width: 60px;
            height: 60px;
            background-color: white;
            border-radius: 50%;
            text-align: center;
            line-height: 60px;
            color: white;
            font-size: 28px;
            text-decoration: none;
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        /* Hover Effect on Icons */
        .social-links a:hover {
            transform: scale(1.1);
            box-shadow: 0px 15px 30px rgba(0, 0, 0, 0.2);
        }

        /* Individual Social Media Icon Colors */
        .social-links .facebook {
            background-color: #1877f2;
        }

        .social-links .instagram {
            background-color: #e4405f;
        }

        .social-links .whatsapp {
            background-color: #25d366;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            .social-box {
                width: 90%;
                padding: 30px; /* Adjusted padding for smaller screens */
            }
            .social-links {
                gap: 15px;
            }
        }
    </style>
</head>
<body>

    <!-- Header Text for Overview -->
    <div class="header-text">
       <h1>My Personal Overview</h1> 
    </div>

    <!-- Box with Personal Description -->
    <div class="social-box"><h4>Suborna Hasan
        Professional Freelancer from Bangladesh
        
        I am a versatile freelancer with the ability to handle a wide range of tasks. Whether it's writing, designing, data entry, or anything in between, I can take on any project and deliver high-quality results. My skills are diverse, and I approach every task with dedication and precision. If you're looking for someone reliable and capable of getting things done, feel free to reach out! Let's work together to achieve your goals.</h4>
        
    <p>&copy; 2025 SUBORNA . All Rights Reserved. </p>
        <p><strong>No Copyright</strong> -  All content on this page is free to use, share, and modify without restrictions.</p>
        <div class="social-links">
            <!-- Social media icons with real colors -->
            <a href="https://www.facebook.com/profile.php?id=61568504961754" target="_blank" title="Facebook" class="facebook">
                <i class="fab fa-facebook-f"></i>
            </a>
            </a><a href="https://www.facebook.com/suborna.kitchen.713997" target="_blank" title="Facebook" class="facebook">
                <i class="fab fa-facebook-f"></i>
            <a href="https://wa.me/8801950588587" target="_blank" title="WhatsApp" class="whatsapp">
                <i class="fab fa-whatsapp"></i>
            </a>
        </div>
    </div>

</body>
</html>
