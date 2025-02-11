<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASSAM READS</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            background-color: #111;
            scroll-behavior: smooth;
        }

        /* Header Section */
        header {
            position: relative;
            background: url('ae2.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            animation: fadeIn 2s ease-in-out;
        }

        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
        }

        .content {
            position: relative;
            z-index: 2;
        }

        h1 {
            font-size: 3.5em;
            margin: 0;
            font-weight: 700;
        }

        .quote {
            font-size: 1.4em;
            font-style: italic;
            margin: 20px 0;
            color: #ccc;
        }

        .btn-register {
            display: inline-block;
            margin-left: 15px;
            padding: 12px 25px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            font-size: 1.1em;
            border-radius: 5px;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .btn-register:hover {
            transform: scale(1.1);
            background-color: #218838;
        }

        /* Navigation Bar */
        .navbar {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0, 0, 0, 0.9);
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
        }

        .navbar .logo img {
            height: 45px;
        }

        .nav-links {
            display: flex;
            align-items: center;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1em;
            transition: color 0.3s;
            position: relative;
        }

        .nav-links a:hover {
            color: #28a745;
        }

        /* Contact Dropdown */
        .contact-dropdown {
            position: absolute;
            display: none;
            background: rgba(0, 0, 0, 0.9);
            padding: 10px;
            border-radius: 5px;
            top: 40px;
            left: 0;
            width: 160px;
        }

        .contact-dropdown a {
            display: block;
            color: #28a745;
            padding: 5px;
            text-decoration: none;
            transition: color 0.3s;
        }

        .contact-dropdown a:hover {
            color: #fff;
        }

        .contact-container {
            position: relative;
        }

        /* About Section */
        .about {
            padding: 50px;
            background-color: #222;
            text-align: left;
            color: #ddd;
            animation: fadeIn 2s ease-in-out;
        }

        .about h2 {
            font-size: 2.3em;
            color: #fff;
        }

        /* Footer Section */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #111;
            color: white;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function () {
            const contactContainer = document.querySelector(".contact-container");
            const contactDropdown = document.querySelector(".contact-dropdown");
            let timeout;

            contactContainer.addEventListener("mouseenter", function () {
                clearTimeout(timeout);
                contactDropdown.style.display = "block";
            });

            contactContainer.addEventListener("mouseleave", function () {
                timeout = setTimeout(() => {
                    contactDropdown.style.display = "none";
                }, 3000);
            });
        });
    </script>
</head>
<body>
    <div class="navbar">
        <div class="logo">
            <img src="ae1.png" alt="ASSAM READS Logo">
        </div>
        <div class="nav-links">
            <a href="#home">HOME</a>
            <a href="#about">ABOUT</a>
            <div class="contact-container">
                <a href="#contact">CONTACT</a>
                <div class="contact-dropdown">
                    <a href="#">Instagram</a>
                    <a href="#">Facebook</a>
                    <a href="#">Twitter</a>
                </div>
            </div>
            <a href="#register" class="btn-register">Register</a>
        </div>
    </div>

    <header id="home">
        <div class="overlay"></div>
        <div class="content">
            <h1>ASSAM READS</h1>
            <p class="quote">"A reader lives a thousand lives before he dies. The man who never reads lives only one."<br> – George R.R. Martin</p>
            <p class="quote">Experience the joy of reading together</p>
        </div>
    </header>

    <section class="about" id="about">
        <h2>ABOUT US</h2>
        <p>ASSAM READS is a community dedicated to reviving the joy of reading among people of all ages. Our aim is to create a space where book lovers can come together, share their passion, and rediscover the magic of literature. We believe in fostering a culture of reading that inspires curiosity, creativity, and connection. Join us in our mission to bring back the habit of reading, one book at a time. Together, let’s build a community where stories unite us and knowledge empowers us.</p>
        <p>মনত আছেনে সেই সময়, যেতিয়া পাঠৰ কিতাপৰ মাজত লুকুৱাই বাহিৰা কিতাপ পঢ়ি ধৰা পৰিছিলোঁ? বা 'ৰংমন' পঢ়িবলৈ বাট চাই থকা সময়? এতিয়া সেই উৎসাহ ক’ত গ’ল? সময়ৰ অভাৱ, নে মোবাইল ফোনৰ গ্ৰাস? যদি আপুনিও বিচাৰে যে সমাজত আৰু নতুন প্রজন্মৰ মাজত কিতাপ পঢ়াৰ অভ্যাস বৰ্তি থাকক, তেন্তে আমাৰ এই প্ৰচেষ্টাত হাত আগবঢ়াওক। আমি একেলগে লগ হৈ নিমাতে কিতাপ পঢ়িম।</p>
    </section>
</body>
</html>
