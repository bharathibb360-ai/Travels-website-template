<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mugil Travels | Force Urbania Rental | ₹33/KM | Luxurious Journey, Affordable Price</title>
  <meta name="description" content="Mugil Travels - குறைந்த பணத்தில் நிறைவான பயணம். Book Force Urbania luxury tourist van at just ₹33/KM with Fuel, Driver Bata, Toll & Rent included. Call +91 994 2222 824.">
  
  <!-- Open Graph / Social Sharing -->
  <meta property="og:title" content="Mugil Travels | Force Urbania Rental | ₹33/KM">
  <meta property="og:description" content="குறைந்த பணத்தில் நிறைவான பயணம். குடும்பமாகவும், நண்பர்களுடனும் சிறந்த பயண அனுபவம்! Force Urbania luxury van rental.">
  <meta property="og:image" content="mugil-travels-poster.jpg">
  <meta property="og:type" content="website">

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800;900&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  
  <!-- Tailwind CSS via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              blue: '#1E40AF',
              blueDark: '#0E1726',
              blueNavy: '#172554',
              orange: '#F97316',
              orangeDark: '#EA580C',
              red: '#DC2626',
              dark: '#0F172A',
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            display: ['Plus Jakarta Sans', 'sans-serif'],
          }
        }
      }
    }
  </script>

  <style>
    body { font-family: 'Inter', sans-serif; }
    h1, h2, h3, h4, .font-display { font-family: 'Plus Jakarta Sans', sans-serif; }
    
    .gradient-royal {
      background: linear-gradient(135deg, #0A1128 0%, #172554 45%, #1E40AF 100%);
    }
    .gradient-poster-banner {
      background: linear-gradient(90deg, #172554 0%, #1E40AF 60%, #0F172A 100%);
    }
    .gradient-orange {
      background: linear-gradient(135deg, #F97316 0%, #EA580C 100%);
    }
    .glass-card {
      background: rgba(255, 255, 255, 0.09);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border: 1px solid rgba(255, 255, 255, 0.18);
    }
    .tab-content { display: none; }
    .tab-content.active { display: block; }
    
    /* Custom Scrollbar */
    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-track { background: #F1F5F9; }
    ::-webkit-scrollbar-thumb { background: #94A3B8; border-radius: 4px; }
    ::-webkit-scrollbar-thumb:hover { background: #64748B; }

    /* Modal Animation */
    .poster-modal { transition: opacity 0.25s ease; }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-orange-500/20 selection:text-orange-700">

  <!-- TOP ANNOUNCEMENT BAR -->
  <div class="bg-slate-950 text-white text-xs py-2.5 px-4 border-b border-blue-900/60">
    <div class="max-w-7xl mx-auto flex items-center justify-between">
      <div class="flex items-center gap-2">
        <span class="bg-red-600 text-white text-[10px] font-black uppercase px-2 py-0.5 rounded tracking-wider shadow-sm">Official Offer</span>
        <span class="text-blue-100 hidden sm:inline">குறைந்த பணத்தில் நிறைவான பயணம் · Force Urbania at <strong class="text-amber-400 font-black">₹33/KM</strong> (Fuel + Driver Bata + Toll + Rent Included)</span>
        <span class="text-blue-100 sm:hidden">Force Urbania @ <strong class="text-amber-400 font-black">₹33/KM All-Inclusive</strong></span>
      </div>
      <div class="flex items-center gap-3 text-xs font-semibold">
        <button onclick="openPosterModal()" class="text-amber-300 hover:text-white underline text-[11px] hidden md:inline-block">
          🖼️ View Official Poster
        </button>
        <a href="tel:+919942222824" class="flex items-center gap-1.5 text-white hover:text-amber-300 transition">
          <svg class="w-3.5 h-3.5 text-brand-orange" fill="currentColor" viewBox="0 0 24 24"><path d="M6.62 10.79a15.053 15.053 0 006.59 6.59l2.2-2.2a1 1 0 011.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 011 1V20a1 1 0 01-1 1A17 17 0 013 4a1 1 0 011-1h3.5a1 1 0 011 1c0 1.25.2 2.46.57 3.58a1 1 0 01-.24 1.01l-2.21 2.2z"/></svg>
          <span class="font-bold">+91 994 2222 824</span>
        </a>
      </div>
    </div>
  </div>

  <!-- NAVIGATION HEADER WITH OFFICIAL LOGO -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
      
      <!-- Brand Logo From Poster -->
      <a href="javascript:void(0)" onclick="switchTab('home')" class="flex items-center gap-3 group">
        <div class="bg-white p-1 rounded-xl shadow-sm border border-slate-100 group-hover:shadow-md transition">
          <img src="logo.png" alt="Mugil Travels Logo" class="h-12 w-auto object-contain" onerror="this.onerror=null; this.src='public/logo.png'">
        </div>
      </a>

      <!-- Desktop Nav Menu -->
      <nav class="hidden lg:flex items-center gap-1">
        <button onclick="switchTab('home')" class="nav-btn px-4 py-2 rounded-xl text-sm font-semibold transition text-brand-blue bg-blue-50" data-tab="home">Home</button>
        <button onclick="switchTab('about')" class="nav-btn px-4 py-2 rounded-xl text-sm font-semibold transition text-slate-600 hover:text-brand-blue hover:bg-slate-100" data-tab="about">About Us</button>
        <button onclick="switchTab('vehicle')" class="nav-btn px-4 py-2 rounded-xl text-sm font-semibold transition text-slate-600 hover:text-brand-blue hover:bg-slate-100" data-tab="vehicle">Our Vehicle</button>
        <button onclick="switchTab('services')" class="nav-btn px-4 py-2 rounded-xl text-sm font-semibold transition text-slate-600 hover:text-brand-blue hover:bg-slate-100" data-tab="services">Services</button>
        <button onclick="switchTab('blog')" class="nav-btn px-4 py-2 rounded-xl text-sm font-semibold transition text-slate-600 hover:text-brand-blue hover:bg-slate-100" data-tab="blog">Blog</button>
        <button onclick="switchTab('contact')" class="nav-btn px-4 py-2 rounded-xl text-sm font-semibold transition text-slate-600 hover:text-brand-blue hover:bg-slate-100" data-tab="contact">Contact</button>
        <button onclick="switchTab('admin')" class="nav-btn px-3 py-2 rounded-xl text-xs font-semibold transition text-slate-400 hover:text-slate-700 hover:bg-slate-100 ml-1" data-tab="admin">🔐 Admin</button>
      </nav>

      <!-- Action Button -->
      <div class="hidden sm:flex items-center gap-3">
        <button onclick="switchTab('booking')" class="bg-brand-orange hover:bg-brand-orangeDark text-white font-bold px-5 py-2.5 rounded-xl text-sm shadow-md hover:shadow-orange-500/25 transition-all flex items-center gap-2">
          <span>Book Your Trip</span>
          <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2.5" d="M14 5l7 7m0 0l-7 7m7-7H3"/></svg>
        </button>
      </div>

      <!-- Mobile Menu Toggle Button -->
      <button onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-lg text-slate-600 hover:bg-slate-100">
        <svg id="menuIcon" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
      </button>
    </div>

    <!-- Mobile Drawer -->
    <div id="mobileMenu" class="hidden lg:hidden border-t border-slate-200 bg-white px-4 py-5 space-y-2 shadow-xl">
      <button onclick="switchTab('home')" class="w-full text-left px-4 py-2.5 rounded-xl font-semibold text-slate-700 hover:bg-blue-50 hover:text-brand-blue">Home</button>
      <button onclick="switchTab('about')" class="w-full text-left px-4 py-2.5 rounded-xl font-semibold text-slate-700 hover:bg-blue-50 hover:text-brand-blue">About Us</button>
      <button onclick="switchTab('vehicle')" class="w-full text-left px-4 py-2.5 rounded-xl font-semibold text-slate-700 hover:bg-blue-50 hover:text-brand-blue">Our Vehicle (Force Urbania)</button>
      <button onclick="switchTab('services')" class="w-full text-left px-4 py-2.5 rounded-xl font-semibold text-slate-700 hover:bg-blue-50 hover:text-brand-blue">Services</button>
      <button onclick="switchTab('blog')" class="w-full text-left px-4 py-2.5 rounded-xl font-semibold text-slate-700 hover:bg-blue-50 hover:text-brand-blue">Blog</button>
      <button onclick="switchTab('contact')" class="w-full text-left px-4 py-2.5 rounded-xl font-semibold text-slate-700 hover:bg-blue-50 hover:text-brand-blue">Contact</button>
      <button onclick="switchTab('admin')" class="w-full text-left px-4 py-2.5 rounded-xl font-semibold text-slate-400 hover:bg-slate-50">🔐 Admin Portal</button>
      <div class="pt-2">
        <button onclick="switchTab('booking')" class="w-full bg-brand-orange text-white font-bold py-3 rounded-xl text-center shadow-md">
          Book Your Trip Now
        </button>
      </div>
    </div>
  </header>

  <!-- ========================================================================= -->
  <!-- TAB 1: HOME PAGE -->
  <!-- ========================================================================= -->
  <main id="tab-home" class="tab-content active">
    
    <!-- HERO SECTION WITH OFFICIAL POSTER ELEMENTS -->
    <section class="gradient-royal text-white py-14 sm:py-20 relative overflow-hidden">
      <!-- Ambient light glow -->
      <div class="absolute -top-24 -left-24 w-96 h-96 bg-blue-600/20 rounded-full blur-3xl pointer-events-none"></div>
      <div class="absolute bottom-0 right-0 w-96 h-96 bg-brand-orange/15 rounded-full blur-3xl pointer-events-none"></div>

      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 lg:gap-8 items-center">
          
          <!-- Left Column: Poster Headlines & CTAs -->
          <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
            
            <!-- Poster Logo Badge on Mobile -->
            <div class="inline-flex items-center gap-2 bg-white px-3 py-1.5 rounded-full shadow-md">
              <img src="logo.png" alt="Mugil Travels" class="h-6 w-auto" onerror="this.onerror=null; this.src='public/logo.png'">
              <span class="text-xs font-bold text-slate-800 tracking-wide uppercase">Force Urbania Rental</span>
            </div>

            <!-- Tamil Main Headline From Poster -->
            <h1 class="font-display font-black tracking-tight leading-tight">
              <span class="block text-2xl sm:text-3xl lg:text-4xl text-blue-200 drop-shadow">குறைந்த பணத்தில்</span>
              <span class="block text-4xl sm:text-6xl lg:text-7xl text-transparent bg-clip-text bg-gradient-to-r from-red-500 via-orange-400 to-amber-300 font-extrabold my-1 drop-shadow-md">
                நிறைவான பயணம்.
              </span>
              <span class="block text-base sm:text-xl font-bold text-orange-200 mt-2">
                குடும்பமாகவும், நண்பர்களுடனும் சிறந்த பயண அனுபவம்!
              </span>
            </h1>

            <!-- English Supporting Text -->
            <p class="text-sm sm:text-base text-blue-100 max-w-2xl mx-auto lg:mx-0 leading-relaxed font-normal">
              Enjoy a luxurious journey at an affordable price with <strong>Mugil Travels</strong>. Experience world-class road comfort in our flagship <strong>Force Urbania</strong> luxury tourist van for outstation tours, temple circuits, and family celebrations across South India.
            </p>

            <!-- Advertised Inclusions Pill (Matching Poster Colors) -->
            <div class="bg-white/10 glass-card rounded-2xl p-4 max-w-xl mx-auto lg:mx-0">
              <div class="flex items-center justify-between mb-2 pb-1 border-b border-white/10">
                <span class="text-xs uppercase font-extrabold text-amber-300 tracking-wider">₹33 Per KM All-Inclusive Rate</span>
                <span class="text-[11px] text-blue-200 font-semibold">As Advertised</span>
              </div>
              <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 text-xs font-bold text-white">
                <span class="flex items-center gap-1.5 bg-blue-600/40 px-2.5 py-1.5 rounded-lg border border-blue-400/30">
                  <span class="w-5 h-5 rounded-full bg-blue-600 flex items-center justify-center text-[11px]">⛽</span> Fuel
                </span>
                <span class="flex items-center gap-1.5 bg-red-600/40 px-2.5 py-1.5 rounded-lg border border-red-400/30">
                  <span class="w-5 h-5 rounded-full bg-red-600 flex items-center justify-center text-[11px]">👤</span> Driver Bata
                </span>
                <span class="flex items-center gap-1.5 bg-green-600/40 px-2.5 py-1.5 rounded-lg border border-green-400/30">
                  <span class="w-5 h-5 rounded-full bg-green-600 flex items-center justify-center text-[11px]">🛣️</span> Toll
                </span>
                <span class="flex items-center gap-1.5 bg-orange-600/40 px-2.5 py-1.5 rounded-lg border border-orange-400/30">
                  <span class="w-5 h-5 rounded-full bg-orange-500 flex items-center justify-center text-[11px]">₹</span> Rent
                </span>
              </div>
            </div>

            <!-- CTA Buttons Matching Poster -->
            <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-1">
              <button onclick="switchTab('booking')" class="w-full sm:w-auto bg-brand-orange hover:bg-brand-orangeDark text-white font-black px-8 py-4 rounded-xl text-base shadow-xl hover:shadow-orange-500/30 transition-all flex items-center justify-center gap-2">
                <span>Book Your Trip</span>
                <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2.5" d="M14 5l7 7m0 0l-7 7m7-7H3"/></svg>
              </button>

              <a href="tel:+919942222824" class="w-full sm:w-auto bg-white hover:bg-slate-100 text-brand-blue font-black px-7 py-4 rounded-xl text-base shadow-xl transition-all flex items-center justify-center gap-2">
                <svg class="w-5 h-5 text-brand-orange" fill="currentColor" viewBox="0 0 24 24"><path d="M6.62 10.79a15.053 15.053 0 006.59 6.59l2.2-2.2a1 1 0 011.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 011 1V20a1 1 0 01-1 1A17 17 0 013 4a1 1 0 011-1h3.5a1 1 0 011 1c0 1.25.2 2.46.57 3.58a1 1 0 01-.24 1.01l-2.21 2.2z"/></svg>
                <span>Call +91 994 2222 824</span>
              </a>
            </div>
          </div>

          <!-- Right Column: REAL FORCE URBANIA VEHICLE PHOTO FROM POSTER -->
          <div class="lg:col-span-5">
            <div class="relative group">
              
              <!-- Real Force Urbania Vehicle Card -->
              <div class="bg-white rounded-3xl p-3 shadow-2xl border border-white/20 overflow-hidden transform group-hover:scale-[1.01] transition-transform duration-300">
                <div class="relative overflow-hidden rounded-2xl">
                  <img src="urbania-van.jpg" alt="Force Urbania - Mugil Travels Luxury Van" class="w-full h-auto object-cover rounded-2xl shadow-inner" onerror="this.onerror=null; this.src='public/urbania-van.jpg'">
                  
                  <!-- Tagline Overlay Badge -->
                  <div class="absolute top-3 left-3 bg-brand-blueDark/80 backdrop-blur text-white text-[11px] font-bold px-3 py-1 rounded-full uppercase tracking-wider border border-white/20">
                    Force Urbania Luxury Van
                  </div>

                  <!-- Rate Badge Overlay -->
                  <div class="absolute bottom-3 right-3 bg-brand-orange text-white text-xs font-black px-3.5 py-1.5 rounded-xl shadow-lg uppercase tracking-wider">
                    ₹33 / KM
                  </div>
                </div>

                <!-- Vehicle Info Banner -->
                <div class="p-4 bg-slate-50 rounded-xl mt-3 flex items-center justify-between">
                  <div>
                    <h3 class="font-bold text-slate-900 text-sm">Force Urbania · Luxury Fleet</h3>
                    <p class="text-xs text-slate-500">Chauffeur Driven · Recliners · Dual AC</p>
                  </div>
                  <button onclick="openPosterModal()" class="text-xs font-bold text-brand-blue hover:text-brand-orange bg-blue-50 hover:bg-blue-100 px-3 py-1.5 rounded-lg transition border border-blue-200">
                    View Poster 🖼️
                  </button>
                </div>
              </div>

              <!-- Floating Pricing Badge Image from Poster -->
              <div class="hidden sm:block absolute -bottom-6 -left-6 w-36 shadow-2xl rounded-2xl overflow-hidden border-2 border-white transform hover:scale-105 transition cursor-pointer" onclick="openPosterModal()" title="Click to view full poster">
                <img src="pricing-badge.png" alt="₹33 per km include fuel driver bata toll rent" class="w-full h-auto" onerror="this.onerror=null; this.src='public/pricing-badge.png'">
              </div>

            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- WHY CHOOSE MUGIL TRAVELS -->
    <section class="py-16 sm:py-24 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="text-center max-w-3xl mx-auto mb-16 space-y-3">
          <span class="text-xs font-bold text-brand-orange uppercase tracking-widest px-3 py-1 bg-orange-50 rounded-full inline-block">The Mugil Travels Standard</span>
          <h2 class="text-3xl sm:text-4xl font-black font-display text-slate-900 tracking-tight">Why Choose Mugil Travels</h2>
          <p class="text-slate-600 text-sm sm:text-base leading-relaxed">
            We provide luxurious, dependable, and budget-friendly road transportation backed by uncompromised vehicle maintenance and experienced drivers.
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
          
          <!-- Card 1 -->
          <div class="bg-slate-50 hover:bg-white p-7 rounded-2xl border border-slate-200 hover:border-brand-blue/30 hover:shadow-xl transition-all duration-300 group">
            <div class="w-14 h-14 rounded-2xl bg-orange-100 text-brand-orange flex items-center justify-center text-2xl font-black mb-5 group-hover:scale-110 transition-transform">
              ₹
            </div>
            <h3 class="text-lg font-bold text-slate-900 mb-2">Affordable Pricing</h3>
            <p class="text-xs font-semibold text-brand-orange uppercase tracking-wider mb-2">Flat ₹33 / KM</p>
            <p class="text-slate-600 text-sm leading-relaxed">
              Premium travel doesn't need to be expensive. Our clear rate of ₹33 per kilometer ensures you get five-star comfort within your budget.
            </p>
          </div>

          <!-- Card 2 -->
          <div class="bg-slate-50 hover:bg-white p-7 rounded-2xl border border-slate-200 hover:border-brand-blue/30 hover:shadow-xl transition-all duration-300 group">
            <div class="w-14 h-14 rounded-2xl bg-blue-100 text-brand-blue flex items-center justify-center text-2xl font-black mb-5 group-hover:scale-110 transition-transform">
              🚐
            </div>
            <h3 class="text-lg font-bold text-slate-900 mb-2">Comfortable Travel</h3>
            <p class="text-xs font-semibold text-brand-blue uppercase tracking-wider mb-2">Force Urbania Fleet</p>
            <p class="text-slate-600 text-sm leading-relaxed">
              Travel relaxed with whisper-quiet cabin acoustics, individual push-back reclining seats, USB ports, and smooth European monocoque suspension.
            </p>
          </div>

          <!-- Card 3 -->
          <div class="bg-slate-50 hover:bg-white p-7 rounded-2xl border border-slate-200 hover:border-brand-blue/30 hover:shadow-xl transition-all duration-300 group">
            <div class="w-14 h-14 rounded-2xl bg-orange-100 text-brand-orange flex items-center justify-center text-2xl font-black mb-5 group-hover:scale-110 transition-transform">
              🛡️
            </div>
            <h3 class="text-lg font-bold text-slate-900 mb-2">Professional Driving</h3>
            <p class="text-xs font-semibold text-brand-orange uppercase tracking-wider mb-2">Seasoned Chauffeurs</p>
            <p class="text-slate-600 text-sm leading-relaxed">
              Courteous, verified highway drivers with exemplary safety records and extensive route knowledge across Tamil Nadu and neighboring states.
            </p>
          </div>

          <!-- Card 4 -->
          <div class="bg-slate-50 hover:bg-white p-7 rounded-2xl border border-slate-200 hover:border-brand-blue/30 hover:shadow-xl transition-all duration-300 group">
            <div class="w-14 h-14 rounded-2xl bg-blue-100 text-brand-blue flex items-center justify-center text-2xl font-black mb-5 group-hover:scale-110 transition-transform">
              ✓
            </div>
            <h3 class="text-lg font-bold text-slate-900 mb-2">Transparent Pricing</h3>
            <p class="text-xs font-semibold text-brand-blue uppercase tracking-wider mb-2">No Hidden Surcharges</p>
            <p class="text-slate-600 text-sm leading-relaxed">
              Fuel, Driver Bata, Toll, and Rent are clearly covered in the advertised ₹33/KM rate. No surprise charges at the end of your journey.
            </p>
          </div>

        </div>
      </div>
    </section>

    <!-- VEHICLE SHOWCASE WITH REAL POSTER IMAGERY -->
    <section class="py-16 sm:py-24 bg-slate-100/70 border-y border-slate-200">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
          
          <!-- Left Specs Column -->
          <div class="lg:col-span-6 space-y-6">
            <span class="text-xs font-bold text-brand-blue uppercase tracking-widest px-3 py-1 bg-blue-50 border border-blue-200 rounded-full inline-block">
              Our Primary Vehicle
            </span>
            <h2 class="text-3xl sm:text-4xl font-black font-display text-slate-900 tracking-tight">
              Force Urbania Luxury Tourist Van
            </h2>
            <p class="text-slate-600 text-sm sm:text-base leading-relaxed">
              As showcased in our official promotion, the Force Urbania is tailored specifically for families and groups who want the utmost in long-distance touring comfort.
            </p>

            <div class="grid grid-cols-2 gap-4 pt-2">
              <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm">
                <span class="text-2xl mb-1 block">❄️</span>
                <p class="font-bold text-slate-900 text-sm">Roof Dual AC</p>
                <p class="text-slate-500 text-xs mt-0.5">Individual vents for each row</p>
              </div>
              <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm">
                <span class="text-2xl mb-1 block">💺</span>
                <p class="font-bold text-slate-900 text-sm">Push-back Seats</p>
                <p class="text-slate-500 text-xs mt-0.5">Ergonomic reclining seats</p>
              </div>
              <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm">
                <span class="text-2xl mb-1 block">📡</span>
                <p class="font-bold text-slate-900 text-sm">GPS Tracking</p>
                <p class="text-slate-500 text-xs mt-0.5">Live tracking & journey safety</p>
              </div>
              <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm">
                <span class="text-2xl mb-1 block">🔌</span>
                <p class="font-bold text-slate-900 text-sm">USB Mobile Ports</p>
                <p class="text-slate-500 text-xs mt-0.5">Fast charging throughout</p>
              </div>
            </div>

            <div class="bg-amber-50 border border-amber-200 rounded-xl p-4 text-xs text-amber-900">
              ℹ️ <strong>Seating Capacity Notice:</strong> Seating configuration (typically 12 to 17 passengers) will be verified upon receiving your trip enquiry.
            </div>

            <div class="flex gap-4 pt-2">
              <button onclick="switchTab('booking')" class="bg-brand-blue hover:bg-blue-800 text-white font-bold px-6 py-3 rounded-xl text-sm transition">
                Book This Vehicle
              </button>
              <button onclick="openPosterModal()" class="border border-slate-300 hover:border-brand-blue text-slate-700 hover:text-brand-blue font-semibold px-6 py-3 rounded-xl text-sm transition">
                View Official Poster
              </button>
            </div>
          </div>

          <!-- Right: Vehicle Real Imagery + Poster Banner -->
          <div class="lg:col-span-6 space-y-6">
            <div class="bg-white rounded-3xl p-6 border border-slate-200 shadow-xl space-y-4">
              <div class="relative rounded-2xl overflow-hidden shadow-md">
                <img src="urbania-van.jpg" alt="Force Urbania on Mountain Highway" class="w-full h-auto object-cover" onerror="this.onerror=null; this.src='public/urbania-van.jpg'">
                <div class="absolute bottom-3 left-3 bg-slate-950/80 backdrop-blur text-white text-xs px-3 py-1 rounded-lg">
                  Actual Vehicle & Scenic Route
                </div>
              </div>

              <!-- Official Poster Snippet -->
              <div class="flex items-center gap-4 bg-blue-50 p-4 rounded-2xl border border-blue-200 cursor-pointer hover:bg-blue-100 transition" onclick="openPosterModal()">
                <img src="mugil-travels-poster.jpg" alt="Mugil Travels Poster" class="w-16 h-20 object-cover rounded-lg shadow-sm border border-white" onerror="this.onerror=null; this.src='public/mugil-travels-poster.jpg'">
                <div class="flex-1">
                  <span class="text-[10px] font-black uppercase text-brand-orange bg-white px-2 py-0.5 rounded shadow-xs">Official Creative</span>
                  <p class="font-bold text-slate-900 text-sm mt-1">Mugil Travels Promotional Poster</p>
                  <p class="text-xs text-brand-blue font-semibold">Click to expand & view full resolution →</p>
                </div>
              </div>

              <!-- Price Box -->
              <div class="p-4 bg-gradient-to-r from-blue-900 to-brand-blue text-white rounded-2xl text-center">
                <span class="text-xs uppercase text-blue-200 font-bold">Base Tariff</span>
                <div class="text-4xl font-black text-amber-400 font-display">₹33 <span class="text-base text-white font-normal">/ KM</span></div>
                <p class="text-xs text-blue-100 mt-1">Fuel · Driver Bata · Toll · Rent Included</p>
              </div>
            </div>
          </div>

        </div>

      </div>
    </section>

    <!-- PRICING & FARE ESTIMATOR SECTION -->
    <section class="py-16 sm:py-24 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="text-center max-w-3xl mx-auto mb-16 space-y-3">
          <span class="text-xs font-bold text-brand-orange uppercase tracking-widest px-3 py-1 bg-orange-50 rounded-full inline-block">Transparent Tariff</span>
          <h2 class="text-3xl sm:text-4xl font-black font-display text-slate-900 tracking-tight">Simple, Transparent Pricing</h2>
          <p class="text-slate-600 text-sm sm:text-base leading-relaxed">
            No complicated calculations or hidden surcharges. Enjoy a straightforward ₹33 per kilometer tariff.
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
          
          <!-- Pricing Inclusions Column -->
          <div class="lg:col-span-7 bg-slate-50 rounded-3xl p-8 border border-slate-200 space-y-6">
            <div class="flex items-baseline justify-between border-b border-slate-200 pb-5">
              <div>
                <span class="text-xs uppercase font-bold text-slate-500 tracking-wider">Base Rate</span>
                <h3 class="text-3xl font-black text-brand-blue font-display">₹33 <span class="text-base text-slate-600 font-normal">per KM</span></h3>
              </div>
              <span class="bg-blue-100 text-brand-blue text-xs font-bold px-3 py-1.5 rounded-full">Force Urbania</span>
            </div>

            <div>
              <p class="text-sm font-bold text-slate-900 mb-3">Advertised Inclusions (From Poster):</p>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 flex items-center gap-2.5">
                  <span class="w-8 h-8 rounded-full bg-blue-600 text-white flex items-center justify-center font-bold text-sm">⛽</span>
                  <div>
                    <span class="font-bold text-slate-800 text-sm">Fuel</span>
                    <p class="text-xs text-slate-500">100% Covered</p>
                  </div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 flex items-center gap-2.5">
                  <span class="w-8 h-8 rounded-full bg-red-600 text-white flex items-center justify-center font-bold text-sm">👤</span>
                  <div>
                    <span class="font-bold text-slate-800 text-sm">Driver Bata</span>
                    <p class="text-xs text-slate-500">Allowance Included</p>
                  </div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 flex items-center gap-2.5">
                  <span class="w-8 h-8 rounded-full bg-green-600 text-white flex items-center justify-center font-bold text-sm">🛣️</span>
                  <div>
                    <span class="font-bold text-slate-800 text-sm">Toll</span>
                    <p class="text-xs text-slate-500">Highway Tolls Included</p>
                  </div>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 flex items-center gap-2.5">
                  <span class="w-8 h-8 rounded-full bg-orange-500 text-white flex items-center justify-center font-bold text-sm">₹</span>
                  <div>
                    <span class="font-bold text-slate-800 text-sm">Rent</span>
                    <p class="text-xs text-slate-500">Vehicle Rental Charge</p>
                  </div>
                </div>
              </div>
            </div>

            <div class="bg-blue-50 border border-blue-200 rounded-2xl p-4 text-xs text-blue-900 space-y-1.5">
              <p class="font-bold flex items-center gap-1.5">
                <span>📌</span> Important Pricing Policy:
              </p>
              <p>• ₹33/KM is the advertised rate and not necessarily the final payable amount for all customized routes.</p>
              <p>• Minimum kilometres, driver night stay allowances (if any), state border entry tax, and parking fees will be confirmed upon checking vehicle availability.</p>
            </div>
          </div>

          <!-- Quick Interactive Fare Estimator Calculator -->
          <div class="lg:col-span-5 bg-white rounded-3xl p-8 border border-slate-200 shadow-xl space-y-5">
            <h3 class="text-xl font-bold text-slate-900">Interactive Fare Estimator</h3>
            <p class="text-xs text-slate-500">Calculate an instant estimate based on ₹33/KM:</p>

            <div class="space-y-4">
              <div>
                <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Estimated Distance (in KM)</label>
                <input type="number" id="calcKm" value="250" min="1" oninput="calculateHeroFare()" class="w-full px-4 py-2.5 border-2 border-slate-200 rounded-xl text-sm font-semibold outline-none focus:border-brand-blue">
              </div>

              <div>
                <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Trip Type</label>
                <select id="calcType" onchange="calculateHeroFare()" class="w-full px-4 py-2.5 border-2 border-slate-200 rounded-xl text-sm font-semibold outline-none focus:border-brand-blue bg-white">
                  <option value="one_way">One Way Trip</option>
                  <option value="round_trip" selected>Round Trip (2x KM)</option>
                </select>
              </div>

              <div class="bg-slate-50 rounded-2xl p-4 border border-slate-100 text-center space-y-1">
                <span class="text-xs uppercase font-bold text-slate-400">Estimated Total Fare</span>
                <div id="calcResult" class="text-3xl font-black text-brand-orange font-display">₹16,500</div>
                <p id="calcBreakdown" class="text-xs text-slate-500">500 KM total @ ₹33/KM</p>
              </div>

              <button onclick="openBookingWithEstimate()" class="w-full bg-brand-orange hover:bg-brand-orangeDark text-white font-bold py-3.5 rounded-xl text-sm shadow transition">
                Proceed to Book with This Estimate →
              </button>
            </div>
          </div>

        </div>

      </div>
    </section>

    <!-- POPULAR TRAVEL CATEGORIES -->
    <section class="py-16 sm:py-24 bg-slate-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="text-center max-w-3xl mx-auto mb-16 space-y-3">
          <span class="text-xs font-bold text-brand-blue uppercase tracking-widest px-3 py-1 bg-blue-50 rounded-full inline-block">Tailored Journeys</span>
          <h2 class="text-3xl sm:text-4xl font-black font-display text-slate-900 tracking-tight">Popular Travel Categories</h2>
          <p class="text-slate-600 text-sm sm:text-base leading-relaxed">
            From joyful family vacations to grand wedding transport, we deliver comfortable journeys for every occasion.
          </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-5 gap-6">
          
          <div class="bg-white p-6 rounded-2xl border border-slate-200 hover:shadow-lg transition text-center group cursor-pointer" onclick="switchTab('booking')">
            <div class="w-16 h-16 rounded-2xl bg-blue-50 text-3xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition">👨‍👩‍👧‍👦</div>
            <h3 class="font-bold text-slate-900 text-base mb-1">Family Trips</h3>
            <p class="text-xs text-slate-500 mb-4">Temple tours, hill stations, and holiday getaways with elders and kids.</p>
            <span class="text-xs font-bold text-brand-blue group-hover:underline">Enquire Now →</span>
          </div>

          <div class="bg-white p-6 rounded-2xl border border-slate-200 hover:shadow-lg transition text-center group cursor-pointer" onclick="switchTab('booking')">
            <div class="w-16 h-16 rounded-2xl bg-purple-50 text-3xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition">🏕️</div>
            <h3 class="font-bold text-slate-900 text-base mb-1">Friends Trips</h3>
            <p class="text-xs text-slate-500 mb-4">College reunions, adventurous road trips, and weekend escapes.</p>
            <span class="text-xs font-bold text-brand-blue group-hover:underline">Enquire Now →</span>
          </div>

          <div class="bg-white p-6 rounded-2xl border border-slate-200 hover:shadow-lg transition text-center group cursor-pointer" onclick="switchTab('booking')">
            <div class="w-16 h-16 rounded-2xl bg-orange-50 text-3xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition">🏛️</div>
            <h3 class="font-bold text-slate-900 text-base mb-1">Tourist Trips</h3>
            <p class="text-xs text-slate-500 mb-4">Explore Ooty, Kodaikanal, Madurai, Rameshwaram, and Munnar.</p>
            <span class="text-xs font-bold text-brand-blue group-hover:underline">Enquire Now →</span>
          </div>

          <div class="bg-white p-6 rounded-2xl border border-slate-200 hover:shadow-lg transition text-center group cursor-pointer" onclick="switchTab('booking')">
            <div class="w-16 h-16 rounded-2xl bg-green-50 text-3xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition">🛣️</div>
            <h3 class="font-bold text-slate-900 text-base mb-1">Outstation Travel</h3>
            <p class="text-xs text-slate-500 mb-4">Dependable long-distance city-to-city travel across South India.</p>
            <span class="text-xs font-bold text-brand-blue group-hover:underline">Enquire Now →</span>
          </div>

          <div class="bg-white p-6 rounded-2xl border border-slate-200 hover:shadow-lg transition text-center group cursor-pointer" onclick="switchTab('booking')">
            <div class="w-16 h-16 rounded-2xl bg-pink-50 text-3xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition">💍</div>
            <h3 class="font-bold text-slate-900 text-base mb-1">Wedding & Events</h3>
            <p class="text-xs text-slate-500 mb-4">Punctual, premium transportation for wedding guests and VIPs.</p>
            <span class="text-xs font-bold text-brand-blue group-hover:underline">Enquire Now →</span>
          </div>

        </div>

      </div>
    </section>

    <!-- CTA BANNER MATCHING POSTER THEME -->
    <section class="py-16 gradient-poster-banner text-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-6">
        <span class="bg-white/10 px-4 py-1.5 rounded-full text-xs font-extrabold uppercase tracking-wider border border-white/20 text-amber-300">
          FOR BOOKING · +91 994 2222 824
        </span>
        <h2 class="text-3xl sm:text-5xl font-black font-display tracking-tight text-white">
          குறைந்த பணத்தில் நிறைவான பயணம்.
        </h2>
        <p class="text-blue-100 text-base sm:text-lg max-w-2xl mx-auto">
          Contact Mugil Travels today. Get a transparent quote at ₹33/KM with vehicle availability confirmed in minutes.
        </p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-4 pt-2">
          <button onclick="switchTab('booking')" class="bg-brand-orange hover:bg-brand-orangeDark text-white font-extrabold px-8 py-4 rounded-xl shadow-xl transition">
            Book Your Trip Online
          </button>
          <a href="https://wa.me/919942222824?text=Hello%20Mugil%20Travels!%20I%20would%20like%20to%20enquire%20about%20Force%20Urbania%20rental." target="_blank" class="bg-green-600 hover:bg-green-700 text-white font-bold px-7 py-4 rounded-xl shadow-xl transition flex items-center gap-2">
            <span>💬 Chat on WhatsApp</span>
          </a>
          <a href="tel:+919942222824" class="bg-white hover:bg-slate-100 text-brand-blue font-bold px-7 py-4 rounded-xl shadow-xl transition flex items-center gap-2">
            <span>📞 Call +91 994 2222 824</span>
          </a>
        </div>
      </div>
    </section>

  </main>


  <!-- ========================================================================= -->
  <!-- TAB 2: ABOUT US PAGE -->
  <!-- ========================================================================= -->
  <main id="tab-about" class="tab-content py-16 bg-slate-50">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 space-y-12">
      
      <!-- Header -->
      <div class="text-center space-y-3">
        <div class="inline-block bg-white p-2 rounded-2xl shadow-sm border border-slate-200 mb-2">
          <img src="logo.png" alt="Mugil Travels" class="h-10 w-auto" onerror="this.onerror=null; this.src='public/logo.png'">
        </div>
        <h1 class="text-3xl sm:text-5xl font-black font-display text-slate-900 tracking-tight">About Mugil Travels</h1>
        <p class="text-brand-blue font-semibold text-lg">"Luxurious Journey, Affordable Price"</p>
        <p class="text-slate-600 text-base max-w-2xl mx-auto leading-relaxed">
          Founded with a clear mission: to make premium, chauffeur-driven group travel across South India truly accessible, dependable, and delightfully comfortable.
        </p>
      </div>

      <!-- Philosophy Cards -->
      <div class="bg-white rounded-3xl p-8 border border-slate-200 shadow-sm space-y-6">
        <h2 class="text-2xl font-bold text-slate-900">Our Travel Service Philosophy</h2>
        
        <div class="space-y-4 text-slate-700 leading-relaxed text-sm sm:text-base">
          <p>
            At <strong>Mugil Travels</strong>, we believe that the journey should be just as memorable and rejuvenating as the destination itself. Whether our guests are travelling for sacred temple pilgrimages, family reunions in the hills, or corporate off-sites, our focus is unwavering: delivering peace of mind from pickup to drop-off.
          </p>
          <p>
            We shattered the common perception that luxury group vehicles demand exorbitant hire rates. By operating our flagship <strong>Force Urbania</strong> fleet at an advertised flat rate of <strong>₹33 per KM</strong> with Fuel, Driver Bata, Toll, and Rent all included, we offer a transparent, five-star travel standard for families and friends.
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 pt-4">
          <div class="bg-slate-50 p-5 rounded-2xl border border-slate-200">
            <span class="text-3xl mb-2 block">🤝</span>
            <h3 class="font-bold text-slate-900 text-sm mb-1">Customer-First Approach</h3>
            <p class="text-xs text-slate-500 leading-relaxed">Punctual arrivals, flexible pickup points, and 24/7 dedicated telephone support.</p>
          </div>
          <div class="bg-slate-50 p-5 rounded-2xl border border-slate-200">
            <span class="text-3xl mb-2 block">💎</span>
            <h3 class="font-bold text-slate-900 text-sm mb-1">Affordable Luxury</h3>
            <p class="text-xs text-slate-500 leading-relaxed">Business-class recliner seating and modern air suspension at ₹33/KM.</p>
          </div>
          <div class="bg-slate-50 p-5 rounded-2xl border border-slate-200">
            <span class="text-3xl mb-2 block">🔍</span>
            <h3 class="font-bold text-slate-900 text-sm mb-1">Transparent Billing</h3>
            <p class="text-xs text-slate-500 leading-relaxed">Zero hidden fees or surprise driver claims. Clear upfront fare quotations.</p>
          </div>
        </div>
      </div>

      <!-- Direct CTA -->
      <div class="bg-brand-blue text-white rounded-3xl p-8 text-center space-y-4">
        <h3 class="text-2xl font-bold font-display">Plan Your Next Trip with Mugil Travels</h3>
        <p class="text-blue-100 text-sm max-w-xl mx-auto">Experience the Force Urbania difference. Speak with our travel coordinator today.</p>
        <div class="flex justify-center gap-4 pt-2">
          <button onclick="switchTab('booking')" class="bg-brand-orange hover:bg-brand-orangeDark text-white font-bold px-6 py-3 rounded-xl text-sm transition">Book Online</button>
          <a href="tel:+919942222824" class="bg-white/10 hover:bg-white/20 text-white font-semibold px-6 py-3 rounded-xl text-sm border border-white/20 transition">Call +91 994 2222 824</a>
        </div>
      </div>

    </div>
  </main>


  <!-- ========================================================================= -->
  <!-- TAB 3: OUR VEHICLE (FORCE URBANIA) PAGE -->
  <!-- ========================================================================= -->
  <main id="tab-vehicle" class="tab-content py-16 bg-slate-50">
    <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 space-y-12">
      
      <!-- Header -->
      <div class="text-center space-y-3">
        <span class="text-xs font-bold text-brand-orange uppercase tracking-widest px-3 py-1 bg-orange-50 rounded-full inline-block">Dedicated Fleet</span>
        <h1 class="text-3xl sm:text-5xl font-black font-display text-slate-900 tracking-tight">Force Urbania Luxury Van</h1>
        <p class="text-slate-600 text-base max-w-xl mx-auto">India's most sophisticated, spacious, and comfortable tourist vehicle.</p>
      </div>

      <!-- Hero Vehicle Banner Card with Real Poster Image -->
      <div class="bg-white rounded-3xl p-6 sm:p-8 shadow-xl border border-slate-200 overflow-hidden space-y-6">
        <div class="relative rounded-2xl overflow-hidden shadow-md">
          <img src="urbania-van.jpg" alt="Force Urbania Luxury Van" class="w-full h-auto object-cover" onerror="this.onerror=null; this.src='public/urbania-van.jpg'">
          <div class="absolute bottom-4 left-4 bg-slate-950/85 backdrop-blur text-white px-4 py-2 rounded-xl border border-white/20">
            <span class="text-xs font-bold text-orange-400 uppercase tracking-wider block">Mugil Travels Flagship</span>
            <span class="text-base sm:text-lg font-black">Force Urbania · Luxury Tourist Van</span>
          </div>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 gap-4 text-center">
          <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
            <p class="text-xs text-slate-400 font-bold uppercase">Rate</p>
            <p class="text-xl font-black text-brand-orange">₹33/KM</p>
          </div>
          <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
            <p class="text-xs text-slate-400 font-bold uppercase">Comfort</p>
            <p class="text-sm font-bold text-slate-900">Push-back Recliners</p>
          </div>
          <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
            <p class="text-xs text-slate-400 font-bold uppercase">Cooling</p>
            <p class="text-sm font-bold text-slate-900">Roof Dual AC</p>
          </div>
          <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
            <p class="text-xs text-slate-400 font-bold uppercase">Safety</p>
            <p class="text-sm font-bold text-slate-900">GPS & Verified Driver</p>
          </div>
        </div>
      </div>

      <!-- Amenities & Specifications Grid -->
      <div class="bg-white rounded-3xl p-8 border border-slate-200 shadow-sm space-y-8">
        <h2 class="text-2xl font-bold text-slate-900">Vehicle Amenities & Facilities</h2>
        
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
          <div class="flex items-start gap-3.5 p-4 rounded-xl bg-slate-50 border border-slate-100">
            <span class="text-2xl">💺</span>
            <div>
              <p class="font-bold text-slate-900 text-sm">Push-back Recliner Seats</p>
              <p class="text-xs text-slate-500 mt-0.5">High-cushion ergonomic seats with individual armrests.</p>
            </div>
          </div>
          <div class="flex items-start gap-3.5 p-4 rounded-xl bg-slate-50 border border-slate-100">
            <span class="text-2xl">❄️</span>
            <div>
              <p class="font-bold text-slate-900 text-sm">Roof-Mounted Dual AC</p>
              <p class="text-xs text-slate-500 mt-0.5">Powerful cooling with separate blowers for every passenger row.</p>
            </div>
          </div>
          <div class="flex items-start gap-3.5 p-4 rounded-xl bg-slate-50 border border-slate-100">
            <span class="text-2xl">📡</span>
            <div>
              <p class="font-bold text-slate-900 text-sm">GPS Live Tracking</p>
              <p class="text-xs text-slate-500 mt-0.5">Real-time route optimization and 24/7 journey safety monitoring.</p>
            </div>
          </div>
          <div class="flex items-start gap-3.5 p-4 rounded-xl bg-slate-50 border border-slate-100">
            <span class="text-2xl">🔌</span>
            <div>
              <p class="font-bold text-slate-900 text-sm">USB Mobile Chargers</p>
              <p class="text-xs text-slate-500 mt-0.5">Keep all family devices powered throughout long highway trips.</p>
            </div>
          </div>
          <div class="flex items-start gap-3.5 p-4 rounded-xl bg-slate-50 border border-slate-100">
            <span class="text-2xl">🎵</span>
            <div>
              <p class="font-bold text-slate-900 text-sm">Premium Music System</p>
              <p class="text-xs text-slate-500 mt-0.5">Bluetooth audio setup for family songs, devotionals, and podcasts.</p>
            </div>
          </div>
          <div class="flex items-start gap-3.5 p-4 rounded-xl bg-slate-50 border border-slate-100">
            <span class="text-2xl">🧳</span>
            <div>
              <p class="font-bold text-slate-900 text-sm">Ample Luggage Trunk</p>
              <p class="text-xs text-slate-500 mt-0.5">Dedicated rear boot space for large suitcases and bags.</p>
            </div>
          </div>
        </div>

        <div class="bg-amber-50 border border-amber-200 rounded-2xl p-5 text-sm text-amber-900 space-y-1.5">
          <p class="font-bold">⚠️ Passenger Capacity & Configuration:</p>
          <p class="text-xs sm:text-sm">
            Exact passenger seating capacity (typically 12 to 17 seater) and luggage volume will be confirmed based on the exact vehicle assigned for your trip dates upon receiving your enquiry.
          </p>
        </div>

        <div class="text-center pt-4">
          <button onclick="switchTab('booking')" class="bg-brand-orange hover:bg-brand-orangeDark text-white font-bold px-8 py-4 rounded-xl shadow-lg transition">
            Book the Force Urbania for Your Trip
          </button>
        </div>
      </div>

    </div>
  </main>


  <!-- ========================================================================= -->
  <!-- TAB 4: SERVICES PAGE -->
  <!-- ========================================================================= -->
  <main id="tab-services" class="tab-content py-16 bg-slate-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 space-y-12">
      
      <!-- Header -->
      <div class="text-center space-y-3">
        <span class="text-xs font-bold text-brand-orange uppercase tracking-widest px-3 py-1 bg-orange-50 rounded-full inline-block">Tour & Travel Packages</span>
        <h1 class="text-3xl sm:text-5xl font-black font-display text-slate-900 tracking-tight">Our Travel Services</h1>
        <p class="text-slate-600 text-base max-w-xl mx-auto">Customized, reliable vehicle rental services designed for all kinds of group journeys.</p>
      </div>

      <!-- Services Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <div class="bg-white p-7 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition space-y-3">
          <div class="text-4xl">👨‍👩‍👧‍👦</div>
          <h3 class="text-xl font-bold text-slate-900">Family Tour Packages</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Spacious and safe travel for all generations. Ample legroom for elders and children with frequent comfort stops.
          </p>
          <div class="pt-2">
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase">Enquire for Family Trip →</button>
          </div>
        </div>

        <div class="bg-white p-7 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition space-y-3">
          <div class="text-4xl">🛣️</div>
          <h3 class="text-xl font-bold text-slate-900">Outstation Trips</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Seamless inter-district and inter-state journeys across Tamil Nadu, Kerala, Karnataka, and Andhra Pradesh.
          </p>
          <div class="pt-2">
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase">Plan Outstation Trip →</button>
          </div>
        </div>

        <div class="bg-white p-7 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition space-y-3">
          <div class="text-4xl">🏔️</div>
          <h3 class="text-xl font-bold text-slate-900">Weekend Getaways</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Quick 2-day retreats to popular hill stations like Ooty, Kodaikanal, Yercaud, and scenic coastal Pondicherry.
          </p>
          <div class="pt-2">
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase">Get Weekend Quote →</button>
          </div>
        </div>

        <div class="bg-white p-7 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition space-y-3">
          <div class="text-4xl">👥</div>
          <h3 class="text-xl font-bold text-slate-900">Group & Corporate Travel</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Team off-sites, corporate conferences, and friend reunions. Travel together in a single cohesive luxury vehicle.
          </p>
          <div class="pt-2">
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase">Enquire Group Travel →</button>
          </div>
        </div>

        <div class="bg-white p-7 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition space-y-3">
          <div class="text-4xl">🛕</div>
          <h3 class="text-xl font-bold text-slate-900">Tourist & Pilgrimage Places</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Complete circuits for Rameshwaram, Madurai Meenakshi Amman, Thanjavur Big Temple, and Tirupati with experienced drivers.
          </p>
          <div class="pt-2">
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase">Book Pilgrimage Tour →</button>
          </div>
        </div>

        <div class="bg-white p-7 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition space-y-3">
          <div class="text-4xl">💍</div>
          <h3 class="text-xl font-bold text-slate-900">Wedding & Event Transfers</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Punctual guest pickup from railway stations, airports, and hotels with coordinated ceremony drop-offs.
          </p>
          <div class="pt-2">
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase">Book Wedding Transfer →</button>
          </div>
        </div>

      </div>

      <!-- FAQs -->
      <div class="bg-white rounded-3xl p-8 border border-slate-200 shadow-sm space-y-6">
        <h2 class="text-2xl font-bold text-slate-900">Frequently Asked Questions</h2>
        
        <div class="space-y-4">
          <div class="border-b border-slate-200 pb-4">
            <h4 class="font-bold text-slate-800 text-sm">What is included in the advertised ₹33/KM price?</h4>
            <p class="text-xs text-slate-600 mt-1">The advertised ₹33 per KM covers Fuel, Driver Bata (allowance), Toll charges, and Vehicle Rent.</p>
          </div>
          <div class="border-b border-slate-200 pb-4">
            <h4 class="font-bold text-slate-800 text-sm">Is there a minimum kilometre limit per day?</h4>
            <p class="text-xs text-slate-600 mt-1">Yes, like most outstation tourist vehicle rentals, standard minimum daily coverage applies depending on your route and dates. This will be communicated when our team confirms your booking.</p>
          </div>
          <div class="border-b border-slate-200 pb-4">
            <h4 class="font-bold text-slate-800 text-sm">How do I confirm vehicle availability?</h4>
            <p class="text-xs text-slate-600 mt-1">Submit a booking enquiry online or call +91 994 2222 824. A Mugil Travels coordinator will verify the schedule and confirm your reservation directly.</p>
          </div>
        </div>
      </div>

    </div>
  </main>


  <!-- ========================================================================= -->
  <!-- TAB 5: ONLINE BOOKING SYSTEM -->
  <!-- ========================================================================= -->
  <main id="tab-booking" class="tab-content py-16 bg-slate-100/80">
    <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <!-- Booking Header -->
      <div class="text-center space-y-3 mb-10">
        <span class="text-xs font-bold text-brand-orange uppercase tracking-widest px-3 py-1 bg-orange-100 rounded-full inline-block">Online Reservation</span>
        <h1 class="text-3xl sm:text-4xl font-black font-display text-slate-900 tracking-tight">Book Your Journey</h1>
        <p class="text-slate-600 text-sm max-w-md mx-auto">
          Complete the form below to receive an instant fare estimate and submit your booking request.
        </p>
      </div>

      <!-- Multi-step Form Container Card -->
      <div class="bg-white rounded-3xl p-6 sm:p-10 border border-slate-200 shadow-xl">
        
        <!-- Step Indicator -->
        <div class="flex items-center justify-between mb-8 pb-6 border-b border-slate-100">
          <div class="flex items-center gap-2">
            <div id="stepBadge1" class="w-8 h-8 rounded-full bg-brand-blue text-white flex items-center justify-center font-bold text-sm">1</div>
            <span class="text-xs font-bold text-slate-700 hidden sm:inline">Trip Details</span>
          </div>
          <div class="flex-1 h-0.5 mx-3 bg-slate-200"></div>
          <div class="flex items-center gap-2">
            <div id="stepBadge2" class="w-8 h-8 rounded-full bg-slate-200 text-slate-600 flex items-center justify-center font-bold text-sm">2</div>
            <span class="text-xs font-bold text-slate-500 hidden sm:inline">Passengers & Notes</span>
          </div>
          <div class="flex-1 h-0.5 mx-3 bg-slate-200"></div>
          <div class="flex items-center gap-2">
            <div id="stepBadge3" class="w-8 h-8 rounded-full bg-slate-200 text-slate-600 flex items-center justify-center font-bold text-sm">3</div>
            <span class="text-xs font-bold text-slate-500 hidden sm:inline">Estimate & Submit</span>
          </div>
        </div>

        <!-- FORM STEP 1: TRIP DETAILS -->
        <div id="formStep1" class="space-y-5">
          <h3 class="text-lg font-bold text-slate-900 border-l-4 border-brand-blue pl-3">Step 1: Contact & Trip Details</h3>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Your Full Name *</label>
              <input type="text" id="custName" placeholder="e.g. Ramesh Kumar" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
              <span id="errName" class="text-red-500 text-xs hidden">Please enter your name</span>
            </div>
            <div>
              <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Mobile Number *</label>
              <input type="tel" id="custPhone" placeholder="10-digit number" maxlength="10" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
              <span id="errPhone" class="text-red-500 text-xs hidden">Please enter a valid 10-digit phone</span>
            </div>
          </div>

          <div>
            <label class="block text-xs font-bold uppercase text-slate-600 mb-1">WhatsApp Number (Optional)</label>
            <input type="tel" id="custWa" placeholder="Leave empty if same as mobile" maxlength="10" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
          </div>

          <!-- Trip Type Selector -->
          <div>
            <label class="block text-xs font-bold uppercase text-slate-600 mb-2">Trip Type *</label>
            <div class="grid grid-cols-3 gap-3">
              <label class="border-2 border-slate-200 has-[:checked]:border-brand-blue has-[:checked]:bg-blue-50/50 rounded-xl p-3 text-center cursor-pointer transition">
                <input type="radio" name="tripTypeRadio" value="one-way" class="sr-only" onchange="onTripTypeChange()">
                <span class="block text-xs font-bold text-slate-800">One Way</span>
              </label>
              <label class="border-2 border-brand-blue bg-blue-50/50 rounded-xl p-3 text-center cursor-pointer transition">
                <input type="radio" name="tripTypeRadio" value="round-trip" checked class="sr-only" onchange="onTripTypeChange()">
                <span class="block text-xs font-bold text-slate-800">Round Trip</span>
              </label>
              <label class="border-2 border-slate-200 has-[:checked]:border-brand-blue has-[:checked]:bg-blue-50/50 rounded-xl p-3 text-center cursor-pointer transition">
                <input type="radio" name="tripTypeRadio" value="multi-day" class="sr-only" onchange="onTripTypeChange()">
                <span class="block text-xs font-bold text-slate-800">Multi-Day</span>
              </label>
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Pickup Location *</label>
              <input type="text" id="pickupLoc" placeholder="e.g. Coimbatore Airport / Address" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
              <span id="errPickup" class="text-red-500 text-xs hidden">Pickup location is required</span>
            </div>
            <div>
              <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Destination Location *</label>
              <input type="text" id="dropLoc" placeholder="e.g. Ooty Town / Hotel" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
              <span id="errDrop" class="text-red-500 text-xs hidden">Destination is required</span>
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Pickup Date *</label>
              <input type="date" id="pickupDate" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
              <span id="errDate" class="text-red-500 text-xs hidden">Pickup date is required</span>
            </div>
            <div>
              <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Pickup Time *</label>
              <input type="time" id="pickupTime" value="06:00" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
            </div>
          </div>

          <div id="returnDateContainer">
            <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Return Date</label>
            <input type="date" id="returnDate" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
          </div>

          <div class="flex justify-end pt-4">
            <button onclick="goToStep(2)" class="bg-brand-blue hover:bg-blue-800 text-white font-bold px-8 py-3 rounded-xl text-sm transition">
              Next: Passengers & Requirements →
            </button>
          </div>
        </div>

        <!-- FORM STEP 2: PASSENGERS & REQUIREMENTS -->
        <div id="formStep2" class="space-y-5 hidden">
          <h3 class="text-lg font-bold text-slate-900 border-l-4 border-brand-blue pl-3">Step 2: Passengers & Travel Notes</h3>

          <div>
            <label class="block text-xs font-bold uppercase text-slate-600 mb-2">Number of Passengers (1 - 20)</label>
            <div class="flex items-center gap-4">
              <button onclick="adjustPax(-1)" class="w-10 h-10 rounded-xl border border-slate-300 font-black text-xl hover:bg-slate-100">-</button>
              <span id="paxCount" class="text-2xl font-black text-brand-blue w-12 text-center">8</span>
              <button onclick="adjustPax(1)" class="w-10 h-10 rounded-xl border border-slate-300 font-black text-xl hover:bg-slate-100">+</button>
              <span class="text-xs text-slate-500">Selected for Force Urbania</span>
            </div>
          </div>

          <div>
            <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Additional Requirements</label>
            <textarea id="reqs" rows="2" placeholder="e.g. child seating, luggage carrier, multiple pickup spots..." class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none resize-none"></textarea>
          </div>

          <div>
            <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Special Instructions</label>
            <textarea id="instructions" rows="2" placeholder="e.g. early morning pickup timing, specific route requests..." class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none resize-none"></textarea>
          </div>

          <div class="flex justify-between pt-4">
            <button onclick="goToStep(1)" class="border border-slate-300 text-slate-700 hover:bg-slate-50 font-bold px-6 py-3 rounded-xl text-sm transition">
              ← Back
            </button>
            <button onclick="goToStep(3)" class="bg-brand-blue hover:bg-blue-800 text-white font-bold px-8 py-3 rounded-xl text-sm transition">
              Next: Fare Estimate & Submit →
            </button>
          </div>
        </div>

        <!-- FORM STEP 3: ESTIMATE & SUBMIT -->
        <div id="formStep3" class="space-y-6 hidden">
          <h3 class="text-lg font-bold text-slate-900 border-l-4 border-brand-blue pl-3">Step 3: Estimated Fare & Submission</h3>

          <div class="bg-blue-50 border border-blue-200 rounded-2xl p-5 space-y-3">
            <label class="block text-xs font-bold uppercase text-blue-900">Approximate Distance (One Way in KM)</label>
            <input type="number" id="bookingKm" value="200" min="10" oninput="updateBookingEstimate()" class="w-full px-4 py-2.5 border border-blue-300 rounded-xl text-sm font-bold text-slate-800 bg-white">
            <p class="text-[11px] text-blue-700">Enter approximate distance to see a live fare breakdown at ₹33/KM.</p>
          </div>

          <!-- Fare Breakdown Box -->
          <div class="bg-slate-50 rounded-2xl p-5 border border-slate-200 space-y-3 text-sm">
            <h4 class="font-bold text-slate-800 uppercase text-xs tracking-wider">Estimated Fare Breakdown:</h4>
            <div class="flex justify-between text-slate-600">
              <span id="breakdownKmLabel">Distance Calculation (200 KM × 2 × ₹33/KM):</span>
              <span id="breakdownTotal" class="font-bold text-slate-900">₹13,200</span>
            </div>
            <div class="flex justify-between text-xs text-green-700 font-semibold border-t border-slate-200 pt-2">
              <span>Included: Fuel, Driver Bata, Toll, Rent</span>
              <span>100% INCLUDED</span>
            </div>
            <div class="flex justify-between items-baseline border-t border-slate-300 pt-2 text-base font-black text-brand-blue">
              <span>Estimated Payable Fare</span>
              <span id="finalEstimatedFare" class="text-2xl text-brand-orange">₹13,200</span>
            </div>
          </div>

          <!-- Important Disclaimer -->
          <div class="bg-amber-50 border border-amber-200 rounded-xl p-4 text-xs text-amber-900 space-y-1">
            <p class="font-bold">⚠️ Important Fare & Availability Notice:</p>
            <p>• ₹33/KM is the advertised rate. This online calculation is an <strong>estimate only</strong>.</p>
            <p>• Final payable price will be confirmed by Mugil Travels after verifying route details, state permits, and vehicle availability.</p>
          </div>

          <div class="flex justify-between pt-4">
            <button onclick="goToStep(2)" class="border border-slate-300 text-slate-700 hover:bg-slate-50 font-bold px-6 py-3 rounded-xl text-sm transition">
              ← Back
            </button>
            <button onclick="submitBookingRequest()" id="btnSubmitBooking" class="bg-brand-orange hover:bg-brand-orangeDark text-white font-extrabold px-8 py-3.5 rounded-xl text-base shadow-lg transition">
              🚀 Submit Booking Request
            </button>
          </div>
        </div>

        <!-- CONFIRMATION SCREEN -->
        <div id="bookingConfirmation" class="text-center py-8 space-y-6 hidden">
          <div class="w-20 h-20 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto text-4xl shadow-inner">
            ✓
          </div>
          <div>
            <span class="bg-green-100 text-green-800 text-xs font-bold px-3 py-1 rounded-full uppercase">Request Received</span>
            <h3 class="text-2xl sm:text-3xl font-black font-display text-slate-900 mt-2">Thank You, <span id="confName">Customer</span>!</h3>
            <p class="text-slate-600 text-sm max-w-md mx-auto mt-1">
              Your booking enquiry has been registered with Mugil Travels. Save your Booking ID below:
            </p>
          </div>

          <div class="bg-gradient-to-r from-blue-900 to-brand-blue text-white rounded-2xl p-6 max-w-md mx-auto text-left shadow-lg space-y-2">
            <p class="text-xs uppercase text-blue-200 font-bold tracking-wider">Your Booking Reference ID</p>
            <p id="confId" class="text-2xl font-mono font-black text-orange-400">MT-1715000000-XYZ</p>
            <div class="pt-2 border-t border-white/20 text-xs text-blue-100 space-y-1">
              <p>📍 Route: <span id="confRoute" class="font-semibold text-white">Coimbatore → Ooty</span></p>
              <p>📅 Date: <span id="confDate" class="font-semibold text-white">2026-11-20</span></p>
              <p>💰 Est. Fare: <span id="confFare" class="font-semibold text-orange-300">₹13,200</span></p>
            </div>
          </div>

          <div class="space-y-3 max-w-md mx-auto">
            <p class="text-xs text-slate-500 font-semibold">Connect with us immediately for instant confirmation:</p>
            <div class="flex flex-col sm:flex-row gap-3">
              <a id="btnConfWa" href="#" target="_blank" class="flex-1 bg-green-600 hover:bg-green-700 text-white font-bold py-3 px-4 rounded-xl text-sm transition shadow flex items-center justify-center gap-2">
                <span>💬 WhatsApp Us Now</span>
              </a>
              <a href="tel:+919942222824" class="flex-1 bg-brand-blue hover:bg-blue-900 text-white font-bold py-3 px-4 rounded-xl text-sm transition shadow flex items-center justify-center gap-2">
                <span>📞 Call +91 994 2222 824</span>
              </a>
            </div>
          </div>

          <div class="pt-4">
            <button onclick="resetBookingForm()" class="text-xs font-bold text-slate-500 hover:text-brand-blue underline">
              Submit Another Booking Enquiry
            </button>
          </div>
        </div>

      </div>

    </div>
  </main>


  <!-- ========================================================================= -->
  <!-- TAB 6: BLOG SECTION -->
  <!-- ========================================================================= -->
  <main id="tab-blog" class="tab-content py-16 bg-slate-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 space-y-12">
      
      <!-- Header -->
      <div class="text-center space-y-3">
        <span class="text-xs font-bold text-brand-orange uppercase tracking-widest px-3 py-1 bg-orange-50 rounded-full inline-block">Travel Insights</span>
        <h1 class="text-3xl sm:text-5xl font-black font-display text-slate-900 tracking-tight">Mugil Travels Road Trip Blog</h1>
        <p class="text-slate-600 text-base max-w-xl mx-auto">Destination guides, rental price breakdowns, and travel planning tips for South India.</p>
      </div>

      <!-- Blog Articles Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <!-- Post 1 -->
        <article class="bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="bg-gradient-to-r from-blue-900 to-brand-blue p-6 text-white text-center">
            <span class="text-4xl block mb-2">🏔️</span>
            <span class="text-xs font-bold uppercase tracking-wider text-orange-300">Travel Guide</span>
          </div>
          <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
            <div>
              <p class="text-xs text-slate-400">6 min read · Tamil Nadu</p>
              <h3 class="font-bold text-slate-900 text-lg mt-1">Best Tourist Places for Family Trips in Tamil Nadu</h3>
              <p class="text-slate-600 text-xs sm:text-sm mt-2 leading-relaxed">
                Explore top destinations including Ooty, Kodaikanal, Rameshwaram, and Madurai. How traveling in a luxury Force Urbania van ensures comfort for elders and kids.
              </p>
            </div>
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase text-left">Book Trip to Tamil Nadu →</button>
          </div>
        </article>

        <!-- Post 2 -->
        <article class="bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="bg-gradient-to-r from-orange-600 to-brand-orange p-6 text-white text-center">
            <span class="text-4xl block mb-2">💰</span>
            <span class="text-xs font-bold uppercase tracking-wider text-blue-100">Pricing Analysis</span>
          </div>
          <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
            <div>
              <p class="text-xs text-slate-400">5 min read · Price Guide</p>
              <h3 class="font-bold text-slate-900 text-lg mt-1">Force Urbania Rental Price Guide: Everything You Need to Know</h3>
              <p class="text-slate-600 text-xs sm:text-sm mt-2 leading-relaxed">
                A complete breakdown of our advertised ₹33/KM tariff. How Fuel, Driver Bata, Toll, and Rent work together to save you up to 30% on group travel.
              </p>
            </div>
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase text-left">Calculate Your Rate →</button>
          </div>
        </article>

        <!-- Post 3 -->
        <article class="bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="bg-gradient-to-r from-slate-800 to-slate-900 p-6 text-white text-center">
            <span class="text-4xl block mb-2">👨‍👩‍👧‍👦</span>
            <span class="text-xs font-bold uppercase tracking-wider text-green-300">Family Travel</span>
          </div>
          <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
            <div>
              <p class="text-xs text-slate-400">7 min read · Tips & Tricks</p>
              <h3 class="font-bold text-slate-900 text-lg mt-1">How to Plan a Comfortable Family Trip across South India</h3>
              <p class="text-slate-600 text-xs sm:text-sm mt-2 leading-relaxed">
                Crucial tips on choosing the right vehicle, planning temple pilgrimage stops, managing luggage, and ensuring elder comfort on highway drives.
              </p>
            </div>
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase text-left">Plan Family Itinerary →</button>
          </div>
        </article>

        <!-- Post 4 -->
        <article class="bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="bg-gradient-to-r from-blue-800 to-blue-950 p-6 text-white text-center">
            <span class="text-4xl block mb-2">🚐</span>
            <span class="text-xs font-bold uppercase tracking-wider text-orange-300">Vehicle Comparison</span>
          </div>
          <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
            <div>
              <p class="text-xs text-slate-400">6 min read · Luxury Van</p>
              <h3 class="font-bold text-slate-900 text-lg mt-1">Benefits of Hiring a Luxury Tourist Van for Outstation Travel</h3>
              <p class="text-slate-600 text-xs sm:text-sm mt-2 leading-relaxed">
                Why Force Urbania's monocoque chassis, individual recliners, and whisper-quiet cabin outshine older generation commercial vans.
              </p>
            </div>
            <button onclick="switchTab('vehicle')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase text-left">Explore Urbania Specs →</button>
          </div>
        </article>

        <!-- Post 5 -->
        <article class="bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="bg-gradient-to-r from-amber-600 to-brand-orange p-6 text-white text-center">
            <span class="text-4xl block mb-2">📊</span>
            <span class="text-xs font-bold uppercase tracking-wider text-white">Budget Guide</span>
          </div>
          <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
            <div>
              <p class="text-xs text-slate-400">8 min read · Cost Planning</p>
              <h3 class="font-bold text-slate-900 text-lg mt-1">Outstation Travel Planning Tips & Budget Optimization Guide</h3>
              <p class="text-slate-600 text-xs sm:text-sm mt-2 leading-relaxed">
                How to structure one-way vs round-trip fares, account for driver allowances, and plan optimal multi-day tours with zero budget surprises.
              </p>
            </div>
            <button onclick="switchTab('booking')" class="text-xs font-bold text-brand-blue hover:text-brand-orange uppercase text-left">Start Booking →</button>
          </div>
        </article>

      </div>

    </div>
  </main>


  <!-- ========================================================================= -->
  <!-- TAB 7: CONTACT PAGE -->
  <!-- ========================================================================= -->
  <main id="tab-contact" class="tab-content py-16 bg-slate-50">
    <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 space-y-12">
      
      <!-- Header -->
      <div class="text-center space-y-3">
        <span class="text-xs font-bold text-brand-orange uppercase tracking-widest px-3 py-1 bg-orange-50 rounded-full inline-block">Direct Contact</span>
        <h1 class="text-3xl sm:text-5xl font-black font-display text-slate-900 tracking-tight">Contact Mugil Travels</h1>
        <p class="text-slate-600 text-base max-w-md mx-auto">We're available 7 days a week to answer your travel questions and confirm bookings.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        
        <!-- Contact Information Cards -->
        <div class="space-y-4">
          <a href="tel:+919942222824" class="block bg-white p-6 rounded-2xl border border-slate-200 hover:border-brand-blue hover:shadow-md transition group">
            <div class="flex items-center gap-4">
              <div class="w-12 h-12 rounded-xl bg-blue-50 text-brand-blue flex items-center justify-center text-2xl group-hover:scale-110 transition">📞</div>
              <div>
                <p class="text-xs text-slate-400 font-bold uppercase">Booking Phone</p>
                <p class="text-xl font-black text-brand-blue">+91 994 2222 824</p>
                <p class="text-xs text-slate-500 mt-0.5">Click to call directly</p>
              </div>
            </div>
          </a>

          <a href="https://wa.me/919942222824?text=Hello%20Mugil%20Travels!%20I%20would%20like%20to%20enquire%20about%20booking%20Force%20Urbania." target="_blank" class="block bg-white p-6 rounded-2xl border border-slate-200 hover:border-green-500 hover:shadow-md transition group">
            <div class="flex items-center gap-4">
              <div class="w-12 h-12 rounded-xl bg-green-50 text-green-600 flex items-center justify-center text-2xl group-hover:scale-110 transition">💬</div>
              <div>
                <p class="text-xs text-slate-400 font-bold uppercase">WhatsApp Enquiry</p>
                <p class="text-xl font-black text-green-600">+91 994 2222 824</p>
                <p class="text-xs text-slate-500 mt-0.5">Chat with our booking team instantly</p>
              </div>
            </div>
          </a>

          <div class="bg-white p-6 rounded-2xl border border-slate-200 space-y-2">
            <p class="text-xs text-slate-400 font-bold uppercase">Service Coverage</p>
            <p class="text-base font-bold text-slate-800">Tamil Nadu & South India</p>
            <p class="text-xs text-slate-500">Pickups available across all major cities, airports, and railway junctions.</p>
          </div>

          <div class="bg-amber-50 border border-amber-200 rounded-2xl p-5 text-xs text-amber-900 space-y-1">
            <p class="font-bold">📍 Business Address & Office Notice:</p>
            <p>Please contact Mugil Travels at <strong>+91 994 2222 824</strong> to confirm our physical office location and depot schedule.</p>
          </div>
        </div>

        <!-- Quick Enquiry Form -->
        <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-sm space-y-4">
          <h3 class="text-lg font-bold text-slate-900">Send an Instant Message</h3>
          
          <div>
            <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Your Name</label>
            <input type="text" id="contactName" placeholder="Full Name" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
          </div>
          <div>
            <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Phone Number</label>
            <input type="tel" id="contactPhone" placeholder="10-digit mobile" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
          </div>
          <div>
            <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Trip Details / Message</label>
            <textarea id="contactMsg" rows="3" placeholder="Tell us your travel dates, pickup city, and destination..." class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none resize-none"></textarea>
          </div>

          <button onclick="sendContactWhatsApp()" class="w-full bg-green-600 hover:bg-green-700 text-white font-bold py-3.5 rounded-xl text-sm shadow transition flex items-center justify-center gap-2">
            <span>💬 Send via WhatsApp for Fastest Response</span>
          </button>
        </div>

      </div>

      <!-- Google Maps Placeholder Section -->
      <div class="bg-white rounded-3xl p-6 border border-slate-200 shadow-sm text-center">
        <div class="bg-slate-100 rounded-2xl h-56 flex flex-col items-center justify-center p-6 border-2 border-dashed border-slate-300">
          <span class="text-4xl mb-2">🗺️</span>
          <h4 class="font-bold text-slate-800 text-sm">Google Maps Location Placeholder</h4>
          <p class="text-xs text-slate-500 mt-1 max-w-sm">Contact Mugil Travels directly at +91 994 2222 824 to confirm our depot address for vehicle inspection.</p>
        </div>
      </div>

    </div>
  </main>


  <!-- ========================================================================= -->
  <!-- TAB 8: ADMIN DASHBOARD (WORKING OFFLINE & IN-BROWSER) -->
  <!-- ========================================================================= -->
  <main id="tab-admin" class="tab-content py-12 bg-slate-100 min-h-screen">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-8">
      
      <!-- Admin Login Gate -->
      <div id="adminLoginBox" class="max-w-md mx-auto bg-white rounded-3xl p-8 border border-slate-200 shadow-xl space-y-6">
        <div class="text-center space-y-2">
          <div class="bg-white p-2 rounded-2xl border border-slate-100 inline-block shadow-sm">
            <img src="logo.png" alt="Mugil Travels" class="h-10 w-auto" onerror="this.onerror=null; this.src='public/logo.png'">
          </div>
          <h2 class="text-2xl font-black font-display text-slate-900 mt-2">Admin Portal</h2>
          <p class="text-xs text-slate-500">Mugil Travels Booking & Enquiry Management</p>
        </div>

        <div class="space-y-4">
          <div>
            <label class="block text-xs font-bold uppercase text-slate-600 mb-1">Enter Admin Password</label>
            <input type="password" id="adminPassInput" placeholder="Password (default: mugiladmin123)" class="w-full px-4 py-2.5 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
            <p id="adminLoginError" class="text-red-500 text-xs mt-1 hidden">Incorrect password. Use: mugiladmin123</p>
          </div>

          <button onclick="handleAdminLogin()" class="w-full bg-brand-blue hover:bg-blue-800 text-white font-bold py-3 rounded-xl text-sm shadow transition">
            🔐 Unlock Dashboard
          </button>
          
          <p class="text-[11px] text-slate-400 text-center">
            Default credentials for local preview: <code class="text-brand-blue font-bold">mugiladmin123</code> or <code class="text-brand-blue font-bold">admin</code>
          </p>
        </div>
      </div>

      <!-- Admin Authenticated View -->
      <div id="adminDashboardView" class="hidden space-y-6">
        
        <!-- Admin Header -->
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 bg-white p-6 rounded-2xl border border-slate-200 shadow-sm">
          <div>
            <span class="text-xs font-bold uppercase text-brand-orange tracking-wider">Mugil Travels Control Room</span>
            <h2 class="text-2xl font-black font-display text-slate-900">Admin Booking Dashboard</h2>
          </div>
          <div class="flex items-center gap-3">
            <button onclick="exportBookingsCSV()" class="bg-green-600 hover:bg-green-700 text-white text-xs font-bold px-4 py-2.5 rounded-xl shadow transition flex items-center gap-1.5">
              <span>📥 Export CSV</span>
            </button>
            <button onclick="handleAdminLogout()" class="border border-slate-300 text-slate-600 hover:text-red-600 hover:bg-red-50 text-xs font-bold px-4 py-2.5 rounded-xl transition">
              🚪 Logout
            </button>
          </div>
        </div>

        <!-- KPI Stats Cards -->
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-4">
          <div class="bg-white p-5 rounded-2xl border border-slate-200 shadow-sm">
            <p class="text-xs font-bold uppercase text-slate-400">Total Bookings</p>
            <p id="statTotal" class="text-3xl font-black text-slate-900 mt-1 font-display">0</p>
          </div>
          <div class="bg-white p-5 rounded-2xl border border-blue-200 bg-blue-50/30 shadow-sm">
            <p class="text-xs font-bold uppercase text-brand-blue">New Enquiries</p>
            <p id="statNew" class="text-3xl font-black text-brand-blue mt-1 font-display">0</p>
          </div>
          <div class="bg-white p-5 rounded-2xl border border-green-200 bg-green-50/30 shadow-sm">
            <p class="text-xs font-bold uppercase text-green-700">Confirmed</p>
            <p id="statConfirmed" class="text-3xl font-black text-green-700 mt-1 font-display">0</p>
          </div>
          <div class="bg-white p-5 rounded-2xl border border-teal-200 bg-teal-50/30 shadow-sm">
            <p class="text-xs font-bold uppercase text-teal-700">Completed</p>
            <p id="statCompleted" class="text-3xl font-black text-teal-700 mt-1 font-display">0</p>
          </div>
        </div>

        <!-- Filters & Search Bar -->
        <div class="bg-white p-5 rounded-2xl border border-slate-200 shadow-sm flex flex-col sm:flex-row gap-3">
          <input type="text" id="adminSearch" oninput="renderAdminBookings()" placeholder="Search customer, phone, route, or ID..." class="flex-1 px-4 py-2 border border-slate-300 rounded-xl text-sm focus:border-brand-blue outline-none">
          <select id="adminStatusFilter" onchange="renderAdminBookings()" class="px-3 py-2 border border-slate-300 rounded-xl text-sm outline-none bg-white font-semibold">
            <option value="">All Statuses</option>
            <option value="New Enquiry">New Enquiry</option>
            <option value="Contacted">Contacted</option>
            <option value="Quotation Sent">Quotation Sent</option>
            <option value="Confirmed">Confirmed</option>
            <option value="Completed">Completed</option>
            <option value="Cancelled">Cancelled</option>
          </select>
          <button onclick="seedSampleData()" class="text-xs font-bold text-slate-500 hover:text-brand-blue border border-slate-200 px-3 py-2 rounded-xl">
            Reset Demo Data
          </button>
        </div>

        <!-- Bookings Table Container -->
        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left text-sm">
              <thead class="bg-slate-50 border-b border-slate-200 text-xs font-bold uppercase text-slate-500">
                <tr>
                  <th class="px-5 py-3.5">Booking ID</th>
                  <th class="px-5 py-3.5">Customer</th>
                  <th class="px-5 py-3.5">Route</th>
                  <th class="px-5 py-3.5">Date</th>
                  <th class="px-5 py-3.5">Pax</th>
                  <th class="px-5 py-3.5">Est. Fare</th>
                  <th class="px-5 py-3.5">Status</th>
                  <th class="px-5 py-3.5 text-right">Actions</th>
                </tr>
              </thead>
              <tbody id="adminBookingsTable" class="divide-y divide-slate-100">
                <!-- Dynamically rendered by JS -->
              </tbody>
            </table>
          </div>
        </div>

      </div>

    </div>
  </main>


  <!-- FOOTER -->
  <footer class="bg-brand-blueDark text-white pt-16 pb-12 border-t border-blue-900">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10 pb-12 border-b border-blue-900/60">
        
        <!-- Col 1 -->
        <div class="space-y-4">
          <div class="bg-white p-2 rounded-xl inline-block shadow-sm">
            <img src="logo.png" alt="Mugil Travels" class="h-10 w-auto" onerror="this.onerror=null; this.src='public/logo.png'">
          </div>
          <p class="text-xs text-blue-200 leading-relaxed">
            Luxurious Journey, Affordable Price. Premium Force Urbania tourist van rental service at flat ₹33 per KM with fuel, driver bata, toll, and rent included.
          </p>
          <p class="text-xs text-amber-400 font-semibold font-display">குறைந்த பணத்தில் நிறைவான பயணம்.</p>
        </div>

        <!-- Col 2: Navigation Links -->
        <div class="space-y-3">
          <h4 class="font-bold text-white text-sm uppercase tracking-wider">Quick Links</h4>
          <ul class="space-y-2 text-xs text-blue-200">
            <li><a href="javascript:void(0)" onclick="switchTab('home')" class="hover:text-white transition">Home</a></li>
            <li><a href="javascript:void(0)" onclick="switchTab('about')" class="hover:text-white transition">About Mugil Travels</a></li>
            <li><a href="javascript:void(0)" onclick="switchTab('vehicle')" class="hover:text-white transition">Our Vehicle (Force Urbania)</a></li>
            <li><a href="javascript:void(0)" onclick="switchTab('services')" class="hover:text-white transition">Tour & Travel Packages</a></li>
            <li><a href="javascript:void(0)" onclick="switchTab('blog')" class="hover:text-white transition">Travel Blog</a></li>
            <li><a href="javascript:void(0)" onclick="switchTab('booking')" class="hover:text-white transition">Online Booking</a></li>
          </ul>
        </div>

        <!-- Col 3: Service Categories -->
        <div class="space-y-3">
          <h4 class="font-bold text-white text-sm uppercase tracking-wider">Travel Services</h4>
          <ul class="space-y-2 text-xs text-blue-200">
            <li>Family Tour Packages</li>
            <li>Outstation Road Trips</li>
            <li>Weekend Hill Station Tours</li>
            <li>Group & Corporate Outings</li>
            <li>Pilgrimage & Temple Circuits</li>
            <li>Wedding & Event Transport</li>
          </ul>
        </div>

        <!-- Col 4: Contact -->
        <div class="space-y-3">
          <h4 class="font-bold text-white text-sm uppercase tracking-wider">Contact & Bookings</h4>
          <p class="text-xs text-blue-200">Phone & WhatsApp:</p>
          <a href="tel:+919942222824" class="text-lg font-black text-amber-400 hover:underline block">+91 994 2222 824</a>
          <p class="text-xs text-blue-300">Service Area: Tamil Nadu & South India</p>
          <div class="pt-2">
            <button onclick="switchTab('admin')" class="text-xs text-blue-400 hover:text-white transition">🔐 Admin Access</button>
          </div>
        </div>

      </div>

      <div class="pt-8 flex flex-col sm:flex-row items-center justify-between text-xs text-blue-300 gap-4">
        <p>© 2026 Mugil Travels. All rights reserved.</p>
        <p>Force Urbania Tourist Van Rental at ₹33/KM</p>
      </div>
    </div>
  </footer>

  <!-- ========================================================================= -->
  <!-- FLOATING ACTION BUTTONS (CALL NOW & WHATSAPP) -->
  <!-- ========================================================================= -->
  <div class="fixed bottom-6 right-6 z-50 flex flex-col items-end gap-3 pointer-events-auto">
    
    <!-- Floating Call Button -->
    <a href="tel:+919942222824" title="Call Mugil Travels" class="w-14 h-14 rounded-full bg-brand-blue text-white shadow-2xl flex items-center justify-center hover:scale-110 active:scale-95 transition-all group relative border-2 border-white">
      <svg class="w-6 h-6 text-white group-hover:rotate-12 transition-transform" fill="currentColor" viewBox="0 0 24 24"><path d="M6.62 10.79a15.053 15.053 0 006.59 6.59l2.2-2.2a1 1 0 011.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 011 1V20a1 1 0 01-1 1A17 17 0 013 4a1 1 0 011-1h3.5a1 1 0 011 1c0 1.25.2 2.46.57 3.58a1 1 0 01-.24 1.01l-2.21 2.2z"/></svg>
      <span class="absolute -top-1 -right-1 flex h-3.5 w-3.5">
        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-orange-400 opacity-75"></span>
        <span class="relative inline-flex rounded-full h-3.5 w-3.5 bg-brand-orange"></span>
      </span>
    </a>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/919942222824?text=Hello%20Mugil%20Travels!%20I%20would%20like%20to%20enquire%20about%20Force%20Urbania%20rental." target="_blank" title="WhatsApp Enquiry" class="w-14 h-14 rounded-full bg-[#25D366] text-white shadow-2xl flex items-center justify-center hover:scale-110 active:scale-95 transition-all border-2 border-white">
      <svg class="w-7 h-7" fill="currentColor" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M11.998 2C6.477 2 2 6.477 2 12c0 1.818.487 3.52 1.338 4.994L2 22l5.159-1.315A9.954 9.954 0 0011.998 22c5.52 0 9.998-4.477 9.998-9.998C21.996 6.479 17.519 2 11.998 2z"/></svg>
    </a>

  </div>

  <!-- ========================================================================= -->
  <!-- MODAL: FULL RESOLUTION POSTER VIEWER -->
  <!-- ========================================================================= -->
  <div id="posterModal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-sm hidden flex items-center justify-center p-4">
    <div class="relative max-w-lg w-full bg-white rounded-3xl overflow-hidden shadow-2xl border border-white/20">
      <button onclick="closePosterModal()" class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-black/60 text-white flex items-center justify-center hover:bg-black transition font-bold text-lg">
        ✕
      </button>
      <div class="p-2 bg-slate-900">
        <img src="mugil-travels-poster.jpg" alt="Mugil Travels Official Promotional Poster" class="w-full h-auto rounded-2xl" onerror="this.onerror=null; this.src='public/mugil-travels-poster.jpg'">
      </div>
      <div class="p-4 bg-white flex items-center justify-between">
        <div>
          <p class="font-bold text-slate-900 text-sm">Official Mugil Travels Poster</p>
          <p class="text-xs text-slate-500">Force Urbania · ₹33/KM</p>
        </div>
        <a href="mugil-travels-poster.jpg" download="Mugil_Travels_Poster.jpg" class="bg-brand-blue text-white text-xs font-bold px-4 py-2 rounded-xl hover:bg-blue-800 transition">
          Download Image
        </a>
      </div>
    </div>
  </div>


  <!-- ========================================================================= -->
  <!-- JAVASCRIPT: TAB NAVIGATION, BOOKING WIZARD, LOCALSTORAGE & ADMIN LOGIC -->
  <!-- ========================================================================= -->
  <script>
    // Poster Modal
    function openPosterModal() {
      document.getElementById('posterModal').classList.remove('hidden');
    }
    function closePosterModal() {
      document.getElementById('posterModal').classList.add('hidden');
    }

    // Tab switching engine
    function switchTab(tabId) {
      document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
      const activeEl = document.getElementById('tab-' + tabId);
      if (activeEl) {
        activeEl.classList.add('active');
        window.scrollTo({ top: 0, behavior: 'smooth' });
      }

      // Update Nav highlighting
      document.querySelectorAll('.nav-btn').forEach(btn => {
        if (btn.getAttribute('data-tab') === tabId) {
          btn.classList.add('text-brand-blue', 'bg-blue-50');
          btn.classList.remove('text-slate-600');
        } else {
          btn.classList.remove('text-brand-blue', 'bg-blue-50');
          btn.classList.add('text-slate-600');
        }
      });

      // Close mobile menu if open
      const mobileMenu = document.getElementById('mobileMenu');
      if (mobileMenu) mobileMenu.classList.add('hidden');

      if (tabId === 'admin') {
        checkAdminSession();
      }
    }

    function toggleMobileMenu() {
      const menu = document.getElementById('mobileMenu');
      menu.classList.toggle('hidden');
    }

    // Hero Quick Fare Calculator
    function calculateHeroFare() {
      const km = parseFloat(document.getElementById('calcKm').value) || 0;
      const type = document.getElementById('calcType').value;
      const rate = 33;
      const totalKm = type === 'round_trip' ? km * 2 : km;
      const fare = totalKm * rate;
      document.getElementById('calcResult').innerText = '₹' + fare.toLocaleString('en-IN');
      document.getElementById('calcBreakdown').innerText = `${totalKm} KM total @ ₹33/KM (${type === 'round_trip' ? 'Round Trip' : 'One Way'})`;
    }

    function openBookingWithEstimate() {
      const km = document.getElementById('calcKm').value;
      switchTab('booking');
      document.getElementById('bookingKm').value = km;
      updateBookingEstimate();
    }

    // Booking Wizard Logic
    let currentPax = 8;
    function adjustPax(delta) {
      currentPax = Math.max(1, Math.min(20, currentPax + delta));
      document.getElementById('paxCount').innerText = currentPax;
    }

    function onTripTypeChange() {
      const selected = document.querySelector('input[name="tripTypeRadio"]:checked')?.value || 'round-trip';
      const retDateContainer = document.getElementById('returnDateContainer');
      if (selected === 'one-way') {
        retDateContainer.classList.add('hidden');
      } else {
        retDateContainer.classList.remove('hidden');
      }
      updateBookingEstimate();
    }

    function goToStep(step) {
      // Validate step 1
      if (step === 2) {
        const name = document.getElementById('custName').value.trim();
        const phone = document.getElementById('custPhone').value.trim();
        const pickup = document.getElementById('pickupLoc').value.trim();
        const drop = document.getElementById('dropLoc').value.trim();
        const pDate = document.getElementById('pickupDate').value;

        let hasError = false;
        if (!name) { document.getElementById('errName').classList.remove('hidden'); hasError = true; } else { document.getElementById('errName').classList.add('hidden'); }
        if (!phone || phone.length < 10) { document.getElementById('errPhone').classList.remove('hidden'); hasError = true; } else { document.getElementById('errPhone').classList.add('hidden'); }
        if (!pickup) { document.getElementById('errPickup').classList.remove('hidden'); hasError = true; } else { document.getElementById('errPickup').classList.add('hidden'); }
        if (!drop) { document.getElementById('errDrop').classList.remove('hidden'); hasError = true; } else { document.getElementById('errDrop').classList.add('hidden'); }
        if (!pDate) { document.getElementById('errDate').classList.remove('hidden'); hasError = true; } else { document.getElementById('errDate').classList.add('hidden'); }

        if (hasError) return;
      }

      // Hide all steps
      document.getElementById('formStep1').classList.add('hidden');
      document.getElementById('formStep2').classList.add('hidden');
      document.getElementById('formStep3').classList.add('hidden');

      // Update badges
      document.getElementById('stepBadge1').className = step >= 1 ? 'w-8 h-8 rounded-full bg-brand-blue text-white flex items-center justify-center font-bold text-sm' : 'w-8 h-8 rounded-full bg-slate-200 text-slate-600 flex items-center justify-center font-bold text-sm';
      document.getElementById('stepBadge2').className = step >= 2 ? 'w-8 h-8 rounded-full bg-brand-blue text-white flex items-center justify-center font-bold text-sm' : 'w-8 h-8 rounded-full bg-slate-200 text-slate-600 flex items-center justify-center font-bold text-sm';
      document.getElementById('stepBadge3').className = step >= 3 ? 'w-8 h-8 rounded-full bg-brand-blue text-white flex items-center justify-center font-bold text-sm' : 'w-8 h-8 rounded-full bg-slate-200 text-slate-600 flex items-center justify-center font-bold text-sm';

      document.getElementById('formStep' + step).classList.remove('hidden');
      if (step === 3) updateBookingEstimate();
    }

    function updateBookingEstimate() {
      const km = parseFloat(document.getElementById('bookingKm').value) || 0;
      const tripType = document.querySelector('input[name="tripTypeRadio"]:checked')?.value || 'round-trip';
      const isRound = tripType !== 'one-way';
      const totalKm = isRound ? km * 2 : km;
      const fare = totalKm * 33;

      document.getElementById('breakdownKmLabel').innerText = `Distance Calculation (${km} KM ${isRound ? '× 2 (Round Trip)' : ''} × ₹33/KM):`;
      document.getElementById('breakdownTotal').innerText = '₹' + fare.toLocaleString('en-IN');
      document.getElementById('finalEstimatedFare').innerText = '₹' + fare.toLocaleString('en-IN');
    }

    // Submit Booking & Save to LocalStorage
    function submitBookingRequest() {
      const name = document.getElementById('custName').value.trim();
      const phone = document.getElementById('custPhone').value.trim();
      const wa = document.getElementById('custWa').value.trim() || phone;
      const pickup = document.getElementById('pickupLoc').value.trim();
      const drop = document.getElementById('dropLoc').value.trim();
      const pDate = document.getElementById('pickupDate').value;
      const pTime = document.getElementById('pickupTime').value;
      const rDate = document.getElementById('returnDate').value;
      const tripType = document.querySelector('input[name="tripTypeRadio"]:checked')?.value || 'round-trip';
      const km = parseFloat(document.getElementById('bookingKm').value) || 200;
      const totalKm = tripType !== 'one-way' ? km * 2 : km;
      const fare = totalKm * 33;
      const reqs = document.getElementById('reqs').value.trim();
      const instructions = document.getElementById('instructions').value.trim();

      const bookingId = 'MT-' + Date.now().toString(36).toUpperCase() + '-' + Math.random().toString(36).substring(2, 6).toUpperCase();

      const newBooking = {
        id: bookingId,
        booking_id: bookingId,
        customer_name: name,
        customer_phone: phone,
        customer_whatsapp: wa,
        pickup_location: pickup,
        drop_location: drop,
        travel_date: pDate,
        pickup_time: pTime,
        return_date: rDate,
        trip_type: tripType,
        passengers: currentPax,
        estimated_distance_km: totalKm,
        estimated_fare: fare,
        final_price: fare,
        status: 'New Enquiry',
        special_requirements: [reqs, instructions].filter(Boolean).join('\n'),
        created_at: new Date().toISOString()
      };

      // Save to localStorage
      const existing = getStoredBookings();
      existing.unshift(newBooking);
      localStorage.setItem('mugil_bookings', JSON.stringify(existing));

      // Show Confirmation Screen
      document.getElementById('formStep3').classList.add('hidden');
      document.getElementById('confName').innerText = name;
      document.getElementById('confId').innerText = bookingId;
      document.getElementById('confRoute').innerText = `${pickup} → ${drop}`;
      document.getElementById('confDate').innerText = `${pDate} (${pTime})`;
      document.getElementById('confFare').innerText = '₹' + fare.toLocaleString('en-IN');

      const waMsg = encodeURIComponent(
        `Hello Mugil Travels!\n\n` +
        `🆔 Booking ID: ${bookingId}\n` +
        `👤 Name: ${name}\n` +
        `📍 Pickup: ${pickup}\n` +
        `🏁 Destination: ${drop}\n` +
        `📅 Date: ${pDate}\n` +
        `👥 Passengers: ${currentPax}\n` +
        `💰 Est. Fare: ₹${fare.toLocaleString('en-IN')} (₹33/KM)\n\n` +
        `Please confirm Force Urbania availability and final quotation. Thank you!`
      );
      document.getElementById('btnConfWa').href = `https://wa.me/919942222824?text=${waMsg}`;

      document.getElementById('bookingConfirmation').classList.remove('hidden');
    }

    function resetBookingForm() {
      document.getElementById('bookingConfirmation').classList.add('hidden');
      goToStep(1);
    }

    // Contact Form WhatsApp sender
    function sendContactWhatsApp() {
      const name = document.getElementById('contactName').value.trim() || 'Visitor';
      const phone = document.getElementById('contactPhone').value.trim() || 'Not specified';
      const msg = document.getElementById('contactMsg').value.trim() || 'I am interested in Force Urbania rental.';
      const text = encodeURIComponent(`Hello Mugil Travels!\n\nName: ${name}\nPhone: ${phone}\nRequirement: ${msg}`);
      window.open(`https://wa.me/919942222824?text=${text}`, '_blank');
    }

    // =========================================================================
    // ADMIN DASHBOARD JAVASCRIPT (LOCALSTORAGE DRIVEN)
    // =========================================================================
    const DEFAULT_BOOKINGS = [
      {
        id: 'MT-LATEST-001',
        booking_id: 'MT-1715600000000-AB12',
        customer_name: 'Senthil Kumar',
        customer_phone: '9840123456',
        pickup_location: 'Coimbatore Airport',
        drop_location: 'Ooty Boat House',
        travel_date: '2026-11-20',
        trip_type: 'round-trip',
        passengers: 8,
        estimated_distance_km: 180,
        estimated_fare: 11880,
        status: 'New Enquiry',
        created_at: new Date().toISOString()
      },
      {
        id: 'MT-LATEST-002',
        booking_id: 'MT-1715500000000-CD34',
        customer_name: 'Dr. Ananya Natarajan',
        customer_phone: '9443188990',
        pickup_location: 'Madurai Junction',
        drop_location: 'Rameshwaram Temple',
        travel_date: '2026-11-22',
        trip_type: 'round-trip',
        passengers: 12,
        estimated_distance_km: 340,
        estimated_fare: 22440,
        status: 'Confirmed',
        created_at: new Date(Date.now() - 86400000).toISOString()
      },
      {
        id: 'MT-LATEST-003',
        booking_id: 'MT-1715400000000-EF56',
        customer_name: 'Karthik Raja',
        customer_phone: '9884011223',
        pickup_location: 'Salem New Bus Stand',
        drop_location: 'Yercaud Lake',
        travel_date: '2026-11-18',
        trip_type: 'one-way',
        passengers: 6,
        estimated_distance_km: 65,
        estimated_fare: 2145,
        status: 'Completed',
        created_at: new Date(Date.now() - 172800000).toISOString()
      }
    ];

    function getStoredBookings() {
      const data = localStorage.getItem('mugil_bookings');
      if (!data) {
        localStorage.setItem('mugil_bookings', JSON.stringify(DEFAULT_BOOKINGS));
        return DEFAULT_BOOKINGS;
      }
      try {
        return JSON.parse(data);
      } catch {
        return DEFAULT_BOOKINGS;
      }
    }

    function checkAdminSession() {
      const isAuth = localStorage.getItem('mugil_admin_auth') === 'true';
      if (isAuth) {
        document.getElementById('adminLoginBox').classList.add('hidden');
        document.getElementById('adminDashboardView').classList.remove('hidden');
        renderAdminBookings();
      } else {
        document.getElementById('adminLoginBox').classList.remove('hidden');
        document.getElementById('adminDashboardView').classList.add('hidden');
      }
    }

    function handleAdminLogin() {
      const pass = document.getElementById('adminPassInput').value.trim();
      if (pass === 'mugiladmin123' || pass === 'admin' || pass === 'mugil123') {
        localStorage.setItem('mugil_admin_auth', 'true');
        document.getElementById('adminLoginError').classList.add('hidden');
        checkAdminSession();
      } else {
        document.getElementById('adminLoginError').classList.remove('hidden');
      }
    }

    function handleAdminLogout() {
      localStorage.removeItem('mugil_admin_auth');
      checkAdminSession();
    }

    function seedSampleData() {
      localStorage.setItem('mugil_bookings', JSON.stringify(DEFAULT_BOOKINGS));
      renderAdminBookings();
    }

    function updateBookingStatusLocal(id, newStatus) {
      const bookings = getStoredBookings();
      const updated = bookings.map(b => b.id === id ? { ...b, status: newStatus } : b);
      localStorage.setItem('mugil_bookings', JSON.stringify(updated));
      renderAdminBookings();
    }

    function renderAdminBookings() {
      const bookings = getStoredBookings();
      const search = (document.getElementById('adminSearch')?.value || '').toLowerCase();
      const statusFilter = document.getElementById('adminStatusFilter')?.value || '';

      const filtered = bookings.filter(b => {
        if (statusFilter && b.status !== statusFilter) return false;
        if (search) {
          const matchName = (b.customer_name || '').toLowerCase().includes(search);
          const matchPhone = (b.customer_phone || '').includes(search);
          const matchId = (b.booking_id || '').toLowerCase().includes(search);
          const matchLoc = (b.pickup_location || '').toLowerCase().includes(search);
          if (!matchName && !matchPhone && !matchId && !matchLoc) return false;
        }
        return true;
      });

      // Update KPI counters
      document.getElementById('statTotal').innerText = bookings.length;
      document.getElementById('statNew').innerText = bookings.filter(b => b.status === 'New Enquiry').length;
      document.getElementById('statConfirmed').innerText = bookings.filter(b => b.status === 'Confirmed').length;
      document.getElementById('statCompleted').innerText = bookings.filter(b => b.status === 'Completed').length;

      const tbody = document.getElementById('adminBookingsTable');
      if (!tbody) return;

      if (filtered.length === 0) {
        tbody.innerHTML = `<tr><td colspan="8" class="text-center py-8 text-slate-400 text-xs">No matching bookings found</td></tr>`;
        return;
      }

      tbody.innerHTML = filtered.map(b => {
        const statusColors = {
          'New Enquiry': 'bg-blue-100 text-blue-800',
          'Contacted': 'bg-yellow-100 text-yellow-800',
          'Quotation Sent': 'bg-purple-100 text-purple-800',
          'Confirmed': 'bg-green-100 text-green-800',
          'Completed': 'bg-teal-100 text-teal-800',
          'Cancelled': 'bg-red-100 text-red-800'
        }[b.status] || 'bg-slate-100 text-slate-800';

        const waMsg = encodeURIComponent(`Hello ${b.customer_name}! This is Mugil Travels regarding your Force Urbania booking (${b.booking_id}) from ${b.pickup_location} to ${b.drop_location}.`);

        return `
          <tr class="hover:bg-slate-50 transition">
            <td class="px-5 py-3.5 font-mono text-xs font-bold text-brand-blue">${b.booking_id}</td>
            <td class="px-5 py-3.5">
              <p class="font-bold text-slate-900">${b.customer_name}</p>
              <p class="text-xs text-slate-400">${b.customer_phone}</p>
            </td>
            <td class="px-5 py-3.5">
              <p class="text-slate-800 text-xs">${b.pickup_location}</p>
              <p class="text-slate-400 text-[11px]">→ ${b.drop_location}</p>
            </td>
            <td class="px-5 py-3.5 text-xs text-slate-700 whitespace-nowrap">${b.travel_date}</td>
            <td class="px-5 py-3.5 text-xs text-center font-bold">${b.passengers}</td>
            <td class="px-5 py-3.5 text-xs font-bold text-slate-900 whitespace-nowrap">₹${(b.estimated_fare || 0).toLocaleString('en-IN')}</td>
            <td class="px-5 py-3.5 whitespace-nowrap">
              <select onchange="updateBookingStatusLocal('${b.id}', this.value)" class="text-xs font-bold rounded-lg px-2 py-1 border border-slate-200 outline-none ${statusColors}">
                <option value="New Enquiry" ${b.status === 'New Enquiry' ? 'selected' : ''}>New Enquiry</option>
                <option value="Contacted" ${b.status === 'Contacted' ? 'selected' : ''}>Contacted</option>
                <option value="Quotation Sent" ${b.status === 'Quotation Sent' ? 'selected' : ''}>Quotation Sent</option>
                <option value="Confirmed" ${b.status === 'Confirmed' ? 'selected' : ''}>Confirmed</option>
                <option value="Completed" ${b.status === 'Completed' ? 'selected' : ''}>Completed</option>
                <option value="Cancelled" ${b.status === 'Cancelled' ? 'selected' : ''}>Cancelled</option>
              </select>
            </td>
            <td class="px-5 py-3.5 text-right whitespace-nowrap space-x-2">
              <a href="https://wa.me/91${b.customer_phone}?text=${waMsg}" target="_blank" class="inline-block bg-green-50 hover:bg-green-100 text-green-700 text-xs font-bold px-2.5 py-1 rounded-lg border border-green-200">
                💬 WA
              </a>
              <a href="tel:+91${b.customer_phone}" class="inline-block bg-blue-50 hover:bg-blue-100 text-brand-blue text-xs font-bold px-2.5 py-1 rounded-lg border border-blue-200">
                📞 Call
              </a>
            </td>
          </tr>
        `;
      }).join('');
    }

    // Export CSV directly in browser
    function exportBookingsCSV() {
      const bookings = getStoredBookings();
      const headers = ['Booking ID', 'Name', 'Phone', 'Pickup', 'Destination', 'Date', 'Passengers', 'Status', 'Estimated Fare'];
      const rows = bookings.map(b => [
        b.booking_id,
        b.customer_name,
        b.customer_phone,
        b.pickup_location,
        b.drop_location,
        b.travel_date,
        b.passengers,
        b.status,
        b.estimated_fare
      ]);

      const csvContent = [headers, ...rows].map(e => e.map(v => `"${String(v || '').replace(/"/g, '""')}"`).join(",")).join("\n");
      const blob = new Blob(["\uFEFF" + csvContent], { type: 'text/csv;charset=utf-8;' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = `mugil_travels_bookings_${Date.now()}.csv`;
      a.click();
      URL.revokeObjectURL(url);
    }

    // Set today as default date on load
    window.addEventListener('DOMContentLoaded', () => {
      const today = new Date().toISOString().split('T')[0];
      const pDateInput = document.getElementById('pickupDate');
      if (pDateInput) {
        pDateInput.min = today;
        pDateInput.value = today;
      }
      calculateHeroFare();
    });
  </script>

</body>
</html>
