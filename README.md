<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Johnson Snacks - Traditional & Crispy Snacks</title>
    <!-- Tailwind CSS for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-amber-50 text-gray-800 font-sans">

    <!-- Header / Navbar -->
    <header class="bg-amber-600 text-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-cookie-bite text-2xl"></i>
                <span class="text-2xl font-bold tracking-wide">Johnson Snacks</span>
            </div>
            <nav class="hidden md:flex space-x-6 font-medium">
                <a href="#home" class="hover:text-amber-200 transition">Home</a>
                <a href="#products" class="hover:text-amber-200 transition">Our Products</a>
                <a href="#about" class="hover:text-amber-200 transition">About Us</a>
                <a href="#contact" class="hover:text-amber-200 transition">Contact</a>
            </nav>
            <a href="https://wa.me/919876543210?text=Hello%20Johnson%20Snacks,%20I%20would%20like%20to%20order%20snacks!" target="_blank" class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded-full font-medium flex items-center space-x-2 transition shadow">
                <i class="fa-brands fa-whatsapp text-lg"></i>
                <span>Order on WhatsApp</span>
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="bg-gradient-to-r from-amber-500 to-orange-600 text-white py-20 px-4 text-center">
        <div class="container mx-auto max-w-3xl">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 drop-shadow-md">Authentic & Crispy Traditional Snacks</h1>
            <p class="text-lg md:text-xl mb-8 text-amber-100">Handcrafted with premium ingredients, love, and traditional taste. Perfect for your tea-time, family gatherings, and festivals!</p>
            <a href="#products" class="bg-white text-orange-600 font-bold px-8 py-3 rounded-full shadow-lg hover:bg-amber-100 transition duration-300 text-lg">View Products & Pricing</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-16 px-4 max-w-6xl mx-auto">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold text-amber-900 mb-2">Our Special Menu</h2>
            <p class="text-gray-600">Freshly manufactured small-scale quality snacks at the best prices.</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <!-- Product 1 -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition border border-amber-200 flex flex-col justify-between">
                <div class="p-6">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-gray-900">மிச்சர் (Mixture)</h3>
                        <span class="bg-amber-100 text-amber-800 text-sm font-semibold px-3 py-1 rounded-full">1 kg</span>
                    </div>
                    <p class="text-gray-600 mb-4 text-sm">Crispy, crunchy, and perfectly spiced traditional mixture made with high-quality ingredients.</p>
                    <div class="text-2xl font-extrabold text-orange-600">₹180 <span class="text-xs text-gray-500 font-normal">/ kg</span></div>
                </div>
                <div class="px-6 pb-6">
                    <a href="https://wa.me/919876543210?text=Hi,%20I%20want%20to%20order%20Mixture%201kg%20for%20₹180" target="_blank" class="block w-full bg-amber-600 hover:bg-amber-700 text-white text-center py-2 rounded-lg font-medium transition">Order via WhatsApp</a>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition border border-amber-200 flex flex-col justify-between">
                <div class="p-6">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-gray-900">நைஸ் மிச்சர் (Nice Mixture)</h3>
                        <span class="bg-amber-100 text-amber-800 text-sm font-semibold px-3 py-1 rounded-full">1 kg</span>
                    </div>
                    <p class="text-gray-600 mb-4 text-sm">Finely textured, mouth-watering nice mixture loaded with flavor and crunch.</p>
                    <div class="text-2xl font-extrabold text-orange-600">₹200 <span class="text-xs text-gray-500 font-normal">/ kg</span></div>
                </div>
                <div class="px-6 pb-6">
                    <a href="https://wa.me/919876543210?text=Hi,%20I%20want%20to%20order%20Nice%20Mixture%201kg%20for%20₹200" target="_blank" class="block w-full bg-amber-600 hover:bg-amber-700 text-white text-center py-2 rounded-lg font-medium transition">Order via WhatsApp</a>
                </div>
            </div>

            <!-- Product 3 -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition border border-amber-200 flex flex-col justify-between">
                <div class="p-6">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-gray-900">முறுக்கு (Murukku)</h3>
                        <span class="bg-amber-100 text-amber-800 text-sm font-semibold px-3 py-1 rounded-full">1 kg</span>
                    </div>
                    <p class="text-gray-600 mb-4 text-sm">Traditional golden-brown crispy murukku prepared with authentic spices and rice flour.</p>
                    <div class="text-2xl font-extrabold text-orange-600">₹170 <span class="text-xs text-gray-500 font-normal">/ kg</span></div>
                </div>
                <div class="px-6 pb-6">
                    <a href="https://wa.me/919876543210?text=Hi,%20I%20want%20to%20order%20Murukku%201kg%20for%20₹170" target="_blank" class="block w-full bg-amber-600 hover:bg-amber-700 text-white text-center py-2 rounded-lg font-medium transition">Order via WhatsApp</a>
                </div>
            </div>

            <!-- Product 4 -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition border border-amber-200 flex flex-col justify-between">
                <div class="p-6">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-gray-900">கார பூந்தி (Kara Boondi)</h3>
                        <span class="bg-amber-100 text-amber-800 text-sm font-semibold px-3 py-1 rounded-full">1 kg</span>
                    </div>
                    <p class="text-gray-600 mb-4 text-sm">Crispy, savory fried gram flour pearls seasoned with curry leaves and spices.</p>
                    <div class="text-2xl font-extrabold text-orange-600">₹200 <span class="text-xs text-gray-500 font-normal">/ kg</span></div>
                </div>
                <div class="px-6 pb-6">
                    <a href="https://wa.me/919876543210?text=Hi,%20I%20want%20to%20order%20Kara%20Boondi%201kg%20for%20₹200" target="_blank" class="block w-full bg-amber-600 hover:bg-amber-700 text-white text-center py-2 rounded-lg font-medium transition">Order via WhatsApp</a>
                </div>
            </div>

            <!-- Product 5 -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition border border-amber-200 flex flex-col justify-between">
                <div class="p-6">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-gray-900">இனிப்பு பூந்தி (Sweet Boondi)</h3>
                        <span class="bg-amber-100 text-amber-800 text-sm font-semibold px-3 py-1 rounded-full">1 kg</span>
                    </div>
                    <p class="text-gray-600 mb-4 text-sm">Deliciously sweet, syrup-soaked boondi pearls that melt in your mouth.</p>
                    <div class="text-2xl font-extrabold text-orange-600">₹200 <span class="text-xs text-gray-500 font-normal">/ kg</span></div>
                </div>
                <div class="px-6 pb-6">
                    <a href="https://wa.me/919876543210?text=Hi,%20I%20want%20to%20order%20Sweet%20Boondi%201kg%20for%20₹200" target="_blank" class="block w-full bg-amber-600 hover:bg-amber-700 text-white text-center py-2 rounded-lg font-medium transition">Order via WhatsApp</a>
                </div>
            </div>

            <!-- Product 6 -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition border border-amber-200 flex flex-col justify-between">
                <div class="p-6">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-gray-900">மைசூர்பாக்கு (Mysore Pak)</h3>
                        <span class="bg-amber-100 text-amber-800 text-sm font-semibold px-3 py-1 rounded-full">1 kg</span>
                    </div>
                    <p class="text-gray-600 mb-4 text-sm">Rich, melt-in-the-mouth traditional sweet made with pure ghee, sugar, and gram flour.</p>
                    <div class="text-2xl font-extrabold text-orange-600">₹240 <span class="text-xs text-gray-500 font-normal">/ kg</span></div>
                </div>
                <div class="px-6 pb-6">
                    <a href="https://wa.me/919876543210?text=Hi,%20I%20want%20to%20order%20Mysore%20Pak%201kg%20for%20₹240" target="_blank" class="block w-full bg-amber-600 hover:bg-amber-700 text-white text-center py-2 rounded-lg font-medium transition">Order via WhatsApp</a>
                </div>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="bg-amber-100 py-16 px-4">
        <div class="container mx-auto max-w-4xl text-center">
            <h2 class="text-3xl font-bold text-amber-900 mb-4">About Johnson Snacks</h2>
            <p class="text-gray-700 text-lg leading-relaxed mb-6">
                Welcome to <strong>Johnson Snacks</strong>! We are a small-scale food manufacturing industry dedicated to bringing authentic, crispy, and delicious homemade-style snacks to your doorstep. We maintain strict hygiene standards and use only high-quality ingredients to ensure that every single bite gives you the authentic taste of tradition.
            </p>
        </div>
    </section>

    <!-- Contact & Footer Section -->
    <footer id="contact" class="bg-gray-900 text-white py-12 px-4">
        <div class="container mx-auto max-w-5xl grid grid-cols-1 md:grid-cols-2 gap-8 mb-8">
            <div>
                <h3 class="text-2xl font-bold mb-4 text-amber-400">Johnson Snacks</h3>
                <p class="text-gray-400 mb-2">Small Scale Food Manufacturing Industry</p>
                <p class="text-gray-400 mb-4">Tamil Nadu, India</p>
            </div>
            <div>
                <h3 class="text-xl font-bold mb-4 text-amber-400">Get in Touch</h3>
                <p class="text-gray-300 mb-2"><i class="fa-solid fa-phone mr-2 text-amber-400"></i> +91 98765 43210</p>
                <p class="text-gray-300 mb-4"><i class="fa-brands fa-whatsapp mr-2 text-green-400"></i> WhatsApp Orders Available</p>
                <a href="https://wa.me/919751662210?text=Hello%20Johnson%20Snacks," target="_blank" class="inline-block bg-green-500 hover:bg-green-600 text-white px-6 py-2 rounded-lg font-medium transition">
                    Chat with Us Now
                </a>
            </div>
        </div>
        <div class="border-t border-gray-800 text-center pt-6 text-gray-500 text-sm">
            &copy; 2026 Johnson Snacks. All rights reserved.
        </div>
    </footer>

</body>
</html>
