<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Responsive GitHub Readme</title>
  <style>
    /* Container for the two GitHub stats and the Artstation image */
    .container {
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      flex-wrap: nowrap;
      max-width: 100%;
      margin: 0 auto;
    }
    .container .item {
      flex: 1;
      text-align: center;
      margin: 10px;
    }
    /* Profile views always centered at the bottom */
    .profile-views {
      text-align: center;
      margin-top: 20px;
    }
    /* For smaller screens, stack items vertically */
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
      .container .item {
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <!-- Container for GitHub stats and Artstation image -->
  <div class="container">
    <!-- Left GitHub readme stats (for wide screens, left; for narrow screens, top) -->
    <div class="item">
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats.vercel.app/api?username=Zimrahin&amp;show_icons=true&amp;theme=transparent&amp;hide_border=true&amp;hide_rank=true&amp;include_all_commits=true&amp;custom_title=Zimrahin's+GitHub+Stats&amp;disable_animations=true&amp;hide=prs" alt="GitHub Stats" />
      </a>
    </div>

    <!-- Artstation image (always in the center) -->
    <div class="item">
      <a href="https://www.artstation.com/artwork/r9neD5">
        <img src="https://cdnb.artstation.com/p/assets/images/images/052/142/157/original/johan-cediel-rodriguez-pixel-artv2exp.gif?1659037637" alt="Artstation Image" width="200"/>
      </a>
    </div>

    <!-- Right GitHub readme stats (for wide screens, right; for narrow screens, bottom above profile views) -->
    <div class="item">
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zimrahin&amp;layout=compact&amp;theme=transparent&amp;hide_border=true&amp;disable_animations=true" alt="Top Languages" />
      </a>
    </div>
  </div>

  <!-- Profile views at the bottom center -->
  <div class="profile-views">
    <a href="https://youtu.be/dQw4w9WgXcQ">
      <img src="https://komarev.com/ghpvc/?username=Zimrahin&amp;label=Profile%20views&amp;color=006aff&amp;style=flat-square" alt="Profile Views" title="GitHub Profile Views"/>
    </a>
  </div>

</body>
</html>
