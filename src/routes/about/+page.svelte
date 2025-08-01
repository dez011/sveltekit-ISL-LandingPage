<script>
    // Card content + icons (inline SVG paths)
    const cards = [
      {
        title: "Our Mission",
        text: "IronSpec builds precision-crafted systems designed to meet the demands of agencies, businesses, and organizations that require uncompromising reliability and performance.",
        icon: `<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12A9 9 0 113 12a9 9 0 0118 0z" />`
      },
      {
        title: "Veteran-Owned Values",
        text: "Rooted in military principles of service, integrity, and accountability, every IronSpec build reflects a commitment to excellence and responsibility.",
        icon: `<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />`
      },
      {
        title: "Commitment to Quality",
        text: "Each machine is hand-assembled, stress-tested, and designed for long-term dependability — we don’t ship anything we wouldn’t trust ourselves.",
        icon: `<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />`
      }
    ];
  </script>
  
  <section class="p-8 max-w-6xl mx-auto space-y-12">
  
    <!-- HERO INTRO -->
    <div class="text-center">
      <h1 class="text-5xl font-extrabold mb-4">About IronSpec</h1>
      <p class="text-xl max-w-3xl mx-auto text-gray-600">
        IronSpec is a veteran-owned technology company that designs and builds
        mission-ready computer systems for businesses and government agencies.
        Every build is guided by precision, security, and a promise of performance.
      </p>
    </div>
  
    <!-- INFO CARDS -->
    <div class="grid gap-6 md:grid-cols-3">
      {#each cards as card}
        <div class="bg-base-100 p-6 rounded-2xl shadow-lg text-center hover:shadow-xl transition">
          
          <!-- ICON -->
          <div class="flex justify-center mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              {@html card.icon}
            </svg>
          </div>
  
          <h2 class="text-2xl font-bold mb-3">{card.title}</h2>
          <p class="text-lg text-gray-700">{card.text}</p>
        </div>
      {/each}
    </div>
  
    <!-- WHY IRONSPEC SECTION -->
    <div>
      <h2 class="text-3xl font-bold mb-4 text-center">Why Choose IronSpec?</h2>
      <ul class="list-disc list-inside space-y-2 text-lg max-w-2xl mx-auto">
        <li><strong>Veteran-Owned:</strong> Built on values of service and trust.</li>
        <li><strong>Precision Assembly:</strong> Every system is hand-built, not mass produced.</li>
        <li><strong>Government-Ready:</strong> Configured to align with procurement standards.</li>
        <li><strong>Rigorous Testing:</strong> Stress-tested for flawless performance.</li>
        <li><strong>U.S.-Based Support:</strong> Help that doesn’t end after delivery.</li>
      </ul>
    </div>
  
  </section>
  