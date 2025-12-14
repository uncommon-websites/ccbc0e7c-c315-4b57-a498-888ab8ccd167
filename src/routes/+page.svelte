<script>
  import VideoCard from "$lib/components/VideoCard.svelte";
</script>

<div class="pt-32 pb-20">
  <!-- Hero Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-24">
    <h1 class="text-[clamp(3rem,8vw,6rem)] leading-[0.9] font-medium text-center mb-12 tracking-tight">
      Say hello to Memo
    </h1>
    
    <div class="w-full aspect-[16/10] bg-gray-200 rounded-2xl overflow-hidden mb-12 relative">
      <!-- Placeholder for Hero Image -->
      <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=2670&auto=format&fit=crop')] bg-cover bg-center opacity-90"></div>
      <div class="absolute inset-0 flex items-center justify-center">
        <!-- Play button overlay if it's a video -->
      </div>
    </div>

    <div class="max-w-2xl">
      <p class="text-xl md:text-2xl leading-relaxed text-gray-800">
        Built for busy households, Memo works 24/7 to make your life lighter. Hand off your repetitive to-do's, so you can focus on what really matters.
      </p>
    </div>
  </section>

  <!-- Intro Video Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-40">
    <div class="flex flex-col md:flex-row items-end justify-between gap-12">
      <div class="max-w-xs mb-8 md:mb-0">
        <p class="text-xs font-medium leading-relaxed text-gray-500 uppercase tracking-wide">
          Robots should give you back what matters most — time. Watch how our team came together to work on this mission.
        </p>
      </div>
      <div class="w-full md:w-[400px]">
        <VideoCard 
          imageSrc="" 
          alt="Team working on mission"
          title="Our Story"
          subtitle="Watch"
        />
      </div>
    </div>
  </section>

  <!-- Mundane Made Magic -->
  <section class="max-w-[1000px] mx-auto px-4 mb-40">
    <div class="flex flex-col gap-8 text-[clamp(4rem,10vw,9rem)] leading-[0.8] tracking-tight font-medium">
      <div class="text-left">Mundane</div>
      <div class="text-center pl-[20%]">made</div>
      <div class="text-right pr-[10%]">magic</div>
    </div>
  </section>

  <!-- Kitchen Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="max-w-2xl mx-auto text-center mb-16">
      <p class="text-lg text-gray-600 leading-relaxed">
        Powered by state-of-the-art AI models and an ever-expanding Skill Library, Memo doesn't just know how to do a few tasks—Memo improves its skills faster than any robot that has come before it.
      </p>
    </div>

    <div class="grid grid-cols-1 gap-4">
      <!-- Main Kitchen Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden group">
        <div class="absolute inset-0 flex items-center justify-center text-gray-400">
          Image: Memo works in the kitchen
        </div>
        <div class="absolute bottom-8 left-8 md:bottom-12 md:left-12">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight">Memo works in the kitchen</h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          01
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div class="aspect-[4/3] bg-gray-200 rounded-2xl overflow-hidden relative p-8 flex items-end">
           <p class="text-xs text-gray-600 max-w-xs">
             Memo can quietly and autonomously clear tables of plates and delicate glasses, throw out food scraps, and load up your dishwasher before running it. Let Memo take care of the mess, so you can go take care of the things only you can do.
           </p>
           <div class="absolute top-4 left-4 text-[10px] text-gray-400 uppercase tracking-wider">Lightening the load</div>
        </div>
        <div class="aspect-[4/3] bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">
            Image: Robot in living room
          </div>
          <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">Spot check: A magic moment</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Homes Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Homes Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
        <div class="absolute inset-0 flex items-center justify-center text-gray-400">
          Image: Memo works in homes it's never seen
        </div>
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center max-w-2xl">
            Memo works in<br/>homes it's never seen
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          02
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">A new home is Memo's terrain.</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             We believe Memo should be easy to use in the real world, starting autonomously out of the box. Hundreds of people in unique homes show Memo their environments each day, so Memo can robustly handle the chaos of real life.
           </p>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">01. Unboxing</span>
          </div>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">02. Learning a new home concept</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Learning Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-40">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Learning Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
        <div class="absolute inset-0 flex items-center justify-center text-gray-400">
          Image: Memo is always learning
        </div>
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center">
            Memo is always learning
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          03
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">Teach it once, it learns.</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             In December 2024, Memo had only one skill. Just six months later, it's managing dishes, laundry, and tidying up. Memo continues to learn fast. Give it time, teach it patience, and watch it unlock happiness.
           </p>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">A. Memo doing laundry</span>
          </div>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">B. Memo tidying up around the house</span>
          </div>
        </div>
      </div>
    </div>
  <!-- Imitation to Intuition -->
  <section class="bg-[#E3EBE6] py-32 mb-32 -mx-4 md:-mx-8 px-4 md:px-8">
    <div class="max-w-[1400px] mx-auto">
      <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-tight font-medium text-center mb-20 tracking-tight text-balance max-w-4xl mx-auto">
        From imitation to intuition
      </h2>

      <div class="flex flex-col items-center mb-20">
        <div class="w-full max-w-md aspect-[3/4] bg-gray-300 rounded-2xl overflow-hidden relative mb-12">
          <div class="absolute inset-0 flex items-center justify-center text-gray-500">
            Image: Hand holding glove
          </div>
        </div>
        
        <div class="max-w-xl text-center">
          <p class="text-lg text-gray-700 leading-relaxed">
            Our Skill Capture Glove™ enables Memo to distill millions of human movements into its onboard AI, unlocking helpful home skills. What the glove does, Memo learns.
          </p>
        </div>
      </div>

      <div class="max-w-4xl mx-auto">
        <VideoCard 
          imageSrc="" 
          alt="Skill Capture Glove Demo"
          title="Skill Capture Glove in use"
          subtitle=""
        />
        <div class="text-center mt-12 space-y-2">
          <p class="text-xs text-gray-500 leading-relaxed max-w-xs mx-auto">
            To date, we've logged over 5,000 hours in our Motion Database. This robust training is what makes Memo useful in yours.
          </p>
          <div class="flex justify-center gap-8 pt-4 text-[10px] uppercase tracking-wider font-medium">
            <a href="#" class="border-b border-black pb-0.5">Explore Technology</a>
            <a href="#" class="border-b border-black pb-0.5">Become a MemDev</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Designed for real use -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="text-center mb-16">
      <h2 class="text-[clamp(3rem,6vw,5rem)] leading-tight font-medium mb-8 tracking-tight">
        Designed for real<br/>use
      </h2>
      
      <div class="inline-flex bg-white rounded-full p-1 border border-gray-200">
        <button class="px-4 py-1.5 rounded-full bg-black text-white text-xs font-medium">Features</button>
        <button class="px-4 py-1.5 rounded-full hover:bg-gray-100 text-gray-500 text-xs font-medium transition-colors">360°</button>
        <button class="px-4 py-1.5 rounded-full hover:bg-gray-100 text-gray-500 text-xs font-medium transition-colors">Anatomy</button>
      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 mb-32">
      <!-- Card 1: Privacy -->
      <div class="aspect-square bg-[#1a1a1a] rounded-2xl overflow-hidden relative group">
        <!-- Abstract Camera Lens / Privacy visual -->
        <div class="absolute inset-0 flex items-center justify-center">
            <div class="w-32 h-32 rounded-full bg-[#2a2a2a] border border-[#333] flex items-center justify-center">
                <div class="w-16 h-16 rounded-full bg-[#111] border border-[#222]"></div>
            </div>
        </div>
        <div class="absolute top-6 left-6 right-6">
          <h3 class="text-white text-sm font-bold mb-2">Your privacy is protected</h3>
          <p class="text-[10px] text-gray-400 leading-relaxed">
            Memo is an autonomous robot that operates device-first. Through systematic operation, culture, we ensure exactly how much (or how little) is known about your most private spaces.
          </p>
        </div>
      </div>

      <!-- Card 2: Safety -->
      <div class="aspect-square bg-[#F0EFE9] rounded-2xl p-6 flex flex-col justify-between overflow-hidden relative">
         <div class="relative z-10">
            <h3 class="text-black text-sm font-bold mb-2">Safety for the whole family</h3>
            <p class="text-[10px] text-gray-500 leading-relaxed">
            With a low center of gravity, stable wheelbase, with no sharp corners and can be wiped down with any household cleaning product.
            </p>
         </div>
         <!-- Orange abstract shape -->
         <div class="absolute -bottom-10 -right-10 w-48 h-48 bg-[#FF4500] rounded-full blur-xl opacity-80"></div>
         <div class="absolute bottom-0 right-0 w-full h-1/2 bg-gradient-to-t from-[#FF4500] to-transparent opacity-20"></div>
         <div class="w-full h-40 bg-[#FF4500] rounded-full absolute -bottom-20 left-1/2 -translate-x-1/2"></div>
      </div>

      <!-- Card 3: Close up -->
      <div class="aspect-square bg-gray-200 rounded-2xl overflow-hidden relative">
         <img src="https://images.unsplash.com/photo-1589254065878-42c9da997008?q=80&w=2670&auto=format&fit=crop" alt="Close up" class="w-full h-full object-cover" />
      </div>
      
       <!-- Card 4: Tailored (Colorful balls) -->
      <div class="aspect-square bg-[#333] rounded-2xl overflow-hidden relative">
         <!-- CSS Art for colorful balls -->
         <div class="absolute inset-0">
            <div class="absolute top-10 left-10 w-20 h-20 rounded-full bg-yellow-400 shadow-lg"></div>
            <div class="absolute top-20 right-10 w-24 h-24 rounded-full bg-red-500 shadow-lg z-10"></div>
            <div class="absolute bottom-10 left-20 w-28 h-28 rounded-full bg-blue-500 shadow-lg"></div>
            <div class="absolute bottom-20 right-20 w-16 h-16 rounded-full bg-green-400 shadow-lg"></div>
            <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-32 h-32 rounded-full bg-white/10 backdrop-blur-md z-20"></div>
         </div>
         <div class="absolute top-6 left-6 right-6 z-30">
          <h3 class="text-white text-sm font-bold mb-2">Tailored to your home</h3>
          <p class="text-[10px] text-gray-300 leading-relaxed">
            Customize Memo to fit your aesthetic with a selection of color-ways and personalized hats.
          </p>
        </div>
      </div>

      <!-- Card 5: Simple, soft -->
      <div class="aspect-square bg-[#B8C6C0] rounded-2xl p-6 flex flex-col justify-between overflow-hidden relative">
         <div class="relative z-10">
            <h3 class="text-black text-sm font-bold mb-2">Simple, soft and easy to clean</h3>
            <p class="text-[10px] text-gray-700 leading-relaxed">
            Memo has a soft-to-the-touch silicone shell, with no sharp corners and can be wiped down with any household cleaning product.
            </p>
         </div>
         <!-- Grid texture -->
         <div class="absolute inset-0 opacity-20" style="background-image: linear-gradient(#000 1px, transparent 1px), linear-gradient(90deg, #000 1px, transparent 1px); background-size: 20px 20px;"></div>
      </div>

      <!-- Card 6: Hand touch -->
      <div class="aspect-square bg-yellow-400 rounded-2xl overflow-hidden relative">
         <img src="https://images.unsplash.com/photo-1616627561839-074385245c90?q=80&w=2574&auto=format&fit=crop" alt="Hand touch" class="w-full h-full object-cover mix-blend-multiply opacity-80" />
         <div class="absolute inset-0 bg-yellow-400/30 mix-blend-overlay"></div>
      </div>
    </div>
    
    <!-- Repeat Tabs for visual consistency if needed or just bottom spacing -->
    <div class="flex justify-center">
       <div class="inline-flex bg-white rounded-full p-1 border border-gray-200 opacity-50 pointer-events-none">
        <button class="px-4 py-1.5 rounded-full bg-black text-white text-xs font-medium">Features</button>
        <button class="px-4 py-1.5 rounded-full text-gray-500 text-xs font-medium">360°</button>
        <button class="px-4 py-1.5 rounded-full text-gray-500 text-xs font-medium">Anatomy</button>
      </div>
    </div>
  </section>

  <!-- Hats Section -->
  <section class="bg-[#DCEBEF] py-40 -mx-4 md:-mx-8 px-4 md:px-8 flex flex-col items-center text-center">
    <div class="flex flex-col md:flex-row items-center justify-between w-full max-w-2xl mb-12 gap-8">
      <span class="text-xs font-medium text-gray-500">Memo wears many hats.</span>
      
      <div class="w-24 h-24 text-black">
        <!-- Flower/Icon -->
        <svg viewBox="0 0 100 100" fill="currentColor" class="w-full h-full animate-spin-slow">
          <path d="M50 20C58 20 65 27 65 35C65 43 58 50 50 50C42 50 35 43 35 35C35 27 42 20 50 20Z" />
          <path d="M50 80C42 80 35 73 35 65C35 57 42 50 50 50C58 50 65 57 65 65C65 73 58 80 50 80Z" />
          <path d="M20 50C20 42 27 35 35 35C43 35 50 42 50 50C50 58 43 65 35 65C27 65 20 58 20 50Z" />
          <path d="M80 50C80 58 73 65 65 65C57 65 50 58 50 50C50 42 57 35 65 35C73 35 80 42 80 50Z" />
        </svg>
      </div>

      <span class="text-xs font-medium text-gray-500">Which should it wear next?</span>
    </div>

    <button class="bg-black text-white px-8 py-3 rounded-full text-xs font-bold uppercase tracking-wider hover:scale-105 transition-transform">
      Cast your vote now
    </button>
  </section>

  <!-- FAQ Section -->
  <section class="max-w-[800px] mx-auto px-4 py-32">
    <h3 class="text-xs font-medium text-gray-500 mb-12">Frequently asked questions</h3>
    
    <div class="space-y-4">
      {#each [
        "What can Memo do?",
        "Is Memo available for purchase?",
        "How much will a Memo cost?",
        "How big is Memo? How fast can Memo move?",
        "Is Memo safe?",
        "What is the Sunday Beta program?"
      ] as question}
        <div class="border-b border-gray-200 pb-4 group cursor-pointer">
          <div class="flex items-center justify-between py-2">
            <span class="text-sm font-medium group-hover:text-gray-600 transition-colors">{question}</span>
            <span class="text-gray-400 group-hover:text-black transition-colors">
              <svg width="10" height="6" viewBox="0 0 10 6" fill="none" class="transform transition-transform group-hover:rotate-180">
                <path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </span>
          </div>
        </div>
      {/each}
    </div>
  </section>

  <!-- Founding Families Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-20">
    <div class="bg-[#111111] rounded-2xl p-12 md:p-24 text-center relative overflow-hidden">
      <div class="relative z-10 flex flex-col items-center gap-6">
        <h2 class="text-white text-xl md:text-2xl font-medium tracking-tight">
          Be one of our Founding Families. <span class="text-[#FCEE4F]">Insider access. Exclusive perks. Design input.</span>
        </h2>
        <button class="inline-flex items-center gap-2 px-6 py-2 rounded-full border border-white/20 text-white text-xs uppercase tracking-wider hover:bg-white/10 transition-colors">
          Beta program
          <svg width="10" height="10" viewBox="0 0 10 10" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M1 9L9 1M9 1H3M9 1V7" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
      </div>
      
      <!-- Background gradient/glow -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full max-w-2xl max-h-2xl bg-gradient-to-r from-blue-900/20 to-purple-900/20 blur-3xl rounded-full pointer-events-none"></div>
    </div>
  </section>

</div>

