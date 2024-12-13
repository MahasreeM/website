# Ex.07 Restaurant Website
# Date:08-11-2024
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HungerHunt</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            text-align: center;
            color: #f4f4f4;
            padding: 40px;
            background: rgba(58, 57, 57, 0.7) url('top.jpg') center center fixed;
            background-size: cover;
            background-blend-mode: darken;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
       }
        .nav {
        text-align: center;
        padding: 10px;
        background-color: #333;
        }

        .nav a {
        color: white;
        margin: 0 15px;
        text-decoration: none;
        font-size: 18px;
        }

        .promo { 
        background-size: cover;
        background-position: center;
        color: rgb(13, 11, 11);
        padding: 40px 20px;
        text-align: center;
        }

        .promo h1 {
        font-size: 36px;
        margin-bottom: 20px;
        }

        .promo p {
        font-size: 16px;
        width: 80%;
        margin: 0 auto;
        }

        /* Cards Section */
        .cards {
        text-align: center;
        padding: 40px 0;
        }

        .card {
        display: inline-block;
        width: 300px;
        margin: 0 15px;
        background-color: #fefefe;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        border-radius: 10px;
        text-align: left;
        padding: 20px;
        }

        .card img {
        width: 100%;
        border-radius: 10px 10px 0 0;
        }

        .card h3 {
        font-size: 20px;
        margin: 15px 0;
        }

        .card p {
        font-size: 14px;
        color: #666;
        }

        .about-section {
        padding: 50px;
        text-align: center;
        }

        .about-section h2 {
        font-size: 36px;
        margin-bottom: 20px;
        }

        .about-section p {
        font-size: 18px;
        max-width: 600px;
        margin: auto;
        }

        /* Contact Section */
        .contact-section {
        padding: 50px;
        text-align: center;
        background-color: #333;
        color: white;
        }

        .contact-section h2 {
        font-size: 36px;
        margin-bottom: 20px;
        }

        /* Footer */
        .footer {
        text-align: center;
        padding: 10px;
        background-color: #333;
        color: white;
        }
        </style>
        </head>
        <body>

 #restaurent.html

        <div class="header">
        <h1>HungerHunt</h1>
        </div>

        <div class="nav">
        <a href="#">Home</a>
        <a href="menu.html">Menu</a>
        <a href="booking.html">Book</a>
        <a href="admin.html">Admin</a>
        <a href="#about">About</a>
        </div>
        <div class="promo">
        <h1>30% Off This Weekend</h1>
        </div>
        <div class="cards">
        <div class="card">
        <img src="menu.jpg" alt="Menu Image"> 
        <a href="menu.html">Click here</a>
        <h3>Our New Menu</h3>

        </div>
        <div class="card">
        <img src="booke.jpg" alt="Book a Table Image"> 
        <a href="booking.html">Click here</a>
        <h3>Book a Table</h3>
        </div>
        <div class="card">
        <img src="opening.jpg" alt="Opening Hours Image"> 
        <a href="opening.html">Click here</a>
        <h3>Opening Hours</h3>
        </div>
    </div>
    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>
        we believe that food should not only nourish the body but also tantalize the taste buds. Our chefs craft each dish with care, using locally sourced, organic produce to ensure that every meal is as fresh 
       and flavorful as possible. 
        </p>
    </section>
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>Email: contact@HungerHunt.com</p>
        <p>Phone: +91 8765433231</p>
        <p>Address: 123 Main Street, Foodville</p>
    </section>
    <footer class="footer">
        <p>&copy; 2024 HungerHunt Restaurant. All Rights Reserved.</p>
        <p>Developed by Maha shree M</p>
    </footer>
</body>
</html>

#style.css

      * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
      }
      body {
          font-family: Arial, sans-serif;
          background-color: #f4f4f4;
      }
      .container {
          display: flex;
          justify-content: center;
          gap: 20px;
          padding: 20px;
      }
      .card {
          background-color: white;
          border-radius: 10px;
          padding: 20px;
          box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
          text-align: center;
          width: 350px;
          text-decoration: none;
          color: inherit;
          transition: transform 0.2s;
      }
      .card:hover {
          transform: scale(1.05);
      }
      h2, h3 {
          margin-bottom: 15px;
          color: #333;
      }
      p, li {
          color: #666;
          font-size: 16px;
      }
      ul {
          list-style-type: none;
          padding-left: 0;
      }
      form {
          text-align: left;
          margin-top: 20px;
      }
      label {
          font-weight: bold;
          display: block;
          margin-bottom: 5px;
      }
      input[type="text"], input[type="email"], input[type="tel"], input[type="date"], input[type="time"], input[type="number"] {
          width: 100%;
          padding: 10px;
          margin-bottom: 15px;
          border: 1px solid #ccc;
          border-radius: 5px;
      }
      input[type="submit"] {
          background-color: #333;
          color: white;
          padding: 10px 20px;
          border: none;
          border-radius: 5px;
          cursor: pointer;
      }
      input[type="submit"]:hover {
          background-color: #555;
      }
      @media screen and (max-width: 768px) {
          .container {
              flex-direction: column;
              align-items: center;
          }
      }

#menu.html

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Menu</title>
          <link rel="stylesheet" href="styles.css">
      </head>
      <body>
          <div class="container">
              <div class="card menu">
                  <h2>Our Menu</h2>
                  <h3>Appetizers</h3>
                 
                  <ul>
                      <img src="food1.jpg">
                      <li>Burger</li>
                      <li>Specially made</li>
                      <li>$6</li>
                  </ul>
      
                  <h3>Main Courses</h3>
                  <ul>
                      <img src="food2.jpg">
                      <li>Pan cake</li>
                      <li>sweet and tasty</li>
                      <li>$15</li>
                      
                  </ul>
      
                  <h3>Desserts</h3>
                  <ul>
                      <img src="food4.jpg">
                      <li>Chocolate Lava Cake - $7</li>
                      <li>Tiramisu - $6</li>
                      <li>Cheesecake - $6</li>
                  </ul>
      
                  <h3>Beverages</h3>
                  <ul>
                      <img src="food3.jpg">
                      <li>French fries</li>
                      <li>crispy and choosy</li>
                      <li>$3</li>
                  </ul>
              </div>
          </div>
      </body>
      </html>

#booking.html

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Book a Table</title>
          <link rel="stylesheet" href="styles.css">
      </head>
      <body>
          <div class="container">
              <div class="card">
                  <h2>Book a Table</h2>
                  <p>Reserve your spot at our restaurant for an amazing dining experience. Please provide your details below, and we will get back to you with confirmation.</p>
      
                  <h3>Contact Information</h3>
                  <ul>
                      <li>Phone: +123-456-7890</li>
                      <li>Email: reservations@restaurant.com</li>
                  </ul>
      
                  <h3>Online Booking Form</h3>
                  <form>
                      <label for="name">Full Name:</label>
                      <input type="text" id="name" name="name" placeholder="Enter your name"><br><br>
      
                      <label for="email">Email:</label>
                      <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>
      
                      <label for="phone">Phone Number:</label>
                      <input type="tel" id="phone" name="phone" placeholder="Enter your phone number"><br><br>
      
                      <label for="date">Reservation Date:</label>
                      <input type="date" id="date" name="date"><br><br>
      
                      <label for="time">Time:</label>
                      <input type="time" id="time" name="time"><br><br>
      
                      <label for="guests">Number of Guests:</label>
                      <input type="number" id="guests" name="guests" min="1" max="20" value="2"><br><br>
      
                      <input type="submit" value="Submit Reservation">
                  </form>
              </div>
          </div>
      </body>
      </html>

#opening.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Book a Table</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="container">
            <div class="card">
                <h2>Book a Table</h2>
                <p>Reserve your spot at our restaurant for an amazing dining experience. Please provide your details below, and we will get back to you with confirmation.</p>
    
                <h3>Contact Information</h3>
                <ul>
                    <li>Phone: +91 8765433231 </li>
                    <li>Email: reservations@restaurant.com</li>
                </ul>
    
                <h3>Online Booking Form</h3>
                <form>
                    <label for="name">Full Name:</label>
                    <input type="text" id="name" name="name" placeholder="Enter your name"><br><br>
    
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>
    
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" placeholder="Enter your phone number"><br><br>
    
                    <label for="date">Reservation Date:</label>
                    <input type="date" id="date" name="date"><br><br>
    
                    <label for="time">Time:</label>
                    <input type="time" id="time" name="time"><br><br>
    
                    <label for="guests">Number of Guests:</label>
                    <input type="number" id="guests" name="guests" min="1" max="20" value="2"><br><br>
    
                    <input type="submit" value="Submit Reservation">
                </form>
            </div>
        </div>![Screenshot (90)](https://github.com/user-attachments/assets/1da9eeb0-1da9-47e0-a26b-a4fd74e68c8a)

    </body>
    </html>

```
# OUTPUT:
![Screenshot (84)](https://github.com/user-attachments/assets/027949a6-92be-4e1d-aaf2-ad2f5de05f70)
![Screenshot (85)](https://github.com/user-attachments/assets/3c8e6674-762e-401a-acad-213c9cb8906c)
![Screenshot (86)](https://github.com/user-attachments/assets/64d7923e-3e55-40a9-ae6b-a1aa865564b1)
![Screenshot (87)](https://github.com/user-attachments/assets/f22d37a4-2707-42f9-9558-8817155f1334)
![Screenshot (88)](https://github.com/user-attachments/assets/4560500f-905d-4c0c-a62b-3a85f0a86aad)
![Screenshot (89)](https://github.com/user-attachments/assets/6e03486f-d625-4a68-9b64-6a9cd0a316e2)
![Screenshot (90)](https://github.com/user-attachments/assets/d67b09e9-28f3-4685-be41-93ea5a3e4a8a)




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
