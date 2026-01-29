<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ekin's Cooking Guide</title>

  <style>
    /* ===== COLOR THEME ===== */
    :root {
      --baby-green: #cfe8dc;
      --beige: #f6f3ea;
      --dark-green: #5f8f7e;
      --white: #ffffff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: var(--beige);
      display: flex;
      height: 100vh;
      overflow: hidden;
      color: #333;
    }

    /* ===== LEFT CONTENT ===== */
    .left {
      width: 65%;
      padding: 60px;
      animation: fadeIn 1.5s ease;
    }

    h1 {
      font-size: 3rem;
      color: var(--dark-green);
      margin-bottom: 10px;
    }

    h2 {
      margin-top: 40px;
      color: var(--dark-green);
    }

    p {
      max-width: 600px;
      line-height: 1.6;
    }

    .editable-box {
      background: var(--white);
      padding: 20px;
      border-left: 6px solid var(--baby-green);
      border-radius: 8px;
      margin-top: 25px;
    }

    /* ===== RIGHT IMAGE SCROLLER ===== */
    .right {
      width: 35%;
      background: var(--baby-green);
      padding: 20px;
      overflow-y: auto;
      animation: slideIn 1.5s ease;
    }

    .right h3 {
      text-align: center;
      color: var(--dark-green);
      margin-bottom: 20px;
    }

    .recipe {
      margin-bottom: 25px;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
    }

    .recipe img {
      width: 100%;
      border-radius: 12px;
      cursor: pointer;
    }

    .recipe:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    }

    /* ===== ANIMATIONS ===== */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideIn {
      from { opacity: 0; transform: translateX(40px); }
      to { opacity: 1; transform: translateX(0); }
    }

    /* ===== SCROLLBAR ===== */
    .right::-webkit-scrollbar {
      width: 8px;
    }

    .right::-webkit-scrollbar-thumb {
      background: #9fcbb9;
      border-radius: 10px;
    }
  </style>
</head>

<body>

  <!-- ===== LEFT SIDE CONTENT ===== -->
  <div class="left">
    <h1>Ekin's Cooking Guide</h1>

    <p>
      Welcome to my cozy cooking space where I share my favorite recipes,
      inspirations, and kitchen experiments.
    </p>

    <div class="editable-box">
      <!-- ✏️ EDIT THIS SECTION LATER -->
      <h2>About Me</h2>
      <p>
        Hi! I’m Ekin. I love creating simple, comforting meals with beautiful
        ingredients. This website is my personal recipe collection.
      </p>
    </div>

    <div class="editable-box">
      <!-- ✏️ EDIT THIS SECTION LATER -->
      <h2>Cooking Style</h2>
      <p>
        Fresh ingredients, cozy flavors, and easy-to-follow recipes
        for everyday cooking.
      </p>
    </div>
  </div>

  <!-- ===== RIGHT SIDE IMAGE SCROLLER ===== -->
  <div class="right">
    <h3>Recipes</h3>

    <!-- IMAGE 1 -->
    <div class="recipe">
      <a href="pasta.html">
        <img src="Spicy-Pasta-recipe-optimised-scaled.webp" alt="Pasta Recipe">
      </a>
    </div>

    <!-- IMAGE 2 -->
    <div class="recipe">
      <a href="cake.html">
        <img src="featured-stovetop-burgers-recipe.jpg" alt="Cake Recipe">
      </a>
    </div>

    <!-- IMAGE 3 -->
    <div class="recipe">
      <a href="cesarsalad.html">
        <img src="Caesar-Salad-9.jpg" alt="Salad Recipe">
      </a>
    </div>

    <!-- ➕ ADD MORE RECIPES HERE -->
  </div>

</body>
</html>
