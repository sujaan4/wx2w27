<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Buddhayan Mahasangh — Official Website</title>
  <meta name="description" content="Buddhayan Mahasangh: Teachings, schedule, and updates. President: Bhante Rajratan." />
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    .logo {
  height: 48px;       /* adjust size */
  width: auto;        /* keep aspect ratio */
  border-radius: 6px; /* optional rounded corners */
  margin-right: 12px; /* space between logo and text */
}



    :root{
      --maroon:#6a1f2b;
      --maroon-dark:#531824;
      --saffron:#d4a017;
      --cream:#f7f3e9;
      --white:#ffffff;
      --blue:#2f5d8a;
      --text:#2a2a2a;
      --muted:#666666;
    }
    body{margin:0;font-family:Inter,Arial;color:var(--text);background:var(--cream);line-height:1.6;}
    a{color:var(--blue);text-decoration:none}
    a:hover{text-decoration:underline}
    header{background:var(--maroon);color:var(--white);position:sticky;top:0;z-index:1000;box-shadow:0 2px 6px rgba(0,0,0,0.2);}
    .topbar{max-width:1120px;margin:0 auto;display:flex;align-items:center;justify-content:space-between;padding:10px 16px;}
    .brand{display:flex;align-items:center;gap:12px;}
    .brand-logo{width:40px;height:40px;border-radius:50%;background:linear-gradient(135deg,var(--saffron),#f0c64a);border:2px solid #fff;}
    .brand h1{font-family:Merriweather,serif;font-size:20px;margin:0;font-weight:700;}
    .brand small{display:block;font-size:12px;color:#ffe9a8;}
    nav ul{list-style:none;margin:0;padding:0;display:flex;gap:18px;}
    nav a{color:#fff;font-weight:600;padding:8px 10px;border-radius:6px;}
    nav a:hover{background:var(--maroon-dark)}
    .hero{background:var(--maroon);color:#fff;padding:60px 16px;text-align:center;}
    .hero img{max-width:100%;border-radius:12px;margin-bottom:20px;box-shadow:0 4px 12px rgba(0,0,0,0.3);}
    .hero h2{font-family:Merriweather,serif;font-size:36px;margin:0 0 10px;}
    .hero p{font-size:18px;margin:0 0 24px}
    .cta{display:inline-block;background:var(--saffron);color:#2a1a0b;padding:10px 16px;border-radius:8px;font-weight:700;}
    section{padding:42px 16px}
    .container{max-width:1120px;margin:0 auto}
    .section-title{font-family:Merriweather,serif;font-size:24px;margin:0 0 16px;color:var(--maroon);border-left:4px solid var(--saffron);padding-left:10px;}
    .grid{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));}
    .card{background:#fff;border-radius:10px;box-shadow:0 2px 10px rgba(0,0,0,0.08);padding:18px;}
    .card img{width:100%;border-radius:10px;margin-bottom:12px;}
    .card h3{margin:0 0 8px;font-size:18px}
    .meta{color:var(--muted);font-size:14px;margin-bottom:8px}
    .embed{position:relative;padding-top:56.25%;border-radius:10px;overflow:hidden;box-shadow:0 2px 10px rgba(0,0,0,0.1)}
    .embed iframe{position:absolute;top:0;left:0;width:100%;height:100%;border:0}
    footer{background:var(--maroon);color:#fff;padding:24px 16px;}
    .footer-wrap{max-width:1120px;margin:0 auto;display:grid;gap:18px;grid-template-columns:2fr 1fr 1fr;}
    .social a{display:inline-block;margin-right:10px;color:#ffe9a8}
    .copyright{margin-top:12px;color:#ffe9a8;font-size:13px}
    @media (max-width:640px){.footer-wrap{grid-template-columns:1fr}}
  </style>
</head>
<body>

<header>
  <div class="topbar">
    <div class="brand">
      <!-- Logo image -->
      <img src="logo of buddhayan mahasangh.png" alt="Buddhayan Mahasangh Logo" class="logo">

      <div>
        <h1>Buddhayan Mahasangh</h1>
        <small>President: Bhante Rajratan</small>
      </div>
    </div>
    <nav>
      <ul id="navlinks">
        <li><a href="#about">About</a></li>
        <li><a href="#teachings">Teachings</a></li>
        <li><a href="#schedule">Schedule</a></li>
        <li><a href="#news">News</a></li>
        <li><a href="#media">Media</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>


<main>
    <section class="hero">
  <img id="heroImage" 
       src="mahakassap_mahavihar imag" 
       alt="Bhante Rajratan teaching" 
       width="900" 
       height="500">

  <h3>Compassion, Wisdom, and Community</h3>
  <p>Official website of Buddhayan Mahasangh under the guidance of President Bhante Rajratan.</p>
  <a class="cta" href="#teachings">Explore Teachings</a>
</section>

<script>
  // Array of image paths
  const images = [
    "mahakassap_mahavihar",
    "bhante_image",
    "IMG20251225092021.jpg",
    "tomorrow program"
  ];

  let index = 0;
  const heroImage = document.getElementById("heroImage");

  // Change image every 2 seconds
  setInterval(() => {
    index = (index + 1) % images.length; // cycle through images
    heroImage.src = images[index];
  }, 2000);
</script>

  

  <section id="about">
    <div class="container">
      <h2 class="section-title">About the Sangha</h2>
      <div class="grid">
        <div class="card">
          <img src="IMG20251225092021.jpg" alt="Lotus symbol">
          <h3>Vision & Mission</h3>
          <p>Promoting the Dhamma through education, social service, and mindful living across India and beyond.</p>
        </div>
        <div class="card">
          <img src="bhante_image" alt="Bhante Rajratan">
          <h3>President: Bhante Rajratan</h3>
          <p>Bhante Rajratan is dedicated to teaching the Buddha’s path with clarity and compassion.Bhante Rajratan is the esteemed president of Buddhayan Mahasangh. A dedicated Buddhist monk from Pune, Maharashtra, India, he has devoted his life to spreading the teachings of the Buddha through meditation, Dhamma talks, and community service. His YouTube channel features insightful videos on mindfulness, the Four Noble Truths, and guided meditations.</p>
        </div>
        <div class="card">
          <img src="bhante_image" alt="Community gathering">
          <h3>Centers & Activities</h3>
          <p>Weekly meditation, lectures, and community programs. Contact us to join or volunteer.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="teachings">
    <div class="container">
      <h2 class="section-title">Teachings & Webcasts</h2>
      <div class="grid">
        <div class="card">
          <div class="embed">
            <iframe src="Majjhima_Nik_ya_1080P.mp4" title="Teaching Video 1" allowfullscreen></iframe>
          </div>
        </div>
        <div class="card">
          <div class="embed">
            <iframe src="Majjhima_Nik_ya_2_1080P.mp4" title="Teaching Video 2" allowfullscreen></iframe>
          </div>
        </div>
      </div>
      <p class="meta">Follow for live teachings and updates on social channels below.</p>
    </div>
  </section>

  <section id="schedule">
    <div class="container">
      <h2 class="section-title">Schedule</h2>
      <div class="grid">
        <div class="card">
          <img src="tomorrow program" alt="Event poster">
          <h3>Upcoming Events</h3>
          <p><strong>Date:</strong> 25 Dec 2025 </br><strong>Time:</strong>3pm to 5pm
          </br><strong>Place:</strong> Mahakassap Mahavihar Ravet.</p>
        </div>
        <div class="card">
            <img src="bhante_image" alt="Event poster">
          <h3>Weekly Program</h3>
          <p><strong>Saturday:</strong> Group meditation, Chanting, Dhamma lecture and Q&A session </br><strong> Sunday:</strong> Group meditation, Chanting, Dhamma lecture and  Q&A session.</p>
        </div>
          <div class="card">
            <img src="bhante_image" alt="Event poster">
          <h3>How to Attend</h3>
          <p>Arrive 30 minutes early. </br>Seats first‑come‑first‑served. </br>Dress modestly & maintain silence in halls.</p>
        </div>
      </div>
    </div>
      </div>
    </div>
  </section>

  <section id="news">
    <div class="container">
      <h2 class="section-title">News & Updates</h2>
      <div class="grid">
        <div class="card">
            <img src="bhante_image" alt="Event poster">
          <h3>Community Outreach</h3>
          <p>Recent seva programs supporting education and health in local communities.</p>
          <p class="meta">Posted: Today</p>
        </div>
        <div class="card">
            <img src="bhante_image" alt="Event poster">
          <h3>Teachings Archive</h3>
          <p>Access past lectures, transcripts, and resources for study and practice.</p>
        </div>
        <div class="card">
            <img src="bhante_image" alt="Event poster">
          <h3>Announcements</h3>
          <p>New publication and upcoming regional dhamma tours.</p>
        </div>
      </div>
    </div>
  </section>
  <section id="media">
    <div class="container">
      <h2 class="section-title">Media & Social</h2>
      <div class="grid">
        <div class="card">
            <img src="Youtube_logo.png" alt="Event poster">
          <h3>YouTube</h3>
          <p>Watch teachings and events.</p>
          <p><a href="https://www.youtube.com/@bhanterajratan3640" target="_blank" rel="noopener">Visit Channel</a></p>
        </div>
        <div class="card">
            <img src="facebook_logo" alt="Event poster">
          <h3>Facebook</h3>
          <p>Community updates and photos.</p>
          <p><a href="hacttps://www.febook.com/Ven.bhanterajratan/" target="_blank" rel="noopener">Visit Page</a></p>
        </div>
        <div class="card">
            <img src="insta_logo" alt="Event poster">
          <h3>Instagram</h3>
          <p>Highlights and announcements.</p>
          <p><a href="https://www.instagram.com/bhanterajratan/" target="_blank" rel="noopener">Visit Profile</a></p>
        </div>
      </div>
    </div>
  </section>
  <section id="contact">
    <div class="container">
      <h2 class="section-title">Practical advice for attending</h2>
      <div class="grid">
        <div class="card">
          <h3>Guidelines</h3>
          <p>Maintain decorum, avoid photography during meditation, and follow volunteers’ instructions.</p>
        </div>
        <div class="card">
          <h3>Contact</h3>
          <p>Email: mahakassapmahavihar@gmail.com </br>Phone: +91-9273510001</p>
        </div>
        <div class="card">
          <h3>Donations</h3>
          <p>Support the Sangha’s educational and social initiatives. UPI / Bank details on request.</p>
        </div>
      </div>
    </div>
  </section>
</main>

<!-- Registration & Donation Section -->
<section id="participation" style="padding:40px 16px; background:#f7f3e9;">
  <div style="max-width:1100px; margin:0 auto;">
    <h2 style="color:#6a1f2b; border-left:4px solid #d4a017; padding-left:8px; font-family:Merriweather,serif;">
      Join & Support Buddhayan Mahasangh
    </h2>

    <!-- Flex container for forms -->
    <div class="form-row">
      <!-- Registration Form -->
      <form id="registrationForm" class="form-card">
        <h3>📝 Registration Form</h3>
        <label>Full Name:</label>
        <input type="text" id="regName" required>
        <label>Email:</label>
        <input type="email" id="regEmail" required>
        <label>Phone:</label>
        <input type="tel" id="regPhone" required>
        <label>Program:</label>
        <select id="regProgram" required>
          <option value="">--Choose--</option>
          <option value="Meditation Retreat">Meditation Retreat</option>
          <option value="Dhamma Lecture">Dhamma Lecture</option>
          <option value="Volunteer Service">Volunteer Service</option>
        </select>
        <button type="submit">Register</button>
        <div id="regMessage" class="message"></div>
      </form>

      <!-- Donation Form -->
      <form id="donationForm" class="form-card">
        <h3>💝 Donation Form</h3>
        <label>Name:</label>
        <input type="text" id="donName" required>
        <label>Email:</label>
        <input type="email" id="donEmail" required>
        <label>Amount (₹):</label>
        <input type="number" id="donAmount" min="1" required>
        <label>Payment Method:</label>
        <select id="donMethod" required>
          <option value="">--Choose--</option>
          <option value="UPI">UPI</option>
          <option value="Bank Transfer">Bank Transfer</option>
          <option value="Card">Credit/Debit Card</option>
        </select>
        <button type="submit">Donate</button>
        <div id="donMessage" class="message"></div>
      </form>
    </div>
  </div>
</section>

<style>
  .form-row {
    display: flex;
    gap: 24px;
    flex-wrap: wrap; /* ensures stacking on small screens */
    margin-top: 20px;
  }
  .form-card {
    flex: 1;
    background:#fff;
    padding:20px;
    border-radius:10px;
    box-shadow:0 4px 12px rgba(0,0,0,0.1);
    min-width:300px;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .form-card:hover {
    transform: translateY(-4px);
    box-shadow:0 6px 16px rgba(0,0,0,0.15);
  }
  .form-card h3 { color:#6a1f2b; margin-top:0; }
  label { display:block; margin-top:12px; font-weight:bold; color:#6a1f2b; }
  input, select {
    width:100%; padding:8px; margin-top:6px;
    border:1px solid #ccc; border-radius:6px;
    transition:border-color 0.2s;
  }
  input:focus, select:focus { border-color:#d4a017; outline:none; }
  button {
    margin-top:16px; background:#d4a017; color:#6a1f2b;
    border:none; padding:10px 16px; border-radius:6px;
    font-weight:bold; cursor:pointer;
    transition: background 0.2s, transform 0.2s;
  }
  button:hover { background:#e6b93f; transform: scale(1.05); }
  .message {
    margin-top:12px; display:none; padding:10px;
    border-radius:6px; font-weight:bold;
  }
</style>

<script>
  // Registration form interactivity
  document.getElementById('registrationForm').addEventListener('submit', function(e){
    e.preventDefault();
    const name = document.getElementById('regName').value.trim();
    const email = document.getElementById('regEmail').value.trim();
    const phone = document.getElementById('regPhone').value.trim();
    const program = document.getElementById('regProgram').value;
    const msg = document.getElementById('regMessage');

    if(name && email && phone && program){
      msg.textContent = `✅ Thank you, ${name}! You have registered for ${program}.`;
      msg.style.background = '#d4edda'; msg.style.color = '#155724';
      msg.style.display = 'block';
      this.reset();
    } else {
      msg.textContent = '❌ Please fill all fields correctly.';
      msg.style.background = '#f8d7da'; msg.style.color = '#721c24';
      msg.style.display = 'block';
    }
  });

  // Donation form interactivity
  document.getElementById('donationForm').addEventListener('submit', function(e){
    e.preventDefault();
    const name = document.getElementById('donName').value.trim();
    const email = document.getElementById('donEmail').value.trim();
    const amount = document.getElementById('donAmount').value;
    const method = document.getElementById('donMethod').value;
    const msg = document.getElementById('donMessage');

    if(name && email && amount > 0 && method){
      msg.textContent = `🙏 Thank you, ${name}! Your donation of ₹${amount} via ${method} is appreciated.`;
      msg.style.background = '#d4edda'; msg.style.color = '#155724';
      msg.style.display = 'block';
      this.reset();
    } else {
      msg.textContent = '❌ Please complete all donation details.';
      msg.style.background = '#f8d7da'; msg.style.color = '#721c24';
      msg.style.display = 'block';
    }
  });

</script>




<footer>
  <div class="footer-wrap">
    <div>
      <strong>Buddhayan Mahasangh</strong>
      <p>President: Bhante Rajratan </br>Dedicated to spreading the Buddha’s teachings with compassion and clarity.</p>
  </div>
</footer>

</body>
</html>
