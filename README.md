<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AquaSense AI | Smart Irrigation Philippines</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .hero-gradient { background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1625246333195-78d9c38ad449?auto=format&fit=crop&q=80&w=1920'); background-size: cover; background-position: center; }
        .accent-green { color: #2D6A4F; }
        .bg-accent-green { background-color: #2D6A4F; }
    </style>
</head>
<body class="font-sans text-gray-800 bg-gray-50">

    <nav class="flex items-center justify-between px-8 py-4 bg-white shadow-md sticky top-0 z-50">
        <div class="text-2xl font-bold accent-green tracking-tighter">AQUASENSE AI</div>
        <div class="hidden md:flex space-x-8 font-medium">
            <a href="#problem" class="hover:text-green-600">Solution</a>
            <a href="#how-it-works" class="hover:text-green-600">Process</a>
            <a href="#dashboard" class="hover:text-green-600">Product</a>
            <a href="#pricing" class="hover:text-green-600">Pricing</a>
        </div>
        <button class="bg-accent-green text-white px-6 py-2 rounded-full font-semibold hover:bg-green-800 transition">Get Demo</button>
    </nav>

    <header class="hero-gradient h-[80vh] flex items-center justify-center text-center text-white px-4">
        <div class="max-w-4xl">
            <h1 class="text-5xl md:text-7xl font-extrabold mb-6">The Future of Farming is <span class="text-green-400">Data-Driven.</span></h1>
            <p class="text-xl md:text-2xl mb-10 text-gray-200">Stop guessing, start growing. Optimize irrigation, reduce waste by 35%, and increase yields with AI-powered analytics.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#" class="bg-accent-green px-8 py-4 rounded-lg text-lg font-bold hover:scale-105 transition-transform">Get a Free Demo</a>
                <a href="#" class="bg-white/10 backdrop-blur-md border border-white/30 px-8 py-4 rounded-lg text-lg font-bold hover:bg-white/20 transition">Watch How It Works</a>
            </div>
        </div>
    </header>

    <section id="problem" class="py-20 px-8 max-w-6xl mx-auto">
        <div class="grid md:grid-cols-2 gap-12 items-center">
            <div class="bg-red-50 p-8 border-l-4 border-red-500 rounded-r-lg">
                <h3 class="text-red-600 font-bold uppercase tracking-widest mb-2 italic">The Conflict</h3>
                <h2 class="text-3xl font-bold mb-4 text-gray-900">Legacy irrigation is "Schedule-Based"</h2>
                <p class="text-gray-600 leading-relaxed">Whether it rains or shines, your pumps run—wasting thousands of liters and leaching vital nutrients from your Philippine soil.</p>
            </div>
            <div class="bg-green-50 p-8 border-l-4 border-green-500 rounded-r-lg">
                <h3 class="text-green-600 font-bold uppercase tracking-widest mb-2 italic">The Resolution</h3>
                <h2 class="text-3xl font-bold mb-4 text-gray-900">AquaSense is "Need-Based"</h2>
                <p class="text-gray-600 leading-relaxed">Our sensors tell you exactly when and where your crops need water, sent straight to your smartphone in real-time.</p>
            </div>
        </div>
    </section>

    <section id="how-it-works" class="bg-white py-20 px-8">
        <div class="max-w-6xl mx-auto text-center mb-16">
            <h2 class="text-4xl font-bold mb-4">The Process</h2>
            <div class="h-1 w-20 bg-accent-green mx-auto"></div>
        </div>
        <div class="grid md:grid-cols-3 gap-12 max-w-6xl mx-auto">
            <div class="text-center">
                <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                    <i class="fa-solid fa-microchip text-2xl accent-green"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">1. Smart Deployment</h3>
                <p class="text-gray-600">Install ultra-low power LoRaWAN sensors across your acreage. Setup takes < 30 mins.</p>
            </div>
            <div class="text-center">
                <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                    <i class="fa-solid fa-cloud-bolt text-2xl accent-green"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">2. Cloud Intelligence</h3>
                <p class="text-gray-600">"Deep-Root" AI analyzes moisture, nitrogen, and localized weather patterns 24/7.</p>
            </div>
            <div class="text-center">
                <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                    <i class="fa-solid fa-mobile-screen text-2xl accent-green"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">3. Precision Action</h3>
                <p class="text-gray-600">Receive alerts or set "Auto-Pilot" to optimize water delivery automatically.</p>
            </div>
        </div>
    </section>

    <section id="dashboard" class="py-20 px-8 bg-gray-900 text-white overflow-hidden">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold mb-12">Actionable Insights</h2>
            <div class="grid md:grid-cols-2 gap-16 items-center">
                <div class="space-y-8">
                    <div class="flex gap-4">
                        <div class="text-green-400 text-2xl"><i class="fa-solid fa-map-location-dot"></i></div>
                        <div>
                            <h4 class="font-bold text-xl">Real-Time Soil Mapping</h4>
                            <p class="text-gray-400">See a high-resolution heat map of your farm’s hydration levels.</p>
                        </div>
                    </div>
                    <div class="flex gap-4">
                        <div class="text-green-400 text-2xl"><i class="fa-solid fa-triangle-exclamation"></i></div>
                        <div>
                            <h4 class="font-bold text-xl">Predictive Stress Alerts</h4>
                            <p class="text-gray-400">Our AI predicts wilting 48 hours before it happens.</p>
                        </div>
                    </div>
                    <div class="flex gap-4">
                        <div class="text-green-400 text-2xl"><i class="fa-solid fa-chart-line"></i></div>
                        <div>
                            <h4 class="font-bold text-xl">Historical Data</h4>
                            <p class="text-gray-400">Compare seasons to optimize your long-term fertilizer and water strategy.</p>
                        </div>
                    </div>
                </div>
                <div class="relative">
                    <div class="bg-gray-800 rounded-xl p-4 shadow-2xl border border-gray-700">
                        <div class="h-64 bg-green-900/20 rounded flex items-center justify-center italic text-gray-500 border-2 border-dashed border-gray-700">
                           [Interactive Dashboard Visualization]
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="pricing" class="py-20 px-8">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12">Investment Plans</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-white p-10 rounded-2xl shadow-lg border-2 border-green-100 hover:border-green-500 transition">
                    <h3 class="text-2xl font-bold mb-2">Starter Kit</h3>
                    <div class="text-4xl font-black accent-green mb-6">₱11,200 <span class="text-sm text-gray-500 font-normal">Setup Fee</span></div>
                    <ul class="space-y-4 mb-8">
                        <li><i class="fa-solid fa-check text-green-500 mr-2"></i> 1 Gateway + 3 Soil Sensors</li>
                        <li><i class="fa-solid fa-check text-green-500 mr-2"></i> Mobile App Access</li>
                        <li><i class="fa-solid fa-check text-green-500 mr-2"></i> 24/7 Monitoring</li>
                        <li class="font-bold accent-green italic">₱2,800 / month</li>
                    </ul>
                    <button class="w-full py-4 border-2 border-green-700 rounded-lg font-bold hover:bg-green-50 accent-green">Inquire Now</button>
                </div>
                <div class="bg-gray-900 p-10 rounded-2xl shadow-lg text-white relative overflow-hidden">
                    <div class="absolute top-0 right-0 bg-green-500 text-white text-xs font-bold px-4 py-1 rounded-bl-lg">SCALABLE</div>
                    <h3 class="text-2xl font-bold mb-2 text-green-400">Enterprise</h3>
                    <div class="text-4xl font-black mb-6">Custom Quote</div>
                    <ul class="space-y-4 mb-8 text-gray-300">
                        <li><i class="fa-solid fa-check text-green-400 mr-2"></i> Unlimited Sensors</li>
                        <li><i class="fa-solid fa-check text-green-400 mr-2"></i> Full ERP Integration</li>
                        <li><i class="fa-solid fa-check text-green-400 mr-2"></i> On-site Tech Support</li>
                        <li><i class="fa-solid fa-check text-green-400 mr-2"></i> Annual Licensing</li>
                    </ul>
                    <button class="w-full py-4 bg-accent-green rounded-lg font-bold hover:bg-green-700 transition">Contact Sales</button>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-white border-t border-gray-200 py-12 px-8">
        <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-12">
            <div>
                <h4 class="font-bold text-xl mb-4 accent-green">AQUASENSE AI</h4>
                <p class="text-gray-500">Technopreneurship Project</p>
                <p class="text-gray-500 italic mt-2 text-sm">Empowering Filipino farmers through precision agriculture.</p>
            </div>
            <div>
                <h4 class="font-bold mb-4">Quick Links</h4>
                <div class="flex flex-col space-y-2 text-gray-600">
                    <a href="#">About Us</a>
                    <a href="#">Privacy Policy</a>
                    <a href="#">DTI Documentation</a>
                </div>
            </div>
            <div>
                <h4 class="font-bold mb-4">Contact</h4>
                <p class="text-gray-600">tech-support@aquasense.ai</p>
                <p class="text-gray-600">+63 9XX XXX XXXX</p>
                <div class="mt-4 flex gap-4 text-2xl text-blue-600">
                    <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                </div>
            </div>
        </div>
        <div class="text-center mt-12 pt-8 border-t border-gray-100 text-gray-400 text-sm">
            © 2026 AquaSense AI. All Rights Reserved.
        </div>
    </footer>

</body>
</html>
