<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>NaijaLuxuryMassage</title>
  <meta name="description" content="Luxury erotic, Swedish, Nuru, Tantric massage, virtual girlfriend, travel companion, girlfriend experience by a beautiful curvy woman in Abuja, Douala, Yaounde, Kribi, Buea, Limbe, Africa." />
  <meta name="keywords" content="erotic massage, Swedish massage, Nuru massage, tantric massage, virtual girlfriend, travel companion, girlfriend experience, VIP massage therapist, luxury massage therapist, beautiful curvy woman, Abuja, Douala, Yaounde, Kribi, Buea, Limbe, Africa" />
  <meta name="author" content="NaijaLuxuryMassage" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    body {
      background: linear-gradient(135deg, #4B0082, #6A0DAD);
      color: #f5e6ca; /* Cream text for body */
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      min-height: 100vh;
    }

    header {
      background: linear-gradient(90deg, #FFD700, #B8860B);
      color: white; /* Changed to white for full contrast */
      padding: 25px 20px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
      border-radius: 0 0 25px 25px;
      font-weight: 700;
      white-space: nowrap; /* Prevent line wrap */
      overflow: visible; /* Prevent clipping */
    }

    header h1 {
      margin: 0;
      font-size: 2.8em; /* Larger font */
    }

    .content {
      padding: 20px;
      max-width: 900px;
      margin: auto;
      color: #f5e6ca; /* Cream text inside content */
    }

    h2, h3 {
      color: #FFD700;
      font-weight: 700;
    }

    ul {
      list-style-type: disc;
      margin-left: 25px;
      color: #FFD700;
      font-weight: 600;
      font-size: 1.1em;
    }

    li {
      margin-bottom: 10px;
    }

    .section {
      margin-bottom: 40px;
      background-color: rgba(255, 215, 0, 0.1);
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(183, 134, 11, 0.3);
      color: #f5e6ca; /* Changed to cream (white-ish) */
    }

    .cta {
      text-align: center;
      background-color: rgba(255, 215, 0, 0.15);
      padding: 20px;
      border-radius: 8px;
      margin-top: 30px;
      color: #f5e6ca; /* Cream text */
      font-weight: 600;
    }

    .hashtags {
      margin-top: 20px;
      color: #d4af37;
      font-size: 0.95em;
      text-align: center;
    }

    .connect {
      text-align: center;
      margin-top: 15px;
      font-size: 1.1em;
      color: #f5e6ca; /* Cream text */
    }

    .connect a {
      background-color: #B8860B;
      color: white !important; /* White text on gold buttons */
      padding: 8px 14px;
      border-radius: 20px;
      text-decoration: none;
      display: inline-block;
      margin: 0 6px;
      font-weight: 600;
      transition: background-color 0.3s ease;
    }

    .connect a:hover {
      background-color: #FFD700;
      color: #4B0082 !important; /* Dark purple on hover */
    }

    .connect a i {
      margin-right: 6px;
    }

    footer {
      background: linear-gradient(90deg, #B8860B, #FFD700);
      padding: 15px;
      text-align: center;
      font-size: 0.9em;
      margin-top: 30px;
      color: white;
      font-weight: 600;
    }

    #preview img,
    #preview video {
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.4);
      object-fit: cover;
    }

    #reviewForm, #bookingForm {
      background-color: rgba(255, 215, 0, 0.15);
      padding: 20px;
      border-radius: 8px;
      max-width: 600px;
      margin: 30px auto;
      color: #f5e6ca; /* Cream text */
    }

    #reviewForm input, #reviewForm select, #reviewForm textarea,
    #bookingForm input, #bookingForm select, #bookingForm textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border-radius: 6px;
      border: 1px solid #B8860B;
      font-size: 1em;
      box-sizing: border-box;
      background-color: #fff8dc;
      color: #4B0082;
    }

    #reviewForm button, #bookingForm button {
      background-color: #B8860B;
      color: #4B0082;
      border: none;
      cursor: pointer;
      font-weight: 700;
      transition: background-color 0.3s ease;
      width: 100%;
      padding: 10px;
      margin-top: 15px;
      border-radius: 6px;
      box-shadow: 0 3px 6px rgba(184, 134, 11, 0.6);
    }

    #reviewForm button:hover, #bookingForm button:hover {
      background-color: #FFD700;
      color: #3e1e68;
    }

    #reviewsList {
      max-width: 600px;
      margin: 20px auto 40px auto;
      padding: 10px;
      background-color: rgba(255, 215, 0, 0.10);
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(184, 134, 11, 0.3);
      color: #f5e6ca; /* Cream text */
    }

    .review {
      margin-bottom: 20px;
      border-bottom: 1px solid #B8860B;
      padding-bottom: 10px;
    }

    .review:last-child {
      border-bottom: none;
    }

    .review strong {
      color: #B8860B;
      font-size: 1.1em;
    }

    .review em {
      display: block;
      margin-top: 5px;
      font-style: normal;
      color: #d4af37; /* Goldish for emphasis */
    }

    .review .rating {
      color: #B8860B;
      font-weight: bold;
    }

    #error, #bookingError {
      color: #ff4444;
      font-weight: 700;
      margin-top: 10px;
    }

    #success, #bookingSuccess {
      color: #00cc66;
      font-weight: 700;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>NAIJALUXURYMASSAGE</h1>
    <p>Hello Sweetheart! 💕</p>
    <p><strong>WhatsApp/SMS Preferred — Always Responded To Promptly</strong></p>
  </header>

  <div class="content">
    <!-- Introduction Section -->
    <div class="section" id="intro-section">
      <h2>HELLO SWEETHEART! 💕</h2>
      <p>(WhatsApp messages and SMS are always attended to promptly and are the preferred way to reach me.)</p>
      <p><strong>NaijaLuxuryMassage</strong> is a professional and certified massage therapist originally based in <strong>Abuja, Nigeria</strong>, and currently available in <strong>Douala, Cameroon</strong>. With over <strong>5 years of experience</strong>, I specialize in providing deeply relaxing, tension-relieving therapeutic massages that help you unwind and rejuvenate.</p>
      <p>💆‍♀️ All the pictures you see are real and mine — I look exactly the same in person.<br />
      💖 I’m friendly, open-minded, professional, elegant, and very discreet.</p>
      <h3>My massage services include:</h3>
      <ul>
        <li>Swedish Massage</li>
        <li>Nuru / Erotic Massage</li>
        <li>Tantric Massage</li>
        <li>Deep Tissue Massage</li>
      </ul>
      <p>Whether you just got off a long flight or had a stressful day at work, I’m here to help you relax and feel good again. I’m also available as a travel companion — graceful, curvy, kind, and always gentle. I’ll be by your side to keep you warm, entertained, and deeply cared for.</p>
      <h3>As your travel or GFE (girlfriend experience) companion, I offer:</h3>
      <ul>
        <li>💋 Unlimited cuddles, intimacy, deep affection, and sweet bonding — all in a safe, clean, and respectful way.</li>
        <li>🌍 Willing to travel to any location with a valid passport — just book me in advance.</li>
        <li>💫 Full discretion and confidentiality guaranteed.</li>
      </ul>
      <hr style="margin: 20px 0; border: none; border-top: 1px dashed #B8860B;" />
      <h3>💌 VIRTUAL GIRLFRIEND EXPERIENCE</h3>
      <p>Even if we’re miles apart, I can still be by your side — virtually! As your virtual girlfriend, I’m available 24/7 to:</p>
      <ul>
        <li>Send you sweet good morning and good night messages</li>
        <li>Be your daily source of affection, romance, and support</li>
        <li>Video call or chat to keep you company</li>
        <li>Send you personalized pictures, voice notes, and loving updates</li>
        <li>Cheer you up when you’re down and celebrate your wins</li>
        <li>Be the gentle, sensual, loving partner you need — anytime, anywhere 💞</li>
      </ul>
      <p>Whether you’re looking for emotional connection, playful conversations, or intimate companionship — virtually or in person — I’m here to give you an unforgettable, satisfying experience.</p>
      <hr style="margin: 20px 0; border: none; border-top: 1px dashed #B8860B;" />
      <p>📲 <strong>Book now via WhatsApp or SMS.</strong><br />
      🧳 <strong>Available to travel outside Douala — just ask!</strong><br />
      🎟️ <strong>Advance bookings encouraged.</strong><br />
      ✨ <strong>With me, your satisfaction is always 100% guaranteed.</strong></p>
      <div class="hashtags">
        #VIPMassageTherapist #NuruMassage #DeepTissueMassage #TantricMassage #GirlfriendExperience #ElegantNigerianInDouala #CertifiedMassageTherapist #TravelCompanion #MassageTherapistDouala #AbujaToTheWorld #BeTreatedLikeAKing #VirtualGFE
      </div>
    </div>

    <!-- Pricing Section -->
    <div class="section" id="pricing-section">
      <h2>Our Services & Prices</h2>
      <ul>
        <li><strong>Nuru / Erotic Massage:</strong> $130</li>
        <li><strong>Deep Tissue Massage:</strong> $90</li>
        <li><strong>Travel Companion Booking:</strong> $300</li>
        <li><strong>Virtual Girlfriend Booking:</strong> $65</li>
      </ul>
    </div>

    <!-- Booking Form -->
    <div class="section" id="booking-section">
      <h2>Book Your Experience</h2>
      <form id="bookingForm">
        <select name="service" id="service" required>
          <option value="" disabled selected>Select a service</option>
          <option value="Nuru / Erotic Massage">$130 - Nuru / Erotic Massage</option>
          <option value="Deep Tissue Massage">$90 - Deep Tissue Massage</option>
          <option value="Travel Companion Booking">$300 - Travel Companion Booking</option>
          <option value="Virtual Girlfriend Booking">$65 - Virtual Girlfriend Booking</option>
        </select>
        <input type="text" name="name" id="bookingName" placeholder="Your name" required />
        <input type="tel" name="phone" id="bookingPhone" placeholder="Phone or WhatsApp number" required />
        <input type="date" name="date" id="bookingDate" required />
        <textarea name="message" id="bookingMessage" placeholder="Additional details or requests (optional)"></textarea>
        <button type="submit">Submit Booking</button>
        <p id="bookingError"></p>
        <p id="bookingSuccess"></p>
      </form>
    </div>

    <!-- Upload Interface -->
    <div class="section" id="upload-section">
      <h2>Upload Photos & Videos</h2>
      <p>Select images or videos to preview before uploading.</p>
      <form id="uploadForm" action="/upload" method="POST" enctype="multipart/form-data">
        <input type="file" id="mediaInput" name="mediaFiles" accept="image/*,video/*" multiple />
        <div id="preview" style="margin-top: 15px; display: flex; flex-wrap: wrap; gap: 15px;"></div>
        <button type="submit" style="margin-top: 20px;">Submit</button>
      </form>
    </div>

    <!-- Reviews Section -->
    <div class="section" id="reviews-section">
      <h2>Reviews</h2>
      <form id="reviewForm">
        <input type="text" name="name" id="name" placeholder="Your name" required />
        <select name="rating" id="rating" required>
          <option value="" disabled selected>Rate (4 or 5 stars only)</option>
          <option value="5">⭐⭐⭐⭐⭐ - Excellent</option>
          <option value="4">⭐⭐⭐⭐ - Very Good</option>
        </select>
        <textarea name="comment" id="comment" placeholder="Your review..." required></textarea>
        <button type="submit">Submit Review</button>
        <p id="error"></p>
        <p id="success"></p>
      </form>

      <div id="reviewsList">
        <!-- Dynamic reviews will be displayed here -->
      </div>
    </div>

    <!-- Call to Action -->
    <div class="cta">
      <p>💌 Ready to relax, connect, and feel adored? Contact me on <a href="https://wa.me/237680543051" target="_blank" style="color:#4B0082; font-weight:700;">WhatsApp</a> or SMS to book your experience today. I'm waiting for you, sweetheart. 💖</p>
      <p><strong>📞 <a href="https://wa.me/237680543051" target="_blank" style="color:#4B0082; font-weight:700;">+237 680 543 051</a></strong></p>
    </div>

    <!-- Social Links -->
    <div class="connect">
      Connect with me:
      <a href="https://wa.me/237680543051" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
      <a href="https://www.instagram.com/naijaluxurymassage" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
      <a href="https://twitter.com/wealthywinning4" target="_blank"><i class="fab fa-twitter"></i> Twitter</a>
      <a href="https://www.facebook.com/profile.php?id=61575164341805&mibextid=rS40aB7S9Ucbxw6v" target="_blank"><i class="fab fa-facebook-f"></i> Facebook</a>
      <a href="https://t.me/NaijaLuxuryMassage" target="_blank"><i class="fab fa-telegram-plane"></i> Telegram</a>
    </div>
  </div>

  <footer>
    &copy; 2025 NaijaLuxuryMassage. All rights reserved.
  </footer>

  <!-- JavaScript -->
  <script>
    // Upload preview
    const mediaInput = document.getElementById('mediaInput');
    const preview = document.getElementById('preview');

    mediaInput.addEventListener('change', () => {
      preview.innerHTML = '';
      const files = mediaInput.files;
      if (files.length === 0) return;

      Array.from(files).forEach(file => {
        const fileType = file.type;
        if (fileType.startsWith('image/')) {
          const img = document.createElement('img');
          img.src = URL.createObjectURL(file);
          img.style.width = '120px';
          img.style.height = '120px';
          preview.appendChild(img);
        } else if (fileType.startsWith('video/')) {
          const video = document.createElement('video');
          video.src = URL.createObjectURL(file);
          video.controls = true;
          video.style.width = '160px';
          video.style.height = '120px';
          preview.appendChild(video);
        }
      });
    });

    // Reviews handling
