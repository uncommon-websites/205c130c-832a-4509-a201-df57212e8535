<script>
  import VideoCard from "$lib/components/VideoCard.svelte";
</script>

<div class="pt-32 pb-20">
  <!-- Hero Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-24">
    <h1 class="text-[clamp(3rem,8vw,6rem)] leading-[0.9] font-medium text-center mb-12 tracking-tight">
      Say hello to Billow
    </h1>
    
    <div class="w-full aspect-[16/10] bg-gray-200 rounded-2xl overflow-hidden mb-12 relative">
      <!-- Placeholder for Hero Image -->
      <img src="/generated/image-a-modern-finance-team-in-a-biotech-or-st-1787249109921-0.webp" alt="Billow automates month-end for finance teams" class="absolute inset-0 w-full h-full object-cover opacity-90" />
      <div class="absolute inset-0 flex items-center justify-center">
        <!-- Play button overlay if it's a video -->
      </div>
    </div>

    <div class="max-w-2xl">
      <p class="text-xl md:text-2xl leading-relaxed text-gray-800">
        Built for finance teams that can't afford a slow close, Billow works around the clock to automate your month-end. Hand off your manual reconciliations, so your team can focus on what actually moves the business.
      </p>
    </div>
  </section>

  <!-- Intro Video Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-40">
    <div class="flex flex-col md:flex-row items-end justify-between gap-12">
      <div class="max-w-xs mb-8 md:mb-0">
        <p class="text-xs font-medium leading-relaxed text-gray-500 uppercase tracking-wide">
          Finance teams deserve tools as rigorous as they are. Watch how our team came together to build the automated close platform that controllers actually trust.
        </p>
      </div>
      <div class="w-full md:w-[400px]">
        <VideoCard 
          imageSrc="/generated/image-a-diverse-team-of-finance-professionals--1787249110903-0.webp" 
          alt="Billow team working on building trusted automation for finance"
          title="Our Story"
          subtitle="Watch"
        />
      </div>
    </div>
  </section>

  <!-- Mundane Made Magic -->
  <section class="max-w-[1000px] mx-auto px-4 mb-40">
    <div class="flex flex-col gap-8 text-[clamp(4rem,10vw,9rem)] leading-[0.8] tracking-tight font-medium">
      <div class="text-left">Manual</div>
      <div class="text-center pl-[20%]">made</div>
      <div class="text-right pr-[10%]">automatic</div>
    </div>
  </section>

  <!-- Reconciliation Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="max-w-2xl mx-auto text-center mb-16">
      <p class="text-lg text-gray-600 leading-relaxed">
        Powered by AI agents trained on your existing spreadsheet workflows and an ever-expanding automation library, Billow doesn't just handle a few line items—it learns your close process faster than any tool that came before it.
      </p>
    </div>

    <div class="grid grid-cols-1 gap-4">
      <!-- Main Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden group">
        <img src="/generated/image-a-digital-dashboard-interface-displaying-1787249138341-0.webp" alt="Billow automates your reconciliations" class="absolute inset-0 w-full h-full object-cover opacity-90" />
        <div class="absolute bottom-8 left-8 md:bottom-12 md:left-12">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight">Billow automates your reconciliations</h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          01
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div class="aspect-[4/3] bg-gray-200 rounded-2xl overflow-hidden relative p-8 flex items-end">
           <p class="text-xs text-gray-600 max-w-xs">
             Billow can silently and autonomously match transactions, flag exceptions, and push reconciled entries directly into your ledger before the close deadline. Let Billow handle the grind, so your controllers can focus on judgment calls that only humans can make.
           </p>
           <div class="absolute top-4 left-4 text-[10px] text-gray-400 uppercase tracking-wider">Lightening the load</div>
        </div>
        <div class="aspect-[4/3] bg-gray-200 rounded-2xl overflow-hidden relative">
           <img src="/generated/image-a-digital-interface-integrating-with-var-1787249104225-0.webp" alt="Billow close dashboard" class="absolute inset-0 w-full h-full object-cover opacity-90" />
          <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">Spot check: A faster close in action</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Workflows Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
        <img src="/generated/image-a-digital-interface-integrating-with-var-1787249104225-0.webp" alt="Billow works in stacks it's never seen" class="absolute inset-0 w-full h-full object-cover opacity-90" />
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center max-w-2xl">
            Billow works in stacks<br/>it's never seen
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          02
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">A new ERP is Billow's terrain.</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             We believe Billow should be ready to work from day one, connecting to your existing systems right out of the box. Finance teams at diverse companies onboard Billow into their environments daily, so it robustly handles the complexity of real ledgers.
           </p>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">01. Connecting your ERP</span>
          </div>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">02. Mapping a new close workflow</span>
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
        <img src="/generated/image-a-digital-dashboard-with-analytics-and-i-1787249107773-0.webp" alt="Billow is always improving" class="absolute inset-0 w-full h-full object-cover opacity-90" />
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center">
            Billow is always improving
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          03
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">Map it once, it runs forever.</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             In its first months, Billow handled basic account reconciliations. Just quarters later, it's managing intercompany eliminations, accrual schedules, and flux analysis. Billow keeps getting faster. Give it your workflows, and watch it reclaim your team's time.
           </p>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">A. Billow running accrual schedules</span>
          </div>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <div class="absolute inset-0 flex items-center justify-center text-gray-400">Image</div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">B. Billow generating the close report</span>
          </div>
        </div>
      </div>
    </div>
  <!-- Imitation to Intuition -->
  <section class="bg-[#E3EBE6] py-32 mb-32 -mx-4 md:-mx-8 px-4 md:px-8">
    <div class="max-w-[1400px] mx-auto">
      <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-tight font-medium text-center mb-20 tracking-tight text-balance max-w-4xl mx-auto">
        From spreadsheet to autonomous agent
      </h2>

      <div class="flex flex-col items-center mb-20">
        <div class="w-full max-w-md aspect-[3/4] bg-gray-300 rounded-2xl overflow-hidden relative mb-12">
          <img src="/generated/image-a-finance-team-member-using-a-workflow-c-1787249103837-0.webp" alt="Workflow capture interface" class="absolute inset-0 w-full h-full object-cover opacity-90" />
        </div>
        
        <div class="max-w-xl text-center">
          <p class="text-lg text-gray-700 leading-relaxed">
            Our Workflow Capture Engine™ enables Billow to distill your existing manual spreadsheet processes into trained AI agents, unlocking automated close skills across your entire finance stack. What your team does manually, Billow learns to run autonomously.
          </p>
        </div>
      </div>

      <div class="max-w-4xl mx-auto">
        <VideoCard 
          imageSrc="" 
          alt="Workflow Capture Engine Demo"
          title="Workflow Capture Engine in use"
          subtitle=""
        />
        <div class="text-center mt-12 space-y-2">
          <p class="text-xs text-gray-500 leading-relaxed max-w-xs mx-auto">
            To date, we've automated over 5,000 hours of manual close work across our customer base. This robust training is what makes Billow useful in yours.
          </p>
          <div class="flex justify-center gap-8 pt-4 text-[10px] uppercase tracking-wider font-medium">
            <a href="#" class="border-b border-black pb-0.5">Explore Technology</a>
            <a href="#" class="border-b border-black pb-0.5">Become a Design Partner</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Designed for real use -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="text-center mb-16">
      <h2 class="text-[clamp(3rem,6vw,5rem)] leading-tight font-medium mb-8 tracking-tight">
        Designed for real<br/>finance teams
      </h2>
      
      <div class="inline-flex bg-white rounded-full p-1 border border-gray-200">
        <button class="px-4 py-1.5 rounded-full bg-black text-white text-xs font-medium">Features</button>
        <button class="px-4 py-1.5 rounded-full hover:bg-gray-100 text-gray-500 text-xs font-medium transition-colors">Integrations</button>
        <button class="px-4 py-1.5 rounded-full hover:bg-gray-100 text-gray-500 text-xs font-medium transition-colors">Security</button>
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
          <h3 class="text-white text-sm font-bold mb-2">Your data never trains our models</h3>
          <p class="text-[10px] text-gray-400 leading-relaxed">
            Billow operates on a strict data sovereignty policy. Your ledger data is never used to train third-party models. Through air-gapped deployment options and SOC 2 Type II certification, we ensure exactly how much — or how little — leaves your environment.
          </p>
        </div>
      </div>

      <!-- Card 2: Safety -->
      <div class="aspect-square bg-[#F0EFE9] rounded-2xl p-6 flex flex-col justify-between overflow-hidden relative">
         <div class="relative z-10">
            <h3 class="text-black text-sm font-bold mb-2">Compliance built for regulated industries</h3>
            <p class="text-[10px] text-gray-500 leading-relaxed">
            SOX-aligned with full segregation of duties, audit trails, and a HIPAA-configurable deployment model under a Business Associate Agreement for biotech and life sciences customers.
            </p>
         </div>
         <!-- Orange abstract shape -->
         <div class="absolute -bottom-10 -right-10 w-48 h-48 bg-[#FF4500] rounded-full blur-xl opacity-80"></div>
         <div class="absolute bottom-0 right-0 w-full h-1/2 bg-gradient-to-t from-[#FF4500] to-transparent opacity-20"></div>
         <div class="w-full h-40 bg-[#FF4500] rounded-full absolute -bottom-20 left-1/2 -translate-x-1/2"></div>
      </div>

      <!-- Card 3: Close up -->
      <div class="aspect-square bg-gray-200 rounded-2xl overflow-hidden relative">
         <img src="/generated/image-a-close-up-of-a-finance-professionals-ha-1787249104062-0.webp" alt="Close up" class="w-full h-full object-cover" />
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
          <h3 class="text-white text-sm font-bold mb-2">Tailored to your close process</h3>
          <p class="text-[10px] text-gray-300 leading-relaxed">
            Configure Billow to match your existing workflows, chart of accounts, and reporting cadences — no rip-and-replace required.
          </p>
        </div>
      </div>

      <!-- Card 5: Simple, soft -->
      <div class="aspect-square bg-[#B8C6C0] rounded-2xl p-6 flex flex-col justify-between overflow-hidden relative">
         <div class="relative z-10">
            <h3 class="text-black text-sm font-bold mb-2">Simple setup, powerful results</h3>
            <p class="text-[10px] text-gray-700 leading-relaxed">
            Billow connects to your ERP, bank feeds, and sub-ledgers through secure native integrations. Your team is up and running in days, not quarters, with full audit-ready output from the first close.
            </p>
         </div>
         <!-- Grid texture -->
         <div class="absolute inset-0 opacity-20" style="background-image: linear-gradient(#000 1px, transparent 1px), linear-gradient(90deg, #000 1px, transparent 1px); background-size: 20px 20px;"></div>
      </div>

      <!-- Card 6: Hand touch -->
      <div class="aspect-square bg-yellow-400 rounded-2xl overflow-hidden relative">
         <img src="/generated/image-a-finance-professional-reaching-out-to-t-1787249122344-0.webp" alt="Hand touch" class="w-full h-full object-cover mix-blend-multiply opacity-80" />
         <div class="absolute inset-0 bg-yellow-400/30 mix-blend-overlay"></div>
      </div>
    </div>
    
    <!-- Repeat Tabs for visual consistency if needed or just bottom spacing -->
    <div class="flex justify-center">
       <div class="inline-flex bg-white rounded-full p-1 border border-gray-200 opacity-50 pointer-events-none">
        <button class="px-4 py-1.5 rounded-full bg-black text-white text-xs font-medium">Features</button>
        <button class="px-4 py-1.5 rounded-full text-gray-500 text-xs font-medium">Integrations</button>
        <button class="px-4 py-1.5 rounded-full text-gray-500 text-xs font-medium">Security</button>
      </div>
    </div>
  </section>

  <!-- Integrations Section -->
  <section class="bg-[#DCEBEF] py-40 -mx-4 md:-mx-8 px-4 md:px-8 flex flex-col items-center text-center">
    <div class="flex flex-col md:flex-row items-center justify-between w-full max-w-2xl mb-12 gap-8">
      <span class="text-xs font-medium text-gray-500">Billow handles many workflows.</span>
      
      <div class="w-24 h-24 text-black">
        <!-- Flower/Icon -->
        <svg viewBox="0 0 100 100" fill="currentColor" class="w-full h-full animate-spin-slow">
          <path d="M50 20C58 20 65 27 65 35C65 43 58 50 50 50C42 50 35 43 35 35C35 27 42 20 50 20Z" />
          <path d="M50 80C42 80 35 73 35 65C35 57 42 50 50 50C58 50 65 57 65 65C65 73 58 80 50 80Z" />
          <path d="M20 50C20 42 27 35 35 35C43 35 50 42 50 50C50 58 43 65 35 65C27 65 20 58 20 50Z" />
          <path d="M80 50C80 58 73 65 65 65C57 65 50 58 50 50C50 42 57 35 65 35C73 35 80 42 80 50Z" />
        </svg>
      </div>

      <span class="text-xs font-medium text-gray-500">Which should we automate next?</span>
    </div>

    <button class="bg-black text-white px-8 py-3 rounded-full text-xs font-bold uppercase tracking-wider hover:scale-105 transition-transform">
      Request a workflow
    </button>
  </section>

  <!-- FAQ Section -->
  <section class="max-w-[800px] mx-auto px-4 py-32">
    <h3 class="text-xs font-medium text-gray-500 mb-12">Frequently asked questions</h3>
    
    <div class="space-y-4">
      {#each [
        "What does Billow automate?",
        "Is Billow available for my team today?",
        "How much does Billow cost?",
        "How long does onboarding take? What ERPs do you support?",
        "Is Billow SOC 2 and SOX compliant?",
        "What is the Billow Design Partner program?"
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

  <!-- Founding Teams Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-20">
    <div class="bg-[#111111] rounded-2xl p-12 md:p-24 text-center relative overflow-hidden">
      <div class="relative z-10 flex flex-col items-center gap-6">
        <h2 class="text-white text-xl md:text-2xl font-medium tracking-tight">
          Be one of our Founding Finance Teams. <span class="text-[#FCEE4F]">Early access. Dedicated onboarding. Direct input on the roadmap.</span>
        </h2>
        <button class="inline-flex items-center gap-2 px-6 py-2 rounded-full border border-white/20 text-white text-xs uppercase tracking-wider hover:bg-white/10 transition-colors">
          Design Partner program
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

