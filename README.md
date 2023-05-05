# RESPONSIVE_WEBSITE_USING-HTML5-AND-CSS3
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="CSS/style.css">
    <link rel="stylesheet" media="screen and (max-width:1200px)" href="CSS/phone.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@700&family=Bree+Serif&display=swap"
        rel="stylesheet">
    <title>Best Online Food Delivery Service in India | MyOnlineMeal.com</title>
</head>

<body>
    <nav id="navbar">
        <div id="logo">
            <img src="logo.png" alt="MyOnlineMeal.com">
        </div>

        <ul>
            <li class="item"><a href="#home">Home</a></li>
            <li class="item"><a href="#services-container">Services</a></li>
            <li class="item"><a href="#clients">Our Clients</a></li>
            <li class="item"><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <section id="home">
        <h1 class="h-primary">Welcome to MyOnlineMeal</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit Lorem ipsum dolor sit. </p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing lorem4 </p>
        <button class="btn">Order Now</button>
    </section>
    
    <section id="services-container">
        <h1 class="h-primary center">Our Services</h1>
        <div id="services">
            <div class="box">
                <img src="img/1.png" alt="">
                <h2 class="h-secondary center">Food Catering</h2>
                <p class="center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam dignissimos amet aliquam voluptatum Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dicta quos corporis rerum laboriosam voluptatum nemo nihil nulla. Amet!, reiciendis nesciunt voluptatem animi id optio beatae ad deserunt culpa, </p>
            </div>
            <div class="box">
                <img src="img/2.png" alt="">
                <h2 class="h-secondary center">Bulk Ordering</h2>
                <p class="center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam dignissimos amet aliquam voluptatum Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora saepe dignissimos culpa sapiente, deleniti molestiae magni ab placeat., reiciendis nesciunt voluptatem animi id optio beatae ad deserunt culpa, </p>
            </div>
            <div class="box">
                <img src="img/3.png" alt="">
                <h2 class="h-secondary center">Food Ordering</h2>
                <p class="center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam dignissimos amet aliquam voluptatum Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus iure unde vel in atque, pariatur laudantium deserunt? Facere?, reiciendis nesciunt voluptatem animi id optio beatae ad deserunt culpa,</p>
            </div>
        </div>
    </section>

    <section id="client-section">
        <h1 class="h-primary center">Our Clients</h1>
        <div id="clients">
            <div class="client-item">
                <img src="img/logo1.png" alt="Our Clients">
            </div>
            <div class="client-item">
                <img src="img/logo2.png" alt="Our Clients">
            </div>
            <div class="client-item">
                <img src="img/logo3.png" alt="Our Clients">
            </div>
            <div class="client-item">
                <img src="img/logo4.png" alt="Our Clients">
            </div>
        </div>
    </section>

    <section id="contact">
        <h1 class="h-primary center">Contact Us</h1>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" name="name" id="name" placeholder="Enter your name">
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" name="name" id="email" placeholder="Enter your email">
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="phone" name="name" id="phone" placeholder="Enter your phone">
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                   <textarea name="message" id="message" cols="30" rows="10"></textarea>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            Copyright &copy; www.myOnlineMeal.com. All rights are reserved! 
        </div>
    </footer>

</body>

</html>
