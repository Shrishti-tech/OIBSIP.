# OIBSIP.
Tribute page
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Virat Kohli — Tribute</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;900&display=swap" rel="stylesheet">

<style>
*{
  margin:0; padding:0; box-sizing:border-box;
  font-family:'Poppins', sans-serif;
}

body{
  background:#ffffff;
  color:#111;
}

/* HERO SECTION */
.hero{
  height:90vh;
  width:100%;
  background:linear-gradient(to right, rgba(255,60,60,0.6), rgba(255,120,0,0.7)),
             url('https://wallpapercave.com/wp/wp9164702.jpg') center/cover no-repeat;
  display:flex;
  align-items:center;
  padding-left:8%;
  color:white;
}

.hero h1{
  font-size:4rem;
  font-weight:900;
  text-transform:uppercase;
  line-height:1;
  text-shadow:0 3px 10px rgba(0,0,0,0.5);
}

.hero p{
  margin-top:10px;
  font-size:1.4rem;
  max-width:530px;
  line-height:1.6;
}

/* SECTION */
section{ padding:60px 10%; }

h2{
  font-size:2.8rem;
  font-weight:900;
  color:#ff3c3c;
  margin-bottom:15px;
}

.card{
  background:#fff4f4;
  padding:25px;
  border-radius:14px;
  box-shadow:0 10px 30px rgba(255,80,80,0.25);
  margin-bottom:40px;
}

.card p{
  font-size:1.1rem;
  line-height:1.8;
  margin-bottom:20px;
}

/* GALLERY */
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:20px;
}

.gallery div{
  background:white;
  padding:10px;
  border-radius:14px;
  box-shadow:0 6px 20px rgba(0,0,0,0.2);
}

.gallery img{
  width:100%;
  height:320px;
  object-fit:cover;
  border-radius:14px;
  transition:.3s;
}

.gallery img:hover{
  transform:scale(1.05);
  box-shadow:0 20px 40px rgba(255,60,60,0.4);
}

.gallery p{
  margin-top:10px;
  font-size:1rem;
  line-height:1.6;
}

/* FOOTER */
footer{
  text-align:center;
  margin-top:50px;
  padding:20px;
  background:#ff3c3c;
  color:white;
  font-weight:600;
}
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <div>
    <h1>Virat Kohli</h1>
    <p>One of the greatest batsmen of all time, known for intensity, passion and world-class consistency.</p>
  </div>
</div>

<!-- ABOUT -->
<section>
  <h2>About the Legend</h2>
  <div class="card">

    <p>
      Virat Kohli represents the modern era of cricket—bold, fearless, supremely fit, and committed to excellence.
      His passion for the game, aggressive attitude, and never-give-up spirit have transformed Indian cricket.
      He continues to inspire millions with his mental toughness, discipline, and iconic performances around the world.
    </p>

    <p>
      Virat Kohli’s journey is a story of relentless hard work and unmatched hunger for success. 
      From a young boy in Delhi dreaming big to becoming the face of world cricket, he has broken barriers 
      and rewritten record books with pure determination.
    </p>

    <p>
      As India’s captain, Virat Kohli brought intensity, accountability, and fitness culture into the team. 
      Under his leadership, India reached new heights in Test cricket, including the historic series win in Australia.
    </p>

    <p>
      Beyond cricket, Kohli stands as a global icon of dedication and resilience. His fitness revolution,
      charity work, and lifestyle choices continue to influence millions across the world.
    </p>

  </div>
</section>

<!-- GALLERY -->
<section>
  <h2>Iconic Moments</h2>

  <div class="gallery">

    <div>
      <img src="virat-kohli-png-lmp0gvwnCMrWEMaJHWAZvqjvFwoMMHf5.webp" alt="VK Image 1">
      <p>
        This image captures Kohli in his intense and focused stance—eyes locked on victory. His ability to stay calm
        under pressure and dominate world-class bowlers has made him one of cricket’s fiercest competitors.
      </p>
    </div>

    <div>
      <img src="3233263dc3da29414ee9fdc15e80eaba.jpg" alt="VK Image 2">
      <p>
        A moment filled with emotion and energy. Kohli's passion for the game is visible every time he steps on the field,
        inspiring teammates and millions of fans across the globe.
      </p>
    </div>

    <div>
      <img src="https://wallpapercave.com/wp/wp4059913.jpg" alt="VK Image 3">
      <p>
        This picture shows Kohli during his prime—confident, explosive and fearless. His consistency across formats
        redefined modern batting standards in international cricket.
      </p>
    </div>

    <div>
      <img src="Virat Kohli Indian cricketer PNG photo_1696774426_659183130.webp" alt="VK Image 4">
      <p>
        A symbol of elegance and national pride. Kohli’s technique, fitness, and discipline shaped him into one of 
        the greatest ambassadors of Indian cricket.
      </p>
    </div>

    <div>
      <img src="virat-kohli-indian-cricketer-playing-shot-hd-transparent-png-7017517125083307yhlzkwvpc.png" alt="VK Image 5">
      <p>
        A beautiful shot illustrating Kohli’s perfect timing and unmatched chase-master ability. His mastery in run-chases
        remains one of the greatest strengths in cricket history.
      </p>
    </div>

  </div>

</section>

<!-- CAREER -->
<section>
  <h2>Career Highlights</h2>

  <div class="card">
    <p>
      ✔ 70+ International Centuries <br>
      ✔ 25,000+ International Runs <br>
      ✔ ICC Cricketer of the Decade (2011–2020) <br>
      ✔ Fastest to 8k, 9k, 10k ODI Runs <br>
      ✔ Fitness icon and inspirational leader <br>
      ✔ One of the greatest chasers in cricket history
    </p>
  </div>
</section>

<footer>
  Made with ❤️ by Shrishti Dixit • King Kohli Forever
</footer>

</body>
</html>
