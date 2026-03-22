<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vandana Fabrication - Satna</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 15px;
      border-radius: 50%;
      font-size: 20px;
    }
  </style>
</head>
<body class="bg-gray-100">

<header class="bg-black text-white p-5 text-center text-2xl font-bold">
  Vandana Fabrication (Satna)
</header>

<section class="text-center p-10 bg-yellow-400">
  <h1 class="text-4xl font-bold mb-4">Steel Welding & Fabrication Services</h1>
  <p class="text-lg">Door-to-Door Service in Satna, Madhya Pradesh</p>
  <a href="https://wa.me/919999999999?text=Hello%20I%20need%20welding%20service%20in%20Satna" class="mt-5 inline-block bg-green-500 text-white px-6 py-3 rounded-2xl">Contact on WhatsApp</a>
</section>

<section class="p-10">
  <h2 class="text-3xl font-bold text-center mb-6">Our Services</h2>
  <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
    <div class="bg-white p-5 rounded-2xl shadow">Steel Welding</div>
    <div class="bg-white p-5 rounded-2xl shadow">Fabrication Work</div>
    <div class="bg-white p-5 rounded-2xl shadow">Repair & Maintenance</div>
    <div class="bg-white p-5 rounded-2xl shadow">Custom Metal Work</div>
  </div>
</section>

<section class="p-10 bg-gray-200 text-center">
  <h2 class="text-2xl font-bold mb-4">AI Assistant</h2>
  <input id="userInput" type="text" placeholder="Ask about services..." class="p-2 w-1/2 rounded">
  <button onclick="reply()" class="bg-blue-500 text-white px-4 py-2 rounded">Ask</button>
  <p id="response" class="mt-4"></p>
</section>

<section class="p-10 text-center">
  <h2 class="text-2xl font-bold mb-4">Book a Service</h2>
  <input type="text" placeholder="Your Name" class="p-2 m-2 rounded"><br>
  <input type="text" placeholder="Phone Number" class="p-2 m-2 rounded"><br>
  <input type="text" placeholder="Service Required" class="p-2 m-2 rounded"><br>
  <button onclick="alert('Request Submitted! We will contact you soon.')" class="bg-black text-white px-5 py-2 rounded mt-3">Submit</button>
</section>

<section class="p-10 text-center">
  <h2 class="text-2xl font-bold mb-4">Our Location</h2>
  <iframe src="https://maps.google.com/maps?q=Satna%20Madhya%20Pradesh&t=&z=13&ie=UTF8&iwloc=&output=embed" width="80%" height="300"></iframe>
</section>

<footer class="bg-black text-white text-center p-5">
  Owner: Vandana Soni | Satna, Madhya Pradesh | Door-to-Door Service | WhatsApp Available
</footer>

<a href="https://wa.me/919999999999?text=Hello%20I%20need%20welding%20service%20in%20Satna" class="whatsapp-float">💬</a>

<script>
function reply() {
  let input = document.getElementById('userInput').value.toLowerCase();
  let response = "";

  if(input.includes("price")) {
    response = "Prices depend on work. Please contact us on WhatsApp.";
  } else if(input.includes("service")) {
    response = "We provide welding, fabrication, and repair services in Satna.";
  } else if(input.includes("location")) {
    response = "We provide door-to-door service in Satna, Madhya Pradesh.";
  } else {
    response = "Please contact us on WhatsApp for full details.";
  }

  document.getElementById('response').innerText = response;
}
</script>

</body>
</html>
