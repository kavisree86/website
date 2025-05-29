# Ex.07 Restaurant Website
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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bakes N Cakez - About</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: black;
      color: white;
    }

    section.about {
      padding: 20px;
    }

    section.about h2 {
      text-align: center;
      font-size: 32px;
      margin-bottom: 20px;
      color: #fff;
    }

    section.about p {
      font-size: 16px;
      color: #ccc;
      line-height: 1.6;
      text-align: center;
    }

    .bakery-showcase {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      background-color: green;
      color: black;
      padding: 20px;
      border-radius: 10px;
      margin-top: 40px;
      align-items: center;
    }

    .bakery-showcase img {
      width: 100%;
      max-width: 350px;
      border-radius: 10px;
      object-fit: cover;
    }

    .bakery-text {
      flex: 1;
      font-size: 1rem;
      align-self: center;
    }

    @media (max-width: 768px) {
      .bakery-showcase {
        flex-direction: column;
        text-align: center;
      }

      .bakery-text {
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <section class="about" id="about">
    <h2>About Us</h2>
    <p>
      TastyBites is your go-to place for mouthwatering meals that are quick, fresh, and unforgettable. 
      From classic burgers to handmade pasta and pizza straight from the oven, we serve happiness on every plate.
    </p>

    <!-- First Row: Box Image + Description -->
    <div class="bakery-showcase">
      <img src="/static/bak_image1.jpg" alt="Cake Box">
      <div class="bakery-text">
        <p>
          Bakes N Cakez in Porur, Chennai is a reliable name in the industry as they aim to deliver the best experience to their customers.
          This has helped them build up a loyal customer base. They started their journey in 2016 and ever since, they have ensured that the
          customer remains at the centre of their business operations and philosophy. As they are located in a favourable neighbourhood, 
          exactly at Old No.6, New No.32, Opposite to GRD THIRUMANA MAHALL, Vanniyar Street, Porur-600116, it is easy to locate Bakes N Cakez 
          on the map. For any kind of assistance or questions, it is best to contact them directly during their business hours.
        </p>
      </div>
    </div>

    <!-- Second Row: Text + Chef Image -->
    <div class="bakery-showcase">
      <div class="bakery-text">
        <p>
          At Bakes N Cakez, everything is handcrafted with love and precision. Our passionate team ensures each product—from gourmet cookies to custom celebration cakes—is baked to perfection. 
          We blend tradition with innovation to serve smiles with every bite.
        </p>
      </div>
      <img src="/static/0e123866-f9d5-4918-aa8e-3115c540113e.png" alt="Chef at Bakes N Cakez">
    </div>
  </section>

</body>
</html>
```
# OUTPUT:
<img width="960" alt="447348991-c8a2d43d-786f-4036-92a2-726a9ec14f06" src="https://github.com/user-attachments/assets/8ff6368f-cc7c-4a46-a7bf-9c23e37d1362" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
