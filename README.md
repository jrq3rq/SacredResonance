```markdown
SacredResonance/
├── public/ # Static assets
│   ├── favicon.ico # App icon
│   ├── index.html # Root HTML with React mount
│   ├── manifest.json # PWA support (name, icons)
│   ├── images/ # Image assets
│   │   ├── logo.png # App logo (512x512)
│   │   ├── logo192.png # PWA logo (192x192)
│   │   └── background.jpg # Optional background for UI
├── src/ # Frontend source code
│   ├── components/ # Reusable React components
│   │   ├── Visualizer.js # Canvas for cymatic patterns
│   │   ├── FrequencySlider.js # Slider for frequency input
│   │   ├── PatternSelector.js # Dropdown for pattern presets
│   │   ├── LessonPanel.js # Sidebar for educational text
│   │   ├── AudioControls.js # Volume slider, mute toggle
│   │   ├── Header.js # Navigation bar
│   │   ├── Footer.js # App info, links
│   │   └── ErrorPrompt.js # Audio error messages
│   ├── context/ # State management
│   │   └── AudioContext.js # Manages Web Audio API state
│   ├── hooks/ # Custom hooks
│   │   ├── useAudio.js # Handles OscillatorNode, AnalyserNode
│   │   └── useLocalStorage.js # Saves user settings (e.g., frequency)
│   ├── pages/ # Page components
│   │   ├── Home.js # Main page with visualizer, controls
│   │   └── About.js # App info, cymatics overview
│   ├── services/ # Audio logic
│   │   └── audioService.js # Web Audio API setup, frequency processing
│   ├── styles/ # Tailwind CSS and custom styles
│   │   ├── App.css # Global styles
│   │   ├── Visualizer.css # Canvas styles
│   │   ├── LessonPanel.css # Sidebar styles
│   │   └── Header.css # Navigation styles
│   ├── utils/ # Utilities
│   │   └── patternMapper.js # Maps frequencies to shapes
│   ├── App.js # Main app with routing
│   ├── index.js # React entry point
│   └── index.css # CSS resets, typography
├── .env # Environment variables (e.g., API keys, if needed)
├── .gitignore # Ignores node_modules, .env
├── package.json # Dependencies (React, Tailwind, Web Audio API)
└── README.md # Setup, usage instructions
```