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

  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Recipes</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1>My Favorite Recipes</h1>

  <section class="recipes">
    <div class="recipe">
      <a href="pasta.html">
        <img src="Spicy-Pasta-recipe-optimised-scaled.webp" alt="Spicy pasta recipe">
        <h2>Spicy Pasta</h2>
      </a>
    </div>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Spicy Pasta Recipe</title>
</head>
<body>

  <h1>Spicy Pasta</h1>
  <img src="Spicy-Pasta-recipe-optimised-scaled.webp" alt="Spicy pasta">

  <h2>Ingredients</h2>
  <ul>
    <li>Pasta</li>
    <li>Olive oil</li>
    <li>Garlic</li>
    <li>Chili flakes</li>
    <li>Tomato sauce</li>
    <li>Salt & pepper</li>
  </ul>

  <h2>Instructions</h2>
  <ol>
    <li>Boil pasta according to package instructions.</li>
    <li>Heat olive oil and sauté garlic.</li>
    <li>Add chili flakes and tomato sauce.</li>
    <li>Mix in pasta and season.</li>
  </ol>

  <a href="index.html">⬅ Back to recipes</a>

</body>
</html>


   <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Burger Recipe</title>
</head>
<body>

  <h1>Juicy Burger</h1>
  <img src="featured-stovetop-burgers-recipe.jpg" alt="Burger">

  <h2>Ingredients</h2>
  <ul>
    <li>Beef patty</li>
    <li>Burger buns</li>
    <li>Cheese</li>
    <li>Lettuce</li>
    <li>Tomato</li>
    <li>Salt & pepper</li>
  </ul>

  <h2>Instructions</h2>
  <ol>
    <li>Season the beef patty.</li>
    <li>Cook on a hot pan or grill.</li>
    <li>Add cheese and let it melt.</li>
    <li>Assemble burger with toppings.</li>
  </ol>

  <a href="index.html">⬅ Back to recipes</a>

</body>
</html>

  </section>

</body>
</html>


    <!-- IMAGE 2 -->
    <div class="recipe">
      <a href="burger.html">
        <img src="featured-stovetop-burgers-recipe.jpg" alt="Burger Recipe">
      </a>
    </div>

    <!-- IMAGE 3 -->
    <div class="recipe">
      <a href="cesarsalad.html">
        <img src="Caesar-Salad-9.jpg" alt="Salad Recipe">
      </a>
    </div>
<div class="right">
  <h3>Recipes</h3>

  <div class="recipe">
    <a href="pasta.html"><img src="images/pasta.jpg" alt="Pasta Recipe"></a>
  </div>

  <div class="recipe">
    <a href="cake.html"><img src="images/cake.jpg" alt="Cake Recipe"></a>
  </div>

  <div class="recipe">
    <a href="cesarsalad.html"><img src="images/Caesar-Salad-9.jpg" alt="Caesar Salad Recipe"></a>
  </div>
</div>

    <!-- ➕ ADD MORE RECIPES HERE -->
  </div>

</body>
</html>
