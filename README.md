<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 270" width="1000" height="270" font-family="'Courier New', Courier, monospace">
  <defs>
    <linearGradient id="bgGrad" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#050510"/>
      <stop offset="0.5" stop-color="#0a0a1f"/>
      <stop offset="1" stop-color="#050510"/>
    </linearGradient>
    <filter id="glowC" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="4" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glowM" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="5" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- master loop clock -->
  <rect width="0" height="0" fill="none">
    <animate id="loop" attributeName="x" from="0" to="0" begin="0s;loop.end" dur="16s"/>
  </rect>

  <!-- background -->
  <rect width="1000" height="270" fill="url(#bgGrad)"/>

  <g stroke="#00f0ff" stroke-width="0.5" opacity="0.07">
    <line x1="0" y1="0" x2="0" y2="270"/>
    <line x1="50" y1="0" x2="50" y2="270"/>
    <line x1="100" y1="0" x2="100" y2="270"/>
    <line x1="150" y1="0" x2="150" y2="270"/>
    <line x1="200" y1="0" x2="200" y2="270"/>
    <line x1="250" y1="0" x2="250" y2="270"/>
    <line x1="300" y1="0" x2="300" y2="270"/>
    <line x1="350" y1="0" x2="350" y2="270"/>
    <line x1="400" y1="0" x2="400" y2="270"/>
    <line x1="450" y1="0" x2="450" y2="270"/>
    <line x1="500" y1="0" x2="500" y2="270"/>
    <line x1="550" y1="0" x2="550" y2="270"/>
    <line x1="600" y1="0" x2="600" y2="270"/>
    <line x1="650" y1="0" x2="650" y2="270"/>
    <line x1="700" y1="0" x2="700" y2="270"/>
    <line x1="750" y1="0" x2="750" y2="270"/>
    <line x1="800" y1="0" x2="800" y2="270"/>
    <line x1="850" y1="0" x2="850" y2="270"/>
    <line x1="900" y1="0" x2="900" y2="270"/>
    <line x1="950" y1="0" x2="950" y2="270"/>
    <line x1="1000" y1="0" x2="1000" y2="270"/>
    <line x1="0" y1="0" x2="1000" y2="0"/>
    <line x1="0" y1="45" x2="1000" y2="45"/>
    <line x1="0" y1="90" x2="1000" y2="90"/>
    <line x1="0" y1="135" x2="1000" y2="135"/>
    <line x1="0" y1="180" x2="1000" y2="180"/>
    <line x1="0" y1="225" x2="1000" y2="225"/>
    <line x1="0" y1="270" x2="1000" y2="270"/>
  </g>

  <rect x="0" y="-6" width="1000" height="4" fill="#00f0ff" opacity="0.10">
    <animate attributeName="y" from="-6" to="270" dur="4.5s" repeatCount="indefinite"/>
  </rect>

  <path d="M22 62 V22 H62" fill="none" stroke="#00f0ff" stroke-width="2.5" stroke-dasharray="90" stroke-dashoffset="90" filter="url(#glowC)">
    <animate attributeName="stroke-dashoffset" from="90" to="0" begin="loop.begin+0.1s" dur="0.7s" fill="freeze"/>
  </path>

  <path d="M938 22 H978 V62" fill="none" stroke="#00f0ff" stroke-width="2.5" stroke-dasharray="90" stroke-dashoffset="90" filter="url(#glowC)">
    <animate attributeName="stroke-dashoffset" from="90" to="0" begin="loop.begin+0.1s" dur="0.7s" fill="freeze"/>
  </path>

  <path d="M978 208 V248 H938" fill="none" stroke="#00f0ff" stroke-width="2.5" stroke-dasharray="90" stroke-dashoffset="90" filter="url(#glowC)">
    <animate attributeName="stroke-dashoffset" from="90" to="0" begin="loop.begin+0.1s" dur="0.7s" fill="freeze"/>
  </path>

  <path d="M62 248 H22 V208" fill="none" stroke="#00f0ff" stroke-width="2.5" stroke-dasharray="90" stroke-dashoffset="90" filter="url(#glowC)">
    <animate attributeName="stroke-dashoffset" from="90" to="0" begin="loop.begin+0.1s" dur="0.7s" fill="freeze"/>
  </path>

  <text x="40" y="50" font-size="13" fill="#00f0ff" opacity="0" letter-spacing="3">[ SYSTEM://BOOT ]<animate attributeName="opacity" values="0;0.8" begin="loop.begin+0.3s" dur="0.4s" fill="freeze"/></text>
  <text x="960" y="50" text-anchor="end" font-size="13" fill="#ff2ee6" opacity="0" letter-spacing="3">[ v2.0.26 ]<animate attributeName="opacity" values="0;0.8" begin="loop.begin+0.3s" dur="0.4s" fill="freeze"/></text>

  <g font-size="56" font-weight="bold" text-anchor="middle" filter="url(#glowC)">
    <text x="52" y="148" fill="#7df9ff" opacity="0">প<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+0.6s" dur="0.16s"/></text>
    <text x="52" y="148" fill="#7df9ff" opacity="0">प<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+0.76s" dur="0.16s"/></text>
    <text x="52" y="148" fill="#7df9ff" opacity="0">ピ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+0.92s" dur="0.16s"/></text>
    <text x="52" y="148" fill="#7df9ff" opacity="0">Π<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.08s" dur="0.16s"/></text>
    <text x="52" y="148" fill="#7df9ff" opacity="0">П<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.24s" dur="0.16s"/></text>
    <text x="52" y="148" fill="#eafcff" opacity="0">P<animate attributeName="opacity" values="0;1" begin="loop.begin+1.4s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+1.4s" dur="0.5s"/></text>
    <text x="116" y="148" fill="#7df9ff" opacity="0">র<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.22s" dur="0.16s"/></text>
    <text x="116" y="148" fill="#7df9ff" opacity="0">र<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.38s" dur="0.16s"/></text>
    <text x="116" y="148" fill="#7df9ff" opacity="0">ラ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.54s" dur="0.16s"/></text>
    <text x="116" y="148" fill="#7df9ff" opacity="0">Ρ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.7s" dur="0.16s"/></text>
    <text x="116" y="148" fill="#7df9ff" opacity="0">Р<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.86s" dur="0.16s"/></text>
    <text x="116" y="148" fill="#eafcff" opacity="0">R<animate attributeName="opacity" values="0;1" begin="loop.begin+2.02s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+2.02s" dur="0.5s"/></text>
    <text x="180" y="148" fill="#7df9ff" opacity="0">ই<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+1.84s" dur="0.16s"/></text>
    <text x="180" y="148" fill="#7df9ff" opacity="0">इ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2s" dur="0.16s"/></text>
    <text x="180" y="148" fill="#7df9ff" opacity="0">イ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2.16s" dur="0.16s"/></text>
    <text x="180" y="148" fill="#7df9ff" opacity="0">Ι<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2.32s" dur="0.16s"/></text>
    <text x="180" y="148" fill="#7df9ff" opacity="0">И<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2.48s" dur="0.16s"/></text>
    <text x="180" y="148" fill="#eafcff" opacity="0">I<animate attributeName="opacity" values="0;1" begin="loop.begin+2.64s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+2.64s" dur="0.5s"/></text>
    <text x="244" y="148" fill="#7df9ff" opacity="0">য়<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2.46s" dur="0.16s"/></text>
    <text x="244" y="148" fill="#7df9ff" opacity="0">य<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2.62s" dur="0.16s"/></text>
    <text x="244" y="148" fill="#7df9ff" opacity="0">ヤ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2.78s" dur="0.16s"/></text>
    <text x="244" y="148" fill="#7df9ff" opacity="0">Υ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+2.94s" dur="0.16s"/></text>
    <text x="244" y="148" fill="#7df9ff" opacity="0">Й<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.1s" dur="0.16s"/></text>
    <text x="244" y="148" fill="#eafcff" opacity="0">Y<animate attributeName="opacity" values="0;1" begin="loop.begin+3.26s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+3.26s" dur="0.5s"/></text>
    <text x="308" y="148" fill="#7df9ff" opacity="0">আ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.08s" dur="0.16s"/></text>
    <text x="308" y="148" fill="#7df9ff" opacity="0">अ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.24s" dur="0.16s"/></text>
    <text x="308" y="148" fill="#7df9ff" opacity="0">ア<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.4s" dur="0.16s"/></text>
    <text x="308" y="148" fill="#7df9ff" opacity="0">Α<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.56s" dur="0.16s"/></text>
    <text x="308" y="148" fill="#7df9ff" opacity="0">А<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.72s" dur="0.16s"/></text>
    <text x="308" y="148" fill="#eafcff" opacity="0">A<animate attributeName="opacity" values="0;1" begin="loop.begin+3.88s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+3.88s" dur="0.5s"/></text>
    <text x="372" y="148" fill="#7df9ff" opacity="0">ন<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.7s" dur="0.16s"/></text>
    <text x="372" y="148" fill="#7df9ff" opacity="0">न<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+3.86s" dur="0.16s"/></text>
    <text x="372" y="148" fill="#7df9ff" opacity="0">ナ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.02s" dur="0.16s"/></text>
    <text x="372" y="148" fill="#7df9ff" opacity="0">Ν<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.18s" dur="0.16s"/></text>
    <text x="372" y="148" fill="#7df9ff" opacity="0">Н<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.34s" dur="0.16s"/></text>
    <text x="372" y="148" fill="#eafcff" opacity="0">N<animate attributeName="opacity" values="0;1" begin="loop.begin+4.5s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+4.5s" dur="0.5s"/></text>
    <text x="436" y="148" fill="#7df9ff" opacity="0">গ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.32s" dur="0.16s"/></text>
    <text x="436" y="148" fill="#7df9ff" opacity="0">ग<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.48s" dur="0.16s"/></text>
    <text x="436" y="148" fill="#7df9ff" opacity="0">ガ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.64s" dur="0.16s"/></text>
    <text x="436" y="148" fill="#7df9ff" opacity="0">Γ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.8s" dur="0.16s"/></text>
    <text x="436" y="148" fill="#7df9ff" opacity="0">Г<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.96s" dur="0.16s"/></text>
    <text x="436" y="148" fill="#eafcff" opacity="0">G<animate attributeName="opacity" values="0;1" begin="loop.begin+5.12s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+5.12s" dur="0.5s"/></text>
    <text x="500" y="148" fill="#7df9ff" opacity="0">স<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+4.94s" dur="0.16s"/></text>
    <text x="500" y="148" fill="#7df9ff" opacity="0">स<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+5.1s" dur="0.16s"/></text>
    <text x="500" y="148" fill="#7df9ff" opacity="0">サ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+5.26s" dur="0.16s"/></text>
    <text x="500" y="148" fill="#7df9ff" opacity="0">Σ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+5.42s" dur="0.16s"/></text>
    <text x="500" y="148" fill="#7df9ff" opacity="0">С<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+5.58s" dur="0.16s"/></text>
    <text x="500" y="148" fill="#eafcff" opacity="0">S<animate attributeName="opacity" values="0;1" begin="loop.begin+5.74s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+5.74s" dur="0.5s"/></text>
    <text x="564" y="148" fill="#7df9ff" opacity="0">হ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+5.56s" dur="0.16s"/></text>
    <text x="564" y="148" fill="#7df9ff" opacity="0">ह<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+5.72s" dur="0.16s"/></text>
    <text x="564" y="148" fill="#7df9ff" opacity="0">ハ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+5.88s" dur="0.16s"/></text>
    <text x="564" y="148" fill="#7df9ff" opacity="0">Η<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+6.04s" dur="0.16s"/></text>
    <text x="564" y="148" fill="#7df9ff" opacity="0">Х<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+6.2s" dur="0.16s"/></text>
    <text x="564" y="148" fill="#eafcff" opacity="0">H<animate attributeName="opacity" values="0;1" begin="loop.begin+6.36s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+6.36s" dur="0.5s"/></text>
    <text x="628" y="148" fill="#7df9ff" opacity="0">উ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+6.18s" dur="0.16s"/></text>
    <text x="628" y="148" fill="#7df9ff" opacity="0">उ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+6.34s" dur="0.16s"/></text>
    <text x="628" y="148" fill="#7df9ff" opacity="0">ウ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+6.5s" dur="0.16s"/></text>
    <text x="628" y="148" fill="#7df9ff" opacity="0">Ʊ<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+6.66s" dur="0.16s"/></text>
    <text x="628" y="148" fill="#7df9ff" opacity="0">У<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.85;1" begin="loop.begin+6.82s" dur="0.16s"/></text>
    <text x="628" y="148" fill="#eafcff" opacity="0">U<animate attributeName="opacity" values="0;1" begin="loop.begin+6.98s" dur="0.12s" fill="freeze"/><animate attributeName="fill" values="#eafcff;#00f0ff;#eafcff" begin="loop.begin+6.98s" dur="0.5s"/></text>
  </g>

  <g font-size="56" font-weight="bold" text-anchor="middle" filter="url(#glowM)">
    <text x="737" y="150" fill="#ff2ee6" opacity="0">D<animate attributeName="opacity" values="0;0.9;0" begin="loop.begin+7.75s" dur="0.18s"/></text>
    <text x="734" y="148" fill="#ff2ee6" opacity="0">D<animate attributeName="opacity" values="0;1" begin="loop.begin+7.85s" dur="0.12s" fill="freeze"/></text>
    <text x="801" y="150" fill="#ff2ee6" opacity="0">E<animate attributeName="opacity" values="0;0.9;0" begin="loop.begin+7.97s" dur="0.18s"/></text>
    <text x="798" y="148" fill="#ff2ee6" opacity="0">E<animate attributeName="opacity" values="0;1" begin="loop.begin+8.07s" dur="0.12s" fill="freeze"/></text>
    <text x="865" y="150" fill="#ff2ee6" opacity="0">Y<animate attributeName="opacity" values="0;0.9;0" begin="loop.begin+8.19s" dur="0.18s"/></text>
    <text x="862" y="148" fill="#ff2ee6" opacity="0">Y<animate attributeName="opacity" values="0;1" begin="loop.begin+8.29s" dur="0.12s" fill="freeze"/></text>
  </g>

  <rect x="22" y="170" width="0" height="2.5" fill="#00f0ff" filter="url(#glowC)">
    <animate attributeName="width" from="0" to="922" begin="loop.begin+8.61s" dur="0.6s" fill="freeze"/>
  </rect>

  <text x="500" y="210" text-anchor="middle" font-size="17" letter-spacing="5" fill="#8afcff" opacity="0">FULL-STACK DEVELOPER ⌁ BUILDING AAKAAR.IO ⌁ ENTREPRENEUR<animate attributeName="opacity" values="0;1" begin="loop.begin+9.11s" dur="0.8s" fill="freeze"/></text>
  <text x="758" y="210" font-size="17" fill="#00f0ff" opacity="0">_<animate attributeName="opacity" values="0;1;0;1;0;1" begin="loop.begin+9.91s" dur="2.4s" repeatCount="2"/></text>

  <rect x="330" y="70" width="340" height="3" fill="#ff2ee6" opacity="0">
    <animate attributeName="opacity" values="0;0.5;0;0.35;0" begin="loop.begin+1.4s" dur="0.3s"/>
  </rect>

  <rect x="240" y="200" width="520" height="3" fill="#ff2ee6" opacity="0">
    <animate attributeName="opacity" values="0;0.5;0;0.35;0" begin="loop.begin+3.1s" dur="0.3s"/>
  </rect>

  <rect x="370" y="110" width="260" height="3" fill="#ff2ee6" opacity="0">
    <animate attributeName="opacity" values="0;0.5;0;0.35;0" begin="loop.begin+5s" dur="0.3s"/>
  </rect>

</svg>
