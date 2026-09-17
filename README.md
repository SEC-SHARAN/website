# Ex.05 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
## index.html
```html
<html>
<head>
    <title>Sea Bay</title>
   
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f0f0f2;
        }
        .custom-navbar {
            background-color: #333333;
        }
        .custom-card {
            background-color: #faebd7;
            border: none;
        }
    </style>
</head>
<body>

    <div class="container my-4">
        <div class="text-center mb-4">
            <h1 class="fw-bold text-dark" style="letter-spacing: 2px;">SEA BAY</h1>
        </div>
   <div class="card custom-navbar mb-4 p-2">
            <ul class="nav justify-content-center">
                <li class="nav-item"><a class="nav-link text-white fw-bold active" href="index.html">Home</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="menu.html">Menu</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="administration.html">Administration</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="contact.html">Contact Us</a></li>
            </ul>
        </div>
        <div class="p-5 mb-4 text-white rounded bg-dark" style="background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1621996346565-e3d5d6281298?auto=format&fit=crop&w=1200&q=80') center/cover;">
            <div class="container-fluid py-3">
                <h2 class="display-6 fw-bold">30% Off This Weekend</h2>
                <p class="col-md-8 fs-6">Join us this weekend and enjoy an exclusive 30% discount on all our signature pasta dishes and chef specials. Bring your family and friends to experience authentic Mediterranean flavors crafted with fresh, local ingredients.</p>
            </div>
        </div>
        <div class="row g-4 mb-4">
            <div class="col-md-4">
                <div class="card custom-card p-3 h-100 shadow-sm">
                    <h3 class="h4 fw-bold mb-3">Our New Menu</h3>
                    <img src="photo-1555939594-58d7cb561ad1.jpg" class="img-fluid rounded mb-3" alt="Menu">
                    <p class="small text-muted">Explore our latest seasonal dishes featuring grilled skewers, freshly baked flatbreads, and zesty citrus-infused creations designed to delight your palate.</p>
                    <a href="#" class="text-decoration-none fw-bold mt-auto">See our new menu</a>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card custom-card p-3 h-100 shadow-sm">
                    <h3 class="h4 fw-bold mb-3">Book a table</h3>
                    <img src="photo-1540420773420-3366772f4999.jpg" class="img-fluid rounded mb-3" alt="Table">
                    <p class="small text-muted">Secure your spot ahead of time for a cozy indoor dining experience or a vibrant outdoor meal. Reserve your table quickly and easily online.</p>
                    <a href="#" class="text-decoration-none fw-bold mt-auto">Book your table now</a>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card custom-card p-3 h-100 shadow-sm">
                    <h3 class="h4 fw-bold mb-3">Opening Hours</h3>
                    <img src="photo-1556910103-1c02745aae4d.jpg" class="img-fluid rounded mb-3" alt="Hours">
                    <p class="small text-muted mb-3">We are open daily to serve you fresh meals, warm hospitality, and delightful drinks during the following weekly hours:</p>
                    <div class="small fw-bold mt-auto">
                        <p class="mb-1">Mon - Fri: 2pm - 10pm</p>
                        <p class="mb-1">Sat: 2pm - 11pm</p>
                        <p class="mb-0">Sun: 2pm - 9pm</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="text-center py-3 border-top">
            <p class="small text-secondary mb-0">Developed by SHARAN S </p>
        </div>

    </div>

</body>
</html>
```
## menu.html
```html
<html>
<head>
    <title>Sea Bay</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background-color: #f0f0f2; }
        .custom-navbar { background-color: #333333; }
        .custom-card { background-color: #faebd7; border: none; }
    </style>
</head>
<body>
    <div class="container my-4">
        <div class="text-center mb-4">
            <h1 class="fw-bold text-dark" style="letter-spacing: 2px;">SEA BAY</h1>
        </div>
        <div class="card custom-navbar mb-4 p-2">
            <ul class="nav justify-content-center">
                <li class="nav-item"><a class="nav-link text-white" href="index.html">Home</a></li>
                <li class="nav-item"><a class="nav-link text-white fw-bold active" href="menu.html">Menu</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="administration.html">Administration</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="contact.html">Contact Us</a></li>
            </ul>
        </div>
        <h2 class="mb-4 text-center fw-bold">Our Complete Menu</h2>
        <div class="row g-4">
            <div class="col-md-6">
                <div class="card custom-card p-3 shadow-sm h-100">
                    <h3 class="h5 fw-bold text-danger">Appetizers & Starters</h3>
                    <ul class="list-unstyled mt-3">
                        <li class="d-flex justify-content-between py-2 border-bottom"><span>Lemon Garlic Bruschetta</span> <strong>$8.50</strong></li>
                        <li class="d-flex justify-content-between py-2 border-bottom"><span>Crispy Calamari</span> <strong>$12.00</strong></li>
                        <li class="d-flex justify-content-between py-2"><span>Greek Salad</span> <strong>$9.50</strong></li>
                    </ul>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card custom-card p-3 shadow-sm h-100">
                    <h3 class="h5 fw-bold text-danger">Main Courses</h3>
                    <ul class="list-unstyled mt-3">
                        <li class="d-flex justify-content-between py-2 border-bottom"><span>Signature Lemon Pasta</span> <strong>$16.00</strong></li>
                        <li class="d-flex justify-content-between py-2 border-bottom"><span>Grilled Chicken Skewers</span> <strong>$18.50</strong></li>
                        <li class="d-flex justify-content-between py-2"><span>Mediterranean Seabass</span> <strong>$22.00</strong></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="text-center py-3 border-top mt-5">
            <p class="small text-secondary mb-0">Developed by SHARAN S</p>
        </div>
    </div>
</body>
</html>
```
## administration.html
```html
<html>
<head>
    <title>Sea Bay</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background-color: #f0f0f2; }
        .custom-navbar { background-color: #333333; }
        .custom-card { background-color: #faebd7; border: none; }
    </style>
</head>
<body>
    <div class="container my-4">
        <div class="text-center mb-4">
            <h1 class="fw-bold text-dark" style="letter-spacing: 2px;">SEA BAY</h1>
        </div>

        <div class="card custom-navbar mb-4 p-2">
            <ul class="nav justify-content-center">
                <li class="nav-item"><a class="nav-link text-white" href="index.html">Home</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="menu.html">Menu</a></li>
                <li class="nav-item"><a class="nav-link text-white fw-bold active" href="administration.html">Administration</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="contact.html">Contact Us</a></li>
            </ul>
        </div>

        <h2 class="mb-4 text-center fw-bold">Staff & Management Portal</h2>
        <div class="row justify-content-center">
            <div class="col-md-6">
                <div class="card custom-card p-4 shadow-sm">
                    <h3 class="h5 fw-bold mb-3">Staff Login</h3>
                    <form>
                        <div class="mb-3">
                            <label class="form-label small fw-bold">Username or Email</label>
                            <input type="text" class="form-control" placeholder="Enter username">
                        </div>
                        <div class="mb-3">
                            <label class="form-label small fw-bold">Password</label>
                            <input type="password" class="form-control" placeholder="Password">
                        </div>
                        <button type="submit" class="btn btn-dark w-100">Login to Dashboard</button>
                    </form>
                </div>
            </div>
        </div>

        <div class="text-center py-3 border-top mt-5">
            <p class="small text-secondary mb-0">Developed by SHARAN S</p>
        </div>
    </div>
</body>
</html>
```
## contact.html
```html
<html>
<head>
    <title>Sea Bay</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background-color: #f0f0f2; }
        .custom-navbar { background-color: #333333; }
        .custom-card { background-color: #faebd7; border: none; }
    </style>
</head>
<body>
    <div class="container my-4">
        <div class="text-center mb-4">
            <h1 class="fw-bold text-dark" style="letter-spacing: 2px;">SEA BAY</h1>
        </div>

        <div class="card custom-navbar mb-4 p-2">
            <ul class="nav justify-content-center">
                <li class="nav-item"><a class="nav-link text-white" href="index.html">Home</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="menu.html">Menu</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="administration.html">Administration</a></li>
                <li class="nav-item"><a class="nav-link text-white fw-bold active" href="contact.html">Contact Us</a></li>
            </ul>
        </div>

        <h2 class="mb-4 text-center fw-bold">Get In Touch</h2>
        <div class="row g-4">
            <div class="col-md-6">
                <div class="card custom-card p-4 shadow-sm h-100">
                    <h3 class="h5 fw-bold mb-3">Send Us a Message</h3>
                    <form>
                        <div class="mb-3">
                            <label class="form-label small fw-bold">Your Name</label>
                            <input type="text" class="form-control" placeholder="John Doe">
                        </div>
                        <div class="mb-3">
                            <label class="form-label small fw-bold">Email Address</label>
                            <input type="email" class="form-control" placeholder="name@example.com">
                        </div>
                        <div class="mb-3">
                            <label class="form-label small fw-bold">Message</label>
                            <textarea class="form-control" rows="3" placeholder="How can we help you?"></textarea>
                        </div>
                        <button type="submit" class="btn btn-dark w-100">Send Message</button>
                    </form>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card custom-card p-4 shadow-sm h-100">
                    <h3 class="h5 fw-bold mb-3">Contact Information</h3>
                    <p class="small text-muted mb-2">Feel free to reach out to us via phone, email, or visit our restaurant location.</p>
                    <p class="mb-1 small"><strong>Address:</strong> Thiruvottiyur, Chennai</p>
                    <p class="mb-1 small"><strong>Phone:</strong> 8015172288</p>
                    <p class="mb-3 small"><strong>Email:</strong> kvarunasharan05@gmail.com</p>
                    <h6 class="fw-bold mt-4">Hours:</h6>
                    <p class="small mb-1">Mon - Fri: 2pm - 10pm</p>
                    <p class="small mb-1">Sat: 2pm - 11pm</p>
                    <p class="small mb-0">Sun: 2pm - 9pm</p>
                </div>
            </div>
        </div>

        <div class="text-center py-3 border-top mt-5">
            <p class="small text-secondary mb-0">Developed by SHARAN S</p>
        </div>
    </div>
</body>
</html>
```

# OUTPUT:
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (46).png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
