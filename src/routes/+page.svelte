<script>
  import VideoCard from "$lib/components/VideoCard.svelte";
</script>

<div class="pb-20">
  <!-- Hero Section - ALREADY CUSTOMIZED, DO NOT MODIFY -->
  <section class="pt-32 pb-12 px-4 sm:px-6">
    <div class="text-center max-w-4xl mx-auto mb-12">
      <div class="flex flex-col items-center justify-center space-y-1 mb-6">
        <p class="text-[#475569] text-sm font-medium">Unified creator operations</p>
        <p class="text-gray-400 text-xs">Replace manager commissions with AI agents</p>
      </div>
      
      <h1 class="text-5xl md:text-7xl lg:text-[5.5rem] leading-none font-medium text-gray-900 tracking-tight">
        Your business on autopilot
      </h1>
    </div>

    <div class="relative w-full max-w-[1400px] mx-auto">
      <div class="rounded-3xl overflow-hidden shadow-sm aspect-[16/9] md:aspect-[21/9] lg:aspect-[16/8] bg-gray-100">
        <img src="https://imolwncbqxugevwmleed.supabase.co/storage/v1/object/public/public-assets/hero-images/ccbc0e7c-c315-4b57-a498-888ab8ccd167/hero-1-img-0-1770165821847.png" 
             alt="CreatorOS Dashboard Preview" 
             class="w-full h-full object-cover">
      </div>

      <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 w-full max-w-max px-4">
        <button class="group bg-[#FCE844] hover:bg-[#fde047] transition-all duration-300 text-gray-900 rounded-full px-6 py-3.5 flex items-center justify-center gap-6 shadow-lg mx-auto">
          <span class="font-medium text-sm tracking-tight">Scale your business</span>
          <span class="font-light text-sm text-gray-800 flex items-center gap-2">
            Join the waitlist
            <span class="w-1.5 h-1.5 bg-black rounded-full"></span>
          </span>
        </button>
      </div>
    </div>
  </section>

  <!-- Value Proposition Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32 mt-24">
    <div class="max-w-3xl mx-auto text-center">
      <p class="text-xl md:text-2xl leading-relaxed text-gray-800">
        CreatorOS replaces spreadsheets, inbox chaos, and part-time managers with AI agents that handle sponsorships, finances, growth, and community. All in one place.
      </p>
    </div>
  </section>

  <!-- Big Statement -->
  <section class="max-w-[1000px] mx-auto px-4 mb-40">
    <div class="flex flex-col gap-8 text-[clamp(3rem,8vw,7rem)] leading-[0.85] tracking-tight font-medium">
      <div class="text-left">All the business,</div>
      <div class="text-center pl-[15%]">none of the</div>
      <div class="text-right pr-[10%]">busywork</div>
    </div>
  </section>

  <!-- Features Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Feature Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden group">
        <img src="/generated/image-professional-creator-working-at-desk-wit-1770166419480-0.webp" alt="AI Agents Managing Creator Business" class="w-full h-full object-cover" />
        <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent"></div>
        <div class="absolute bottom-8 left-8 md:bottom-12 md:left-12">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight">AI agents that work 24/7</h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          01
        </div>
      </div>

      <!-- Sub Features Row -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div class="aspect-[4/3] bg-white rounded-2xl overflow-hidden relative p-8 flex flex-col justify-between">
           <div class="absolute top-4 left-4 text-[10px] text-gray-400 uppercase tracking-wider">Deals Agent</div>
           <p class="text-sm text-gray-700 max-w-xs">
             Automate brand outreach, negotiation, and payment tracking. Handle sponsorships start to finish without the back-and-forth.
           </p>
        </div>
        <div class="aspect-[4/3] bg-gray-200 rounded-2xl overflow-hidden relative">
           <img src="/generated/image-young-content-creator-reviewing-brand-de-1770166422132-1.webp" alt="Deal Management" class="w-full h-full object-cover" />
           <div class="absolute inset-0 bg-gradient-to-t from-black/40 to-transparent"></div>
          <div class="absolute bottom-4 left-4 text-white">
            <span class="text-xs font-medium">Brand partnerships simplified</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Finance & Growth Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Finance Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
        <img src="/generated/image-creator-analyzing-financial-dashboard-wi-1770166424193-2.webp" alt="Financial Dashboard" class="w-full h-full object-cover" />
        <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent"></div>
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center max-w-2xl">
            Track revenue and<br/>expenses in real time
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          02
        </div>
      </div>

      <!-- Sub Features Row -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">Finance Agent</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             Get reports, reconcile payments, and plan your runway. No more spreadsheet chaos or missed invoices.
           </p>
        </div>
        <div class="aspect-square md:aspect-auto md:h-64 bg-gray-50 rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">Growth Agent</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             Test content strategies, optimize revenue, and spot viral trends early. Scale without more grunt work.
           </p>
        </div>
        <div class="aspect-square md:aspect-auto md:h-64 bg-gray-100 rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">Community Agent</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             Manage community, launch drops, and build a direct relationship with fans. Own your audience.
           </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Target Audience Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-40">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
        <img src="/generated/image-youtuber-filming-content-in-home-studio--1770166426781-3.webp" alt="Creator in studio" class="w-full h-full object-cover" />
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent"></div>
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center max-w-3xl px-4">
            Built for emerging-pro creators
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          03
        </div>
      </div>

      <!-- Sub Content Row -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-8 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">The $10K-$100K stage</p>
           <p class="text-sm text-gray-700 leading-relaxed">
             You're earning real money, but stuck between DIY tools and expensive managers. CreatorOS gives you the infrastructure to scale—without the 15-20% commission.
           </p>
        </div>
        <div class="aspect-square md:aspect-auto md:h-64 bg-gray-50 rounded-2xl p-8 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">Starting with YouTubers & TikTokers</p>
           <p class="text-sm text-gray-700 leading-relaxed">
             We're laser-focused on video creators who need business infrastructure but lack operational systems to scale. If you're serious about growth, CreatorOS is for you.
           </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Social Proof Section -->
  <section class="bg-gray-50 py-32 mb-32 -mx-4 md:-mx-8 px-4 md:px-8">
    <div class="max-w-[1400px] mx-auto">
      <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-tight font-medium text-center mb-20 tracking-tight text-balance max-w-4xl mx-auto">
        Like having a business manager—without giving up 20%
      </h2>

      <div class="flex flex-col items-center mb-20">
        <div class="w-full max-w-md aspect-[3/4] bg-gray-300 rounded-2xl overflow-hidden relative mb-12">
          <img src="/generated/image-confident-female-creator-smiling-while-r-1770166430691-5.webp" alt="Successful creator" class="w-full h-full object-cover" />
        </div>
        
        <div class="max-w-xl text-center">
          <p class="text-lg text-gray-700 leading-relaxed mb-4">
            "Emerging-pro creators are stuck: $10K-$100K/month in earnings, but no infrastructure to grow. We built CreatorOS for this exact stage."
          </p>
          <p class="text-sm text-gray-500">Replace commissions with software.</p>
        </div>
      </div>

      <div class="max-w-4xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div class="bg-white rounded-2xl p-8">
            <h3 class="text-sm font-medium mb-4">Built by operators who've been there</h3>
            <p class="text-xs text-gray-600 leading-relaxed">
              Co-founder Michele built media ops from the inside at Wonder Media Network. Moe led systems architecture across 200+ AWS architects. Together, we built CreatorOS to run your business like a business—without turning you into a manager.
            </p>
          </div>
          <div class="bg-white rounded-2xl p-8">
            <h3 class="text-sm font-medium mb-4">Join the OS for the $70B creator economy</h3>
            <p class="text-xs text-gray-600 leading-relaxed">
              Start free. Let AI handle the overhead. Focus on what got you here—creating. Join 8-10M emerging-pro creators who need business infrastructure to scale.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Community Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
      <img src="/generated/image-diverse-group-of-content-creators-collab-1770166428737-4.webp" alt="Creator community" class="w-full h-full object-cover" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent"></div>
      <div class="absolute bottom-12 left-12 right-12">
        <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight mb-4">
          Join the creator community
        </h2>
        <p class="text-white/90 text-sm max-w-xl">
          Connect with other emerging-pro creators, share strategies, and grow together. CreatorOS is more than software—it's a community.
        </p>
      </div>
    </div>
  </section>

  <!-- FAQ Section -->
  <section class="max-w-[800px] mx-auto px-4 py-32">
    <h3 class="text-xs font-medium text-gray-500 mb-12 uppercase tracking-wider">Frequently asked questions</h3>
    
    <div class="space-y-4">
      {#each [
        "What does CreatorOS do?",
        "How much does CreatorOS cost?",
        "What makes CreatorOS different from other creator tools?",
        "Who is CreatorOS built for?",
        "How do the AI agents work?",
        "When can I start using CreatorOS?"
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

  <!-- CTA Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-20">
    <div class="bg-[#111111] rounded-2xl p-12 md:p-24 text-center relative overflow-hidden">
      <div class="relative z-10 flex flex-col items-center gap-6">
        <h2 class="text-white text-2xl md:text-4xl font-medium tracking-tight max-w-3xl">
          Ready to scale your creator business? <span class="text-[#FCE844]">Join the waitlist for early access.</span>
        </h2>
        <button class="inline-flex items-center gap-2 px-8 py-3 rounded-full bg-[#FCE844] hover:bg-[#fde047] text-black text-sm font-medium tracking-tight hover:scale-105 transition-all">
          Get early access
          <svg width="10" height="10" viewBox="0 0 10 10" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M1 9L9 1M9 1H3M9 1V7" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
        <p class="text-gray-400 text-xs">Start free. Let AI handle the overhead. Focus on creating.</p>
      </div>
      
      <!-- Background gradient/glow -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full max-w-2xl max-h-2xl bg-gradient-to-r from-yellow-900/20 to-orange-900/20 blur-3xl rounded-full pointer-events-none"></div>
    </div>
  </section>

</div>

