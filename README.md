<!-- StudyFlow AI Animated SVG Logo -->
<svg width="600" height="160" viewBox="0 0 600 160" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad" x1="0" y1="0" x2="600" y2="0">
      <stop offset="0%" stop-color="#6EE7B7">
        <animate attributeName="stop-color"
                 values="#6EE7B7; #3B82F6; #9333EA; #6EE7B7"
                 dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#9333EA">
        <animate attributeName="stop-color"
                 values="#9333EA; #3B82F6; #6EE7B7; #9333EA"
                 dur="6s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect x="10" y="10" width="580" height="140" rx="24"
        fill="#020617" stroke="url(#grad)" stroke-width="2"
        filter="url(#glow)">
    <animate attributeName="stroke-width"
             values="2;3;2" dur="3s" repeatCount="indefinite" />
  </rect>

  <!-- Text -->
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
        font-family="Orbitron, system-ui, sans-serif"
        font-size="40" fill="url(#grad)" filter="url(#glow)">
    StudyFlow AI
  </text>
</svg>
