# restaurant- <!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Annalakshmi Restaurant</title>

  <link rel="stylesheet" href="style.css">
</head>

<body>

  <!-- Navbar -->

  <nav>

    <h1>Annalakshmi</h1>

    <ul>
      <li>Home</li>
      <li>Menu</li>
      <li>Reservation</li>
      <li>Contact</li>
    </ul>

  </nav>

  <!-- Hero Section -->

  <section class="hero">

    <img src="images/restaurant.jpg" alt="Restaurant Image">

    <h2>Experience Traditional Fine Dining</h2>

    <button>Reserve Table</button>
    <!-- About Section -->

<section class="about">

  <div class="about-text">

    <h2>About Annalakshmi</h2>

    <p>
      Annalakshmi is a traditional vegetarian fine dining restaurant
      known for its cultural ambience, elegant hospitality,
      and authentic Indian cuisine.

      The restaurant blends spirituality, tradition,
      and premium dining experience together.
    </p>

    <p>
      Experienced chefs prepare dishes with authentic flavors
      and rich South Indian traditions.
    </p>

  </div>

  <div class="about-image">

    <img src="images/about.jpg" alt="Restaurant Interior">

  </div>

</section>

  </section>

<section class="tables">

  <!-- Table 1 -->

  <div class="card">

    <h3>Table 1</h3>

    <p id="status1">🟢 Available</p>

    <p>Seats: 4</p>

    <input type="text" id="name1" placeholder="Enter Name">

    <input type="text" id="phone1" placeholder="Phone Number">

    <button onclick="reserveTable('status1','name1','phone1')">
      Reserve
    </button>

  </div>

  <!-- Table 2 -->

  <div class="card">

    <h3>Table 2</h3>

    <p id="status2">🟢 Available</p>

    <p>Seats: 6</p>

    <input type="text" id="name2" placeholder="Enter Name">

    <input type="text" id="phone2" placeholder="Phone Number">

    <button onclick="reserveTable('status2','name2','phone2')">
      Reserve
    </button>

  </div>

  <!-- Table 3 -->

  <div class="card">

    <h3>Table 3</h3>

    <p id="status3">🟡 Cleaning</p>

    <p>Seats: 2</p>

    <input type="text" id="name3" placeholder="Enter Name">

    <input type="text" id="phone3" placeholder="Phone Number">

    <button onclick="reserveTable('status3','name3','phone3')">
      Reserve
    </button>

  </div>

</section>

  <script src="script.js"></script>

</body>

</html>
