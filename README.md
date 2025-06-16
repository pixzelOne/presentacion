# Welcome to the Android & Samsung A52m Showcase

<div align="center" markdown="1">

  <!-- Animated Android mascot with bouncing and color pulsation -->
  <img 
    src="https://placehold.co/150x150/3ddc84/ffffff?text=Android+Bot+Logo" 
    alt="Animated Android robot icon in green with bouncing and color pulsation animation" 
    style="animation: bounce-pulse 4s ease-in-out infinite; width: 150px; height: 150px; display: block; margin: 0 auto;"
  />

</div>

<style>
  /* Bouncing and color pulse animation */
  @keyframes bounce-pulse {
    0%, 100% {
      transform: translateY(0);
      filter: drop-shadow(0 0 2px #28a745);
      filter: drop-shadow(0 0 4px #28a745);
      filter: drop-shadow(0 0 8px #28a745);
    }
    25% {
      transform: translateY(-20px);
      filter: drop-shadow(0 0 6px #22b14c);
      filter: drop-shadow(0 0 10px #22b14c);
    }
    50% {
      transform: translateY(0);
      filter: drop-shadow(0 0 2px #28a745);
    }
    75% {
      transform: translateY(-10px);
      filter: drop-shadow(0 0 4px #2ecc71);
      filter: drop-shadow(0 0 8px #2ecc71);
    }
  }

  /* Animated fade-in heading */
  h1, h2 {
    animation: fade-slide-in 1.5s ease forwards;
    opacity: 0;
    transform: translateY(20px);
  }

  h1 {
    animation-delay: 0.3s;
    font-family: 'Poppins', sans-serif;
    font-weight: 900;
    font-size: 3rem;
    color: #2ecc71;
    margin-bottom: 16px;
  }

  h2 {
    animation-delay: 0.6s;
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
    font-size: 2rem;
    color: #27ae60;
    margin-top: 64px;
    margin-bottom: 12px;
    border-left: 6px solid #27ae60;
    padding-left: 12px;
  }

  @keyframes fade-slide-in {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  /* Floating leaf-like decorative shapes */
  .floating-shape {
    position: fixed;
    border-radius: 50%;
    opacity: 0.15;
    filter: drop-shadow(0 0 4px #27ae60);
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
  }

  .shape-1 {
    width: 60px;
    height: 60px;
    background: #27ae60;
    top: 10vh;
    left: 10vw;
    animation-name: floatUpDown;
    animation-duration: 5s;
  }

  .shape-2 {
    width: 90px;
    height: 90px;
    background: #2ecc71;
    top: 75vh;
    right: 15vw;
    animation-name: floatUpDown;
    animation-duration: 7s;
    animation-delay: 1s;
  }

  .shape-3 {
    width: 40px;
    height: 40px;
    background: #1e8449;
    top: 50vh;
    left: 80vw;
    animation-name: floatUpDown;
    animation-duration: 6s;
    animation-delay: 0.5s;
  }

  @keyframes floatUpDown {
    0%, 100% {
      transform: translateY(0);
      opacity: 0.15;
    }
    50% {
      transform: translateY(-25px);
      opacity: 0.25;
    }
  }

  /* Body styling for presentation */
  body {
    background: linear-gradient(135deg, #eafaf1 0%, #cefae0 100%);
    color: #145a32;
    font-family: 'Poppins', sans-serif;
    line-height: 1.5;
    margin: 48px 24px;
    padding-bottom: 120px;
  }

  p {
    font-size: 1.1rem;
    max-width: 680px;
    margin: 0 auto 24px auto;
    padding: 0 12px;
  }

  /* Section container */
  section {
    max-width: 720px;
    margin: 0 auto 48px auto;
    padding: 0 12px;
  }
</style>

<section>
  <h1>Welcome to Your Android & Samsung A52m Presentation</h1>
  <p>This repository showcases the power and versatility of Android devices with a special focus on the Samsung Galaxy A52m. The Android mascot above features smooth, continuous animations embodying the energy and friendliness of the Android ecosystem.</p>
</section>

<section>
  <h2>About the Samsung Galaxy A52m</h2>
  <p>The Samsung Galaxy A52m is a dynamic midrange smartphone featuring:</p>
  <ul>
    <li>6.5-inch Super AMOLED display with 90Hz refresh rate for fluid visuals.</li>
    <li>Qualcomm Snapdragon 720G processor optimized for performance and power efficiency.</li>
    <li>Quad rear camera system with OIS for steady, clear photos.</li>
    <li>4500mAh battery with fast 25W charging support.</li>
    <li>Runs Android 11 with Samsung’s One UI for an intuitive user experience.</li>
  </ul>
</section>

<section>
  <h2>Experience the Motion</h2>
  <p>The animations in this README use modern CSS keyframes to create engaging, non-intrusive motion effects including:</p>
  <ul>
    <li><strong>Bounce and pulse</strong> on the Android mascot for lively presence.</li>
    <li><strong>Fade and slide</strong> for headings to enhance the presentation flow.</li>
    <li><strong>Floating accent shapes</strong> drifting gently in the background to add depth and harmony.</li>
  </ul>
</section>

<section>
  <h2>Get Involved</h2>
  <p>Feel free to explore, adapt, or enhance this project with your own creative animations and Android-based projects. Your contributions and suggestions are highly encouraged!</p>
</section>

<div class="floating-shape shape-1" aria-hidden="true"></div>
<div class="floating-shape shape-2" aria-hidden="true"></div>
<div class="floating-shape shape-3" aria-hidden="true"></div>

---
Thank you for visiting this animated README showcase!

