<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Tanmay - Power BI & Tableau Dashboards</title>
  <meta name="description" content="Explore Power BI and Tableau dashboards created by Your Name for data visualization projects.">
  <meta name="keywords" content="Power BI, Tableau, data visualization, dashboards, portfolio">
  <meta name="author" content="Your Name">
  <link rel="icon" href="favicon.png" type="image/x-icon" alt="Website Favicon">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles/light.css" id="light-theme">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
  /* Reset some default styles */
  body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
  }

  body {
    scroll-behavior: smooth;
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    color: #333333;
    background-color: #f7f7f7;
    border: 2px dotted #555555; /* Add this line for the dotted border */
  }

  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 50px;
    background-color: #C4C3BE;
    min-height: 100vh;
    max-width: 1400px;
    margin: 0 auto;
    border: 4px dotted #555555; /* Add this line for the dotted border */
  }

  .content {
    max-width: 800px;
    background-color: #FBFBFB;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    padding: 50px;
    border: 4px ridge #555555; /* Add this line for the dotted border */
  }

  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 20px;
  }

  .logo {
    width: 100px;
    height: 100px;
    border: 2px solid #F9F9F9;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    overflow: hidden;
  }

  .logo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 5px;
  }

  .contact-info {
    text-align: right;
  }

  h1 {
    font-size: 36px;
    margin-bottom: 20px;
    font-weight: 700;
    color: #454545;
  }

  h2 {
    font-size: 24px;
    margin-top: 30px;
    margin-bottom: 10px;
    font-weight: 700;
    color: #191919;
  }

  p {
    margin-bottom: 10px;
    font-size: 16px;
    line-height: 1.6;
  }

  ul {
    list-style-type: disc;
    padding-left: 20px;
    margin-top: 5px;
    margin-bottom: 10px;
  }

  li {
    margin-bottom: 5px;
    font-size: 16px;
    line-height: 1.6;
  }

  a {
    color: #1B2430;
    text-decoration: none;
  }

  a:hover {
    color: #20262E;
  }
  .project-title summary {
    cursor: pointer;
  }

  .project-screenshot.lazy {
    opacity: 0;
  }

  .project-screenshot.lazy-loaded {
    opacity: 1;
    transition: opacity 0.5s ease-in-out;
  }
  .screenshots,
  .links {
    margin-top: 10px;
  }

  .screenshots img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 10px;
    border: 4px ridge #555555;
    transition: opacity 0.5s ease-in-out;
  }

  .screenshots img.lazy {
    opacity: 0;
  }

  .screenshots img.lazy-loaded {
    opacity: 1;
  }
  .project-title summary {
    cursor: pointer;
  }

  .project-screenshot.lazy {
    opacity: 0;
  }

  .project-screenshot.lazy-loaded {
    opacity: 1;
    transition: opacity 0.5s ease-in-out;
  }
  .project-screenshot {
    max-width: 100%;
  }

  .footer {
    margin-top: 5px;
    text-align: center;
    font-size: 10px !important; /* Use !important to override conflicting styles */
    color: #777777;
  }

  .footer a {
    color: #0F0F0F;
    text-decoration: none;
  }

  .footer a:hover {
    text-decoration: underline;
  }


  /* Change the background and text color for selected content */
  ::selection {
    background-color: #555555; /* Adjust the background color as needed */
    color: #ffffff; /* Adjust the text color as needed */
  }

 /* Change the background and text color for selected content in Firefox */
  ::-moz-selection {
    background-color: #555555; /* Adjust the background color as needed */
    color: #ffffff; /* Adjust the text color as needed */
  }

  @media only screen and (max-width: 600px) {
    body {
      font-size: 14px;
      line-height: 1.5;
    }

    h1 {
      font-size: 24px;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 20px;
      margin-top: 20px;
      margin-bottom: 10px;
    }

    p,
    ul,
    li {
      margin-bottom: 8px;
    }

    .container {
      padding: 5px;
    }

    .content {
      padding: 10px;
    }

    .header {
      flex-direction: column;
      text-align: center;
      margin-bottom: 15px;
    }

    .logo {
      width: 80px;
      height: 80px;
      margin: 0 auto 10px;
    }

    .screenshots {
      margin-top: 20px;
    }

    .screenshots img {
      max-width: 100%;
      height: auto;
      border-radius: 5px;
      margin-bottom: 10px;
      border: 3px ridge #555555;
    }
  }
  </style>
</head>
<body>
  <div class="container">
    <div class="content">
      <div class="header">
        <div class="logo">
          <img src="profile_picture.jpg" alt="Logo">
        </div>
        <div class="contact-info">
          <p><strong>Email:</strong> kalbandetanmay@gmail.com</p>
          <p><strong>Phone:</strong> 737-838-1494</p>
        </div>
      </div>

      <h1>Tanmay Kalbande</h1>
      <h2>Power BI & Tableau Dashboards</h2>

      <!-- Power BI Dashboard -->
      <div class="project">
        <details class="project-title">
          <summary>
            <i class="fa fa-bar-chart"></i> <strong>Power BI Dashboard: Data Wave Metrics in India</strong>
            <ul>
              <li>Explore key wireless data usage and ARPU (Average Revenue Per User) metrics in India over different quarters.</li>
              <li>Gain insights into quarterly revenue, data consumption trends, and tariff variations.</li>
              <p><strong>Screenshot Title: Quarterly Metrics Overview</strong></p> <!-- Added Screenshot Title -->
            </ul>
          </summary>
          <img data-src="dashboard_screenshot/power_bi_screenshot_1.png" alt="Power BI Screenshot" class="project-screenshot lazy">
          <p class="project-link"><a href="dashboard/Data Wave Metrics in India.pbix" target="_blank">Download Power BI Dashboard</a></p>
        </details>
      </div>
    </div>
  </div>
  <!-- Footer -->
  <div class="footer">
      <p>Connect with me on <a href="https://www.linkedin.com/in/tanmay-kalbande" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a> | Check out my projects on <a href="https://github.com/tanmay-kalbande" target="_blank"><i class="fab fa-github"></i> GitHub</a></p>
      <p>© 2024 Tanmay Kalbande. All rights reserved.</p>
  </div>
  <script>
  document.addEventListener("DOMContentLoaded", function () {
    var lazyImages = document.querySelectorAll(".lazy");

    var lazyLoad = function () {
      lazyImages.forEach(function (img) {
        if (img.offsetTop < window.innerHeight + window.pageYOffset) {
          img.src = img.dataset.src;
          img.classList.remove("lazy");
          img.classList.add("lazy-loaded");
        }
      });
    };

    window.addEventListener("scroll", lazyLoad);
    window.addEventListener("resize", lazyLoad);
    window.addEventListener("orientationchange", lazyLoad);

    lazyLoad();
  });
</script>
</body>
</html>
