<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Celestial Archer - Nine Moons</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;800&family=Plus+Jakarta+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        cinzel: ['Cinzel', 'serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        celestial: {
                            bg: '#080a16',
                            deep: '#0d1127',
                            accent: '#6366f1',
                            gold: '#f59e0b',
                            silver: '#e2e8f0',
                            moon: '#fef08a'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        body {
            background-color: #080a16;
            color: #e2e8f0;
            overflow-x: hidden;
            user-select: none;
        }

        /* Glassmorphism styles */
        .glass-panel {
            background: rgba(15, 23, 42, 0.75);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.12);
        }

        .glass-modal {
            background: rgba(10, 14, 31, 0.88);
            backdrop-filter: blur(24px);
            -webkit-backdrop-filter: blur(24px);
            border: 1px solid rgba(168, 85, 247, 0.3);
            box-shadow: 0 0 50px rgba(99, 102, 241, 0.25);
        }

        /* Neon Glowing Title Effect */
        .neon-glow-title {
            color: #fffde7;
            text-shadow: 
                0 0 7px #fff,
                0 0 15px #f59e0b,
                0 0 25px #f97316,
                0 0 45px #ef4444,
                0 0 70px #dc2626;
            animation: neonPulse 2s ease-in-out infinite alternate;
        }

        @keyframes neonPulse {
            0% {
                text-shadow: 
                    0 0 5px #fff,
                    0 0 12px #f59e0b,
                    0 0 22px #f97316,
                    0 0 35px #ef4444,
                    0 0 55px #dc2626;
            }
            100% {
                text-shadow: 
                    0 0 10px #fff,
                    0 0 20px #fbbf24,
                    0 0 35px #f97316,
                    0 0 55px #ef4444,
                    0 0 85px #b91c1c;
            }
        }

        /* Glowing Effects for Warm Reddish-Orange Sun-Moons */
        .moon-glow {
            filter: drop-shadow(0 0 15px rgba(239, 68, 68, 0.75)) drop-shadow(0 0 30px rgba(245, 158, 11, 0.5));
            transition: all 0.5s ease-out;
        }

        .moon-glow:hover {
            filter: drop-shadow(0 0 25px rgba(248, 113, 113, 0.95)) drop-shadow(0 0 45px rgba(251, 191, 36, 0.8));
            transform: scale(1.1);
        }

        .falling-moon-anim {
            animation: moonFall 2.2s cubic-bezier(0.25, 0.46, 0.45, 0.94) forwards;
        }

        @keyframes moonFall {
            0% {
                transform: translateY(0) scale(1) rotate(0deg);
                opacity: 1;
                filter: drop-shadow(0 0 30px rgba(239, 68, 68, 0.9));
            }
            50% {
                transform: translateY(220px) scale(0.85) rotate(180deg);
                opacity: 0.85;
            }
            100% {
                transform: translateY(550px) scale(0.2) rotate(360deg);
                opacity: 0;
            }
        }

        /* Pulse animation for action button */
        .btn-pulse {
            animation: pulseGlow 2s infinite;
        }

        @keyframes pulseGlow {
            0%, 100% {
                box-shadow: 0 0 15px rgba(245, 158, 11, 0.4), 0 0 30px rgba(99, 102, 241, 0.2);
            }
            50% {
                box-shadow: 0 0 30px rgba(245, 158, 11, 0.8), 0 0 50px rgba(99, 102, 241, 0.5);
            }
        }

        /* Bow String Tension Animation */
        .bow-draw {
            transition: transform 0.25s ease-in-out;
        }

        /* Custom Scrollbar for Text Area */
        textarea::-webkit-scrollbar {
            width: 6px;
        }
        textarea::-webkit-scrollbar-track {
            background: rgba(15, 23, 42, 0.5);
            border-radius: 4px;
        }
        textarea::-webkit-scrollbar-thumb {
            background: rgba(99, 102, 241, 0.5);
            border-radius: 4px;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between font-sans relative overflow-hidden">

    <canvas id="skyCanvas" class="fixed inset-0 w-full h-full pointer-events-none z-0"></canvas>

    <!-- Header & HUD Bar -->
    <header class="relative z-10 w-full px-6 py-4 flex flex-col md:flex-row justify-between items-center gap-4 glass-panel border-b border-indigo-900/30">
        <div class="flex items-center space-x-3">
            <div class="w-11 h-11 rounded-full bg-gradient-to-tr from-red-600 via-amber-500 to-yellow-300 flex items-center justify-center shadow-lg shadow-amber-500/40">
                <i class="fa-solid font-cinzel text-amber-100 text-xl">🥮</i>
            </div>
            <div>
                <h1 class="font-cinzel text-2xl md:text-3xl font-extrabold tracking-wider neon-glow-title">
                    Happy Moon Festival
                </h1>
                <p class="text-xs text-amber-200/80 font-medium tracking-widest uppercase">Legend of Hou Yi & The Nine Celestial Moons</p>
            </div>
        </div>

        <!-- HUD Counters & Controls -->
        <div class="flex items-center space-x-4">
            <!-- Moons Counter -->
            <div class="flex items-center space-x-2 px-3.5 py-1.5 rounded-full bg-slate-900/80 border border-red-500/40 shadow-inner">
                <i class="fa-solid fa-moon text-amber-400 text-sm"></i>
                <span class="text-xs text-slate-300 font-semibold">MOONS:</span>
                <span id="moonsRemainingText" class="text-sm font-bold text-amber-300">9 / 9</span>
            </div>

            <!-- Arrows Counter -->
            <div class="flex items-center space-x-2 px-3.5 py-1.5 rounded-full bg-slate-900/80 border border-amber-500/40 shadow-inner">
                <i class="fa-solid fa-location-arrow text-amber-400 text-sm transform -rotate-45"></i>
                <span class="text-xs text-slate-300 font-semibold">QUIVER:</span>
                <span id="arrowCountHUD" class="text-sm font-bold text-amber-400">9 Arrows</span>
            </div>

            <!-- Sound & BGM Toggle Button -->
            <button id="soundBtn" onclick="toggleAudio()" title="Toggle Celestial Music & FX" class="w-9 h-9 rounded-full bg-slate-800/80 hover:bg-slate-700 border border-amber-500/50 flex items-center justify-center text-amber-300 transition-colors shadow-sm">
                <i id="soundIcon" class="fa-solid fa-music text-sm animate-pulse"></i>
            </button>

            <!-- Journal / Written Words Button -->
            <button onclick="openJournal()" title="View Celestial Journal" class="w-9 h-9 rounded-full bg-slate-800/80 hover:bg-indigo-900/60 border border-indigo-500/40 flex items-center justify-center text-amber-300 transition-colors">
                <i class="fa-solid fa-book-bookmark text-sm"></i>
            </button>
        </div>
    </header>

    <main class="relative z-10 flex-1 flex flex-col justify-between p-4 md:p-6 max-w-7xl mx-auto w-full">
        
        <!-- Sky Moons Area -->
        <div class="relative w-full pt-2 pb-6 min-h-[260px] flex flex-col items-center justify-center">
            
            <!-- Subtitle Instructions -->
            <p id="instructionText" class="text-center font-cinzel text-amber-200/90 text-sm md:text-base font-semibold tracking-wider mb-6 bg-slate-900/70 px-6 py-2 rounded-full border border-amber-500/30 shadow-lg shadow-amber-500/10">
                Shoot one of the moon and answer a question.
            </p>

            <!-- 9 Moons Container (3 lines with 3 moons each) -->
            <div id="moonsGrid" class="grid grid-cols-3 gap-4 md:gap-6 w-full max-w-md mx-auto items-center justify-items-center">
                <!-- Moons will be dynamically generated by JS -->
            </div>
        </div>

        <div class="relative w-full flex flex-col items-center justify-end pb-1">
            
            <!-- Archer Visual Stage on Mountain Hill -->
            <div class="relative w-full max-w-lg h-64 flex items-end justify-center">
                
                <!-- Flying Arrow Canvas element container -->
                <div id="arrowContainer" class="absolute inset-0 pointer-events-none"></div>

                <!-- Archer Character & Mountain Hill Graphic -->
                <div id="archerCharacter" class="relative w-full h-full flex justify-center items-end transition-transform duration-300">
                    <svg width="380" height="250" viewBox="0 0 380 250" fill="none" xmlns="http://www.w3.org/2000/svg" class="drop-shadow-2xl">
                        <defs>
                            <!-- Skin Gradient -->
                            <linearGradient id="chibiSkinGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#ffe5d9"/>
                                <stop offset="50%" stop-color="#ffcad4"/>
                                <stop offset="100%" stop-color="#f4acb7"/>
                            </linearGradient>

                            <!-- Hair & Eyebrow Dark Gradient -->
                            <linearGradient id="chibiHairGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#2d3142"/>
                                <stop offset="60%" stop-color="#1b1d28"/>
                                <stop offset="100%" stop-color="#0f1017"/>
                            </linearGradient>

                            <!-- Slate Blue Robe Gradient -->
                            <linearGradient id="robeGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#6c757d"/>
                                <stop offset="50%" stop-color="#495057"/>
                                <stop offset="100%" stop-color="#212529"/>
                            </linearGradient>

                            <linearGradient id="robePurpleGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#6b705c"/>
                                <stop offset="0%" stop-color="#586071"/>
                                <stop offset="50%" stop-color="#3d4353"/>
                                <stop offset="100%" stop-color="#252a36"/>
                            </linearGradient>

                            <!-- Cyan/Teal Martial Arts Pants Gradient -->
                            <linearGradient id="chibiPantsGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#4ea8de"/>
                                <stop offset="50%" stop-color="#3a86c8"/>
                                <stop offset="100%" stop-color="#1d4e89"/>
                            </linearGradient>

                            <!-- Ribbon Hair Tie & Sash Accent -->
                            <linearGradient id="orangeRibbonGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#ffb703"/>
                                <stop offset="50%" stop-color="#fb8500"/>
                                <stop offset="100%" stop-color="#d97706"/>
                            </linearGradient>

                            <!-- Bow Wood Texture -->
                            <linearGradient id="chibiBowGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#e9c46a"/>
                                <stop offset="50%" stop-color="#b08968"/>
                                <stop offset="100%" stop-color="#7f5539"/>
                            </linearGradient>

                            <linearGradient id="hillGrad" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" stop-color="#8c5835"/>
                                <stop offset="40%" stop-color="#633c20"/>
                                <stop offset="100%" stop-color="#2c170a"/>
                            </linearGradient>

                            <filter id="softShadow" x="-20%" y="-20%" width="140%" height="140%">
                                <feDropShadow dx="0" dy="3" stdDeviation="3" flood-opacity="0.3"/>
                            </filter>
                        </defs>

                        <!-- Mountain Hill Base -->
                        <path d="M 5 250 Q 190 178 375 250 Z" fill="url(#hillGrad)" stroke="#3e200c" stroke-width="2"/>
                        <path d="M 25 250 Q 190 190 355 250 Z" fill="#734323" opacity="0.7"/>
                        <path d="M 80 250 Q 190 205 300 250 Z" fill="#91562d" opacity="0.4"/>

                        <!-- Mountain Branches -->
                        <path d="M 45 230 C 35 210, 20 200, 10 180 M 24 202 L 5 195 M 32 215 L 12 210 M 40 222 L 25 225" stroke="#311909" stroke-width="2.5" stroke-linecap="round"/>
                        <path d="M 335 235 C 348 215, 360 200, 372 185 M 348 212 L 370 202 M 342 222 L 362 218" stroke="#311909" stroke-width="2.5" stroke-linecap="round"/>

                        <g id="houYiCharacter" transform="translate(45, 10)">
                            
                            <!-- Back Quiver -->
                            <g id="svgQuiver" filter="url(#softShadow)">
                                <rect x="82" y="80" width="16" height="52" rx="5" transform="rotate(-20 82 80)" fill="#4a2810" stroke="#2a1405" stroke-width="2"/>
                                <rect x="83" y="86" width="14" height="5" transform="rotate(-20 82 80)" fill="#ffb703"/>
                                
                                <g id="quiverArrowIcons">
                                    <line x1="78" y1="78" x2="65" y2="48" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="82" y1="76" x2="71" y2="46" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="86" y1="74" x2="77" y2="44" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="90" y1="72" x2="83" y2="42" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="94" y1="70" x2="89" y2="40" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="98" y1="68" x2="95" y2="38" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="102" y1="66" x2="101" y2="36" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="106" y1="64" x2="107" y2="34" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                    <line x1="110" y1="62" x2="113" y2="32" stroke="#d97706" stroke-width="3" stroke-linecap="round"/>
                                </g>
                            </g>

                            <!-- Wide Martial Arts Feet & Wrapped Boots -->
                            <!-- Left Foot -->
                            <path d="M92 188 L114 188 C118 188 120 192 118 198 L90 198 Z" fill="#2d3142" stroke="#1f222e" stroke-width="1.5"/>
                            <path d="M94 188 L112 188" stroke="#586071" stroke-width="2"/>
                            
                            <!-- Right Foot -->
                            <path d="M152 182 L176 182 C180 182 182 186 180 192 L148 192 Z" fill="#2d3142" stroke="#1f222e" stroke-width="1.5"/>
                            <path d="M154 182 L174 182" stroke="#586071" stroke-width="2"/>

                            <!-- Baggy Cyan Trousers (Crouching Stance) -->
                            <path d="M88 144 Q105 158 116 188 L92 188 Q82 165 88 144 Z" fill="url(#chibiPantsGrad)"/>
                            <path d="M142 144 Q160 156 172 182 L150 182 Q136 160 142 144 Z" fill="url(#chibiPantsGrad)"/>
                            <path d="M106 142 Q128 152 148 142 L142 162 Q125 168 110 162 Z" fill="#1d4e89"/>

                            <!-- Flowing Ribbon Waist Sash -->
                            <path d="M82 142 C70 148 60 160 52 175 C62 172 74 160 84 148 Z" fill="url(#robePurpleGrad)"/>
                            <path d="M80 145 C65 152 52 168 45 185 C58 180 72 166 82 152 Z" fill="url(#robePurpleGrad)" opacity="0.85"/>

                            <!-- Off-the-Shoulder Slate Robe & Bare Right Chest -->
                            <path d="M110 106 Q130 108 142 118 L138 144 L104 144 Z" fill="url(#chibiSkinGrad)"/>
                            <path d="M102 108 C115 110 135 115 146 122 L148 145 L98 145 Z" fill="url(#robePurpleGrad)" filter="url(#softShadow)"/>
                            <path d="M125 112 C135 118 145 125 148 138 L138 145 Z" fill="#2d3142"/>

                            <!-- Chibi Head Structure -->
                            <path d="M140 38 C158 35 175 42 192 48 C176 52 162 50 142 46 Z" fill="url(#orangeRibbonGrad)"/>
                            <path d="M138 42 C154 45 170 56 185 64 C170 62 158 56 138 48 Z" fill="url(#orangeRibbonGrad)" opacity="0.85"/>

                            <!-- High Spiky Ponytail -->
                            <path d="M122 38 C130 20 152 12 168 16 C155 30 145 42 130 46 Z" fill="url(#chibiHairGrad)"/>

                            <!-- Chibi Face Base -->
                            <path d="M88 68 C80 40 138 35 145 68 C148 94 92 100 88 68 Z" fill="url(#chibiSkinGrad)" filter="url(#softShadow)"/>
                            <path d="M138 68 C145 65 148 76 142 80 Z" fill="url(#chibiSkinGrad)"/>

                            <!-- Jet Black Hair Structure & Signature Sweeping Bangs -->
                            <path d="M88 65 C85 42 110 32 135 38 C142 45 140 58 138 65 Q115 45 88 65 Z" fill="url(#chibiHairGrad)"/>
                            <path d="M130 44 C110 42 85 58 80 82 C92 72 110 60 132 58 Z" fill="url(#chibiHairGrad)"/>
                            <path d="M115 42 C100 48 88 62 82 72 C92 64 108 55 122 52 Z" fill="#1b1d28"/>

                            <!-- Heroic Eyebrows -->
                            <path d="M96 66 L114 60 L122 65" stroke="#11131a" stroke-width="3.5" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M125 65 L138 62" stroke="#11131a" stroke-width="3" fill="none" stroke-linecap="round"/>

                            <!-- Intense Anime Eyes -->
                            <g id="chibiEyes">
                                <ellipse cx="108" cy="74" rx="5.5" ry="7" fill="#11131a"/>
                                <ellipse cx="109" cy="73" rx="3.5" ry="5" fill="#2d3142"/>
                                <circle cx="107" cy="71" r="1.8" fill="#ffffff"/>
                                <circle cx="110" cy="76" r="0.9" fill="#ffffff"/>

                                <ellipse cx="132" cy="72" rx="4.5" ry="6" fill="#11131a"/>
                                <circle cx="131" cy="70" r="1.5" fill="#ffffff"/>
                            </g>

                            <!-- Determined Mouth Line -->
                            <path d="M110 88 L122 86" stroke="#8a3030" stroke-width="2" stroke-linecap="round"/>

                            <!-- Bare Right Arm Holding Bow Line -->
                            <path d="M128 118 L152 108 L168 104" stroke="url(#chibiSkinGrad)" stroke-width="9" stroke-linecap="round" stroke-linejoin="round"/>

                            <!-- Left Arm Pulling Bowstring -->
                            <path id="pullingArm" d="M106 122 L128 112 L148 102" stroke="url(#chibiSkinGrad)" stroke-width="9" stroke-linecap="round" stroke-linejoin="round"/>

                            <!-- Wooden Recurve Bow -->
                            <g filter="url(#softShadow)">
                                <path id="bowArc" d="M148 38 Q195 100 158 162" stroke="url(#chibiBowGrad)" stroke-width="6.5" stroke-linecap="round" fill="none"/>
                                <path d="M148 38 Q144 30 152 26" stroke="#ffb703" stroke-width="3" fill="none"/>
                                <path d="M158 162 Q156 170 164 172" stroke="#ffb703" stroke-width="3" fill="none"/>
                            </g>

                            <!-- Bow String -->
                            <path id="bowString" d="M148 38 L148 102 L158 162" stroke="#fef08a" stroke-width="1.8" fill="none"/>

                            <!-- Ready Arrow on Bow -->
                            <g id="svgReadyArrow" filter="url(#softShadow)">
                                <line x1="120" y1="102" x2="182" y2="88" stroke="#e9c46a" stroke-width="3.5"/>
                                <polygon points="182,80 198,86 184,95" fill="#e2e8f0" stroke="#64748b" stroke-width="1.2"/>
                                <polygon points="120,99 110,104 117,107" fill="#212529"/>
                            </g>
                        </g>
                    </svg>
                </div>
            </div>

            <!-- Primary "CLICK" Action Button -->
            <div class="mt-1 flex flex-col items-center">
                <button id="shootBtn" onclick="shootArrow()" class="btn-pulse relative group px-10 py-3.5 rounded-full bg-gradient-to-r from-amber-500 via-red-500 to-amber-600 text-slate-950 font-cinzel font-extrabold text-lg md:text-xl tracking-widest shadow-2xl transform active:scale-95 transition-all duration-200 border-2 border-amber-300/80 cursor-pointer flex items-center space-x-3">
                    <i class="fa-solid fa-crosshairs text-slate-950 group-hover:rotate-45 transition-transform duration-300"></i>
                    <span>CLICK</span>
                    <i class="fa-solid fa-feather text-slate-950"></i>
                </button>
                <span class="text-xs text-amber-200/80 font-medium mt-1.5">Click to release an arrow at the celestial moons</span>
            </div>
        </div>
    </main>

    <div id="questionModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-950/80 backdrop-blur-md opacity-0 pointer-events-none transition-all duration-500">
        <div class="glass-modal w-full max-w-lg rounded-2xl p-6 md:p-8 flex flex-col items-center text-center relative transform scale-90 transition-all duration-500 shadow-2xl border border-indigo-500/30" id="modalContent">
            
            <!-- Falling Moon Mini Icon Header -->
            <div class="w-16 h-16 rounded-full bg-gradient-to-br from-amber-200 to-indigo-600 p-0.5 shadow-lg shadow-amber-300/30 mb-4 animate-bounce">
                <div class="w-full h-full rounded-full bg-slate-950 flex items-center justify-center">
                    <i id="modalMoonIcon" class="fa-solid fa-moon text-3xl text-amber-300"></i>
                </div>
            </div>

            <!-- Q1 to Q9 Moon Box Indicator -->
            <div class="px-5 py-1.5 bg-amber-500/20 border border-amber-400/40 rounded-lg mb-3 shadow-sm">
                <span id="modalMoonTag" class="text-base font-cinzel font-extrabold tracking-widest text-amber-300 uppercase">
                    Q1
                </span>
            </div>

            <!-- Header sentence -->
            <h3 id="modalQuestionTitle" class="font-cinzel text-sm md:text-base font-bold text-slate-100 mb-3 leading-relaxed">
                After you answer this question, you can shoot another moon in the sky.
            </h3>

            <!-- Specific Question Prompt for Q1-Q9 -->
            <p id="modalQuestionPrompt" class="text-xs md:text-sm text-amber-200/90 italic font-medium mb-5 px-4 py-2 rounded-lg bg-slate-900/80 border border-amber-500/30 w-full text-center shadow-inner">
                Question prompt loading...
            </p>

            <!-- Question Box Text Input Area -->
            <div id="quizContainer" class="w-full mb-6 flex flex-col items-center">
                <!-- SVG Illustration Container -->
                <div id="quizIllustration" class="w-full max-w-sm h-40 rounded-xl overflow-hidden mb-3 border border-amber-400/40 shadow-lg relative bg-slate-950 flex items-center justify-center">
                </div>

                <!-- Answer Sentence Input Box -->
                <div class="w-full bg-slate-900/90 border border-amber-500/40 rounded-xl p-3.5 flex flex-col sm:flex-row items-center justify-between gap-2 shadow-inner">
                    <span id="answerPrefixLabel" class="text-sm font-bold text-amber-200 whitespace-nowrap">Answer:</span>
                    <input type="text" id="quizAnswerInput" placeholder="type answer here..." class="w-full bg-slate-950 border border-indigo-500/50 rounded-lg px-3 py-2 text-sm text-slate-100 font-semibold focus:outline-none focus:border-amber-400 focus:ring-1 focus:ring-amber-400/30 transition-all text-center" onkeyup="handleQuizInput(event)">
                    <span id="answerSuffixLabel" class="text-sm font-bold text-amber-200 whitespace-nowrap"></span>
                    <button onclick="checkQuizAnswer()" class="w-full sm:w-auto px-4 py-2 rounded-lg bg-amber-500 hover:bg-amber-400 text-slate-950 font-cinzel font-bold text-xs tracking-wider transition-colors shadow">
                        CHECK
                    </button>
                </div>

                <!-- Feedback Display Box -->
                <div id="quizFeedback" class="mt-2 text-xs font-bold flex items-center space-x-2 min-h-[24px]"></div>
            </div>

            <!-- "RETURN" Button to return to archer main page -->
            <button id="returnBtn" onclick="closeQuestionBox()" class="w-full py-3.5 px-6 rounded-xl bg-gradient-to-r from-indigo-600 via-purple-600 to-amber-600 text-white font-cinzel font-bold tracking-wider hover:brightness-110 active:scale-98 transition-all shadow-lg shadow-indigo-600/30 flex items-center justify-center space-x-2">
                <span>RETURN</span>
                <i class="fa-solid fa-arrow-right-from-bracket text-sm"></i>
            </button>
        </div>
    </div>

    <div id="journalModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-950/85 backdrop-blur-md opacity-0 pointer-events-none transition-all duration-300">
        <div class="glass-modal w-full max-w-2xl max-h-[85vh] rounded-2xl p-6 md:p-8 flex flex-col relative border border-amber-500/30 shadow-2xl">
            <div class="flex justify-between items-center mb-6 border-b border-indigo-900/50 pb-4">
                <div class="flex items-center space-x-3">
                    <i class="fa-solid fa-book-journal-whills text-2xl text-amber-400"></i>
                    <div>
                        <h2 class="font-cinzel text-xl font-bold text-amber-200">Celestial Journal</h2>
                        <p class="text-xs text-indigo-300/70">Your reflections recorded with each fallen moon</p>
                    </div>
                </div>
                <button onclick="closeJournal()" class="text-slate-400 hover:text-white p-2 rounded-lg hover:bg-slate-800 transition-colors">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>

            <div id="journalEntriesList" class="flex-1 overflow-y-auto space-y-4 pr-2">
                <!-- Journal entries populated via JS -->
            </div>

            <div class="mt-6 pt-4 border-t border-indigo-900/50 flex justify-between items-center">
                <span id="journalCount" class="text-xs text-indigo-300/80 font-medium">0 of 9 Moons Shot</span>
                <button onclick="closeJournal()" class="px-5 py-2 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold tracking-wider transition-colors">
                    Close Journal
                </button>
            </div>
        </div>
    </div>

    <div id="completionModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-950/90 backdrop-blur-lg opacity-0 pointer-events-none transition-all duration-700">
        <div class="glass-modal w-full max-w-lg rounded-2xl p-8 flex flex-col items-center text-center border border-amber-400/40 shadow-2xl">
            <div class="w-20 h-20 rounded-full bg-gradient-to-tr from-amber-400 to-yellow-200 flex items-center justify-center shadow-xl shadow-amber-400/30 mb-6 animate-pulse">
                <i class="fa-solid fa-crown text-4xl text-slate-950"></i>
            </div>
            <h2 class="font-cinzel text-2xl md:text-3xl font-extrabold text-amber-300 mb-2">
                SKY HARMONY RESTORED
            </h2>
            <p class="text-sm text-indigo-200/90 mb-6 leading-relaxed">
                All 9 moons have gracefully fallen. Your words and wishes now illuminate the starry realm eternal.
            </p>
            <div class="flex space-x-4 w-full">
                <button onclick="openJournal(); closeCompletionModal();" class="flex-1 py-3 rounded-xl bg-slate-800 hover:bg-slate-700 text-amber-300 font-cinzel font-semibold text-xs tracking-wider border border-amber-500/30 transition-all">
                    VIEW JOURNAL
                </button>
                <button onclick="resetGame()" class="flex-1 py-3 rounded-xl bg-gradient-to-r from-amber-500 to-indigo-600 text-slate-950 font-cinzel font-bold text-xs tracking-wider hover:brightness-110 transition-all shadow-lg shadow-amber-500/20">
                    RESTART JOURNEY
                </button>
            </div>
        </div>
    </div>

    <script>
        let arrowsRemaining = 9;
        let moons = [];
        let activeFallingMoonIndex = null;
        let isShooting = false;
        let audioEnabled = true;
        let journalData = Array(9).fill("");
        let bgmActive = false;
        let bgmInterval = null;

        /* 
           ==========================================================================
           QUESTION CONFIGURATION (MOON 1 TO MOON 9)
           ==========================================================================
           You can change any question's lines here!
           
           Properties for each question:
           - title: The subtitle below the moon (e.g. "Moon of Eternity")
           - prompt: The main question line shown in the pop-up modal
           - prefix: Text displayed BEFORE the input box (e.g. "Answer: Mike and his friends are having a")
           - suffix: Text displayed AFTER the input box (e.g. "Moon Festival.")
           - correctAnswer: Array of acceptable answers for checking (e.g. ["green"])
           - hasQuiz: Set to true for answer checking, or false for open-ended writing
           ==========================================================================
        */
        const moonQuestions = [
            { title: "Moon of Celebration", prompt: "Q1: What can we do on Moon Festival?", prefix: "Answer: We have a", suffix: ".", correctAnswer: ["barbecue", "barbeque", "bbq"], hasQuiz: true },
            { title: "Moon of Observation", prompt: "Q2: What do we do on Moon festival?", prefix: "Answer: We watch the", suffix: "moon.", correctAnswer: ["full"], hasQuiz: true },
            { title: "Moon of Gratitude", prompt: "Q3: What do we eat on Moon festival?", prefix: "Answer: We eat", suffix: ".", correctAnswer: ["mooncakes", "mooncake", "moon cakes", "moon cake"], hasQuiz: true },
            { title: "Moon of Courage", prompt: "Q4: What do we do on Moon festival?", prefix: "Answer: We", suffix: "the pomelo.", correctAnswer: ["peel"], hasQuiz: true },
            { title: "Moon of Harmony", prompt: "Q5: When we go grocery shopping, we should do _____ shopping.", prefix: "Answer: We should do", suffix: "shopping.", correctAnswer: ["nacked", "naked"], hasQuiz: true },
            
            // =========================================================================
            // QUESTION 6 CONFIGURATION
            // Change any of the values below to update the lines in the answer box:
            // =========================================================================
            { 
                title: "Moon of Creativity", 
                prompt: "Q6: Mike and his friends are having a _____ Moon Festival.", // Prompt above input box
                prefix: "Answer:",              // Text BEFORE input box
                suffix: "",                                          // Text AFTER input box
                correctAnswer: ["green"],                                          // Correct answer(s) to check
                hasQuiz: true 
            },
            
            { title: "Moon of Connection", prompt: "Q7: We can use the peel for _____.", prefix: "Answer: We can use the peel for", suffix: ".", correctAnswer: ["cleaning"], hasQuiz: true },
            { title: "Moon of Wisdom", prompt: "Q8: The Moon Festival this year is on September _____.", prefix: "Answer: September", suffix: "", correctAnswer: ["25", "25th", "25."], hasQuiz: true },
            { title: "Moon of Eternity", prompt: "Q9: What's your wish to the moon?", prefix: "Answer: I wish for", suffix: ".", correctAnswer: ["peace", "happiness", "love", "health"], hasQuiz: false }
        ];

        // SVG Illustrations for Q1 - Q8
        const q1IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="skyGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#fbbf24"/>
                        <stop offset="50%" stop-color="#fef08a"/>
                        <stop offset="100%" stop-color="#86efac"/>
                    </linearGradient>
                    <linearGradient id="grillGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#374151"/>
                        <stop offset="100%" stop-color="#111827"/>
                    </linearGradient>
                </defs>
                <rect width="400" height="200" fill="url(#skyGrad)"/>
                <path d="M0 130 Q100 110 200 135 T400 125 L400 200 L0 200 Z" fill="#4ade80"/>
                <path d="M-10 100 Q40 60 90 100 Q150 50 210 110 Z" fill="#22c55e" opacity="0.6"/>
                <path d="M220 90 Q280 40 340 90 Q380 60 410 100 Z" fill="#16a34a" opacity="0.5"/>
                <rect x="230" y="140" width="130" height="12" rx="3" fill="#b45309"/>
                <rect x="250" y="152" width="10" height="30" fill="#78350f"/>
                <rect x="320" y="152" width="10" height="30" fill="#78350f"/>
                <circle cx="260" cy="125" r="12" fill="#fde047"/>
                <circle cx="295" cy="118" r="14" fill="#fda4af"/>
                <circle cx="335" cy="115" r="15" fill="#fca5a5"/>
                <ellipse cx="110" cy="150" rx="35" ry="12" fill="url(#grillGrad)"/>
                <path d="M75 150 C75 175 145 175 145 150 Z" fill="url(#grillGrad)"/>
                <line x1="85" y1="170" x2="70" y2="195" stroke="#111827" stroke-width="4"/>
                <line x1="135" y1="170" x2="150" y2="195" stroke="#111827" stroke-width="4"/>
                <line x1="110" y1="172" x2="110" y2="198" stroke="#111827" stroke-width="4"/>
                <ellipse cx="110" cy="148" rx="28" ry="8" fill="#ef4444"/>
                <line x1="88" y1="145" x2="132" y2="145" stroke="#f97316" stroke-width="3" stroke-linecap="round"/>
                <line x1="92" y1="150" x2="128" y2="150" stroke="#fbbf24" stroke-width="3" stroke-linecap="round"/>
                <path d="M100 140 Q95 120 105 105 T95 85" fill="none" stroke="#ffffff" stroke-width="2" opacity="0.6"/>
                <path d="M120 140 Q125 120 115 105 T125 85" fill="none" stroke="#ffffff" stroke-width="2" opacity="0.6"/>
                <circle cx="55" cy="105" r="16" fill="#fbcfe8"/>
                <path d="M40 125 C40 105 70 105 70 125 L65 180 L45 180 Z" fill="#38bdf8"/>
                <path d="M46 125 L64 125 L60 175 L50 175 Z" fill="#fef3c7"/>
                <path d="M62 135 L88 145" stroke="#fbcfe8" stroke-width="5" stroke-linecap="round"/>
                <path d="M85 143 L98 147 M85 147 L98 147" stroke="#9ca3af" stroke-width="2"/>
            </svg>
        `;

        const q2IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="nightSkyGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#0b132b"/>
                        <stop offset="50%" stop-color="#1c2541"/>
                        <stop offset="100%" stop-color="#1e1b4b"/>
                    </linearGradient>
                    <filter id="moonSoftGlow" x="-50%" y="-50%" width="200%" height="200%">
                        <feGaussianBlur stdDeviation="5" result="blur" />
                        <feComposite in="SourceGraphic" in2="blur" operator="over"/>
                    </filter>
                </defs>
                <rect width="400" height="200" fill="url(#nightSkyGrad)"/>

                <circle cx="40" cy="30" r="1" fill="#fff" opacity="0.8"/>
                <circle cx="120" cy="20" r="1.5" fill="#fff" opacity="0.9"/>
                <circle cx="210" cy="45" r="1" fill="#fff" opacity="0.7"/>
                <circle cx="280" cy="25" r="1.2" fill="#fff" opacity="0.8"/>
                <circle cx="350" cy="50" r="1" fill="#fff" opacity="0.9"/>
                <circle cx="180" cy="80" r="1" fill="#fff" opacity="0.6"/>
                <circle cx="310" cy="90" r="1.5" fill="#fef08a" opacity="0.8"/>

                <circle cx="70" cy="45" r="26" fill="#fef08a" opacity="0.25" />
                <circle cx="70" cy="45" r="18" fill="#fffde7" filter="url(#moonSoftGlow)"/>
                <circle cx="64" cy="40" r="3" fill="#ebd280" opacity="0.4"/>
                <circle cx="75" cy="48" r="4" fill="#ebd280" opacity="0.3"/>

                <path d="M0 200 L0 170 Q100 150 200 175 T400 165 L400 200 Z" fill="#0d1322"/>

                <g transform="translate(145, 65)">
                    <circle cx="30" cy="18" r="10" fill="#1e1b18"/>
                    <path d="M 22 22 Q 30 12 38 22 Z" fill="#2d2824"/>
                    <rect x="27" y="26" width="6" height="6" fill="#3a322c"/>
                    <path d="M 10 32 C 15 30 45 30 50 32 L 47 95 C 38 97 22 97 13 95 Z" fill="#94a3b8"/>
                    <path d="M 10 32 L 2 68 L 11 70 L 17 40 Z" fill="#64748b"/>
                    <path d="M 50 32 L 58 68 L 49 70 L 43 40 Z" fill="#64748b"/>
                    <path d="M 13 95 L 28 135 L 32 135 L 47 95 Z" fill="#1e293b"/>
                </g>

                <g transform="translate(225, 115)">
                    <circle cx="20" cy="12" r="9" fill="#1e1b18"/>
                    <path d="M 10 10 C 10 22 30 22 30 10 Z" fill="#2d2824"/>
                    <path d="M 8 20 C 12 18 28 18 32 20 L 34 50 C 26 53 14 53 6 50 Z" fill="#f43f5e"/>
                    <path d="M 8 20 L 2 35 L 7 37 L 12 25 Z" fill="#e11d48"/>
                    <path d="M 32 20 L 38 35 L 33 37 L 28 25 Z" fill="#e11d48"/>
                    <path d="M 7 50 L 14 85 L 26 85 L 33 50 Z" fill="#1e1b4b"/>
                </g>
            </svg>
        `;

        const q3IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="matGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#a3e635"/>
                        <stop offset="50%" stop-color="#84cc16"/>
                        <stop offset="100%" stop-color="#65a30d"/>
                    </linearGradient>
                    <linearGradient id="woodGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#fde68a"/>
                        <stop offset="50%" stop-color="#f59e0b"/>
                        <stop offset="100%" stop-color="#d97706"/>
                    </linearGradient>
                    <linearGradient id="crustGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#fbbf24"/>
                        <stop offset="60%" stop-color="#d97706"/>
                        <stop offset="100%" stop-color="#92400e"/>
                    </linearGradient>
                    <linearGradient id="pasteGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#fef08a"/>
                        <stop offset="50%" stop-color="#eab308"/>
                        <stop offset="100%" stop-color="#ca8a04"/>
                    </linearGradient>
                </defs>

                <rect width="400" height="200" fill="url(#matGrad)"/>
                <g stroke="#4d7c0f" stroke-width="1.5" opacity="0.3">
                    <line x1="0" y1="20" x2="400" y2="20"/><line x1="0" y1="40" x2="400" y2="40"/>
                    <line x1="0" y1="60" x2="400" y2="60"/><line x1="0" y1="80" x2="400" y2="80"/>
                    <line x1="0" y1="100" x2="400" y2="100"/><line x1="0" y1="120" x2="400" y2="120"/>
                    <line x1="0" y1="140" x2="400" y2="140"/><line x1="0" y1="160" x2="400" y2="160"/>
                    <line x1="0" y1="180" x2="400" y2="180"/>
                </g>

                <ellipse cx="140" cy="35" rx="22" ry="10" fill="#ffffff" stroke="#e2e8f0" stroke-width="2"/>
                <ellipse cx="140" cy="35" rx="18" ry="7" fill="#f59e0b" opacity="0.8"/>
                <ellipse cx="270" cy="30" rx="20" ry="9" fill="#ffffff" stroke="#e2e8f0" stroke-width="2"/>
                <ellipse cx="270" cy="30" rx="16" ry="6" fill="#f59e0b" opacity="0.8"/>

                <rect x="30" y="65" width="260" height="120" rx="16" fill="url(#woodGrad)" stroke="#b45309" stroke-width="3"/>
                <rect x="38" y="73" width="244" height="104" rx="12" fill="#fef3c7" opacity="0.3"/>

                <g transform="translate(45, 75)">
                    <ellipse cx="80" cy="55" rx="58" ry="32" fill="url(#crustGrad)" stroke="#78350f" stroke-width="2"/>
                    <ellipse cx="80" cy="48" rx="52" ry="26" fill="#f59e0b" stroke="#b45309" stroke-width="2"/>
                    <ellipse cx="80" cy="48" rx="42" ry="20" fill="none" stroke="#78350f" stroke-width="2" stroke-dasharray="4,2"/>
                    <ellipse cx="80" cy="48" rx="24" ry="11" fill="none" stroke="#78350f" stroke-width="2"/>
                    <circle cx="80" cy="48" r="4" fill="#ef4444"/>
                    <path d="M70 48 Q80 40 90 48 Q80 56 70 48 Z" fill="none" stroke="#78350f" stroke-width="1.5"/>
                    <polygon points="80,48 135,58 120,80 80,48" fill="url(#pasteGrad)" stroke="#b45309" stroke-width="1.5"/>
                    <circle cx="102" cy="62" r="7" fill="#ef4444"/>
                </g>

                <g transform="translate(185, 95)">
                    <polygon points="10,10 65,22 45,45 10,10" fill="url(#pasteGrad)" stroke="#b45309" stroke-width="2"/>
                    <path d="M 65 22 Q 58 35 45 45 L 65 22 Z" fill="url(#crustGrad)" stroke="#78350f" stroke-width="2"/>
                    <circle cx="34" cy="25" r="6" fill="#ef4444"/>
                </g>

                <g transform="translate(260, 85)">
                    <path d="M120 70 C80 50 60 20 20 22 C10 23 5 18 15 12 C30 10 60 25 70 12 C75 5 85 8 80 18 C95 18 105 30 130 50 Z" fill="#ffe4e6" stroke="#f43f5e" stroke-width="2"/>
                </g>
            </svg>
        `;

        const q4IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="pomBgGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#1e293b"/>
                        <stop offset="100%" stop-color="#0f172a"/>
                    </linearGradient>
                    <linearGradient id="pomSkinGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#84cc16"/>
                        <stop offset="60%" stop-color="#65a30d"/>
                        <stop offset="100%" stop-color="#4d7c0f"/>
                    </linearGradient>
                    <linearGradient id="pithGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#ffffff"/>
                        <stop offset="100%" stop-color="#fef3c7"/>
                    </linearGradient>
                </defs>
                <rect width="400" height="200" fill="url(#pomBgGrad)"/>
                
                <g transform="translate(140, 25)">
                    <ellipse cx="60" cy="70" rx="46" ry="52" fill="url(#pithGrad)" stroke="#e2e8f0" stroke-width="2"/>
                    <path d="M 45 35 Q 60 70 45 105 M 60 28 Q 60 70 60 112 M 75 35 Q 60 70 75 105" stroke="#fbbf24" stroke-width="2" opacity="0.4" fill="none"/>

                    <path d="M 18 50 C -25 30 -35 95 -12 118 C 8 108 18 85 18 50 Z" fill="url(#pomSkinGrad)" stroke="#3f6212" stroke-width="2"/>
                    <path d="M 18 50 C -5 50 -5 100 -12 118 C 8 98 12 78 18 50 Z" fill="#fde047" opacity="0.75"/>

                    <path d="M 102 50 C 145 30 155 95 132 118 C 112 108 102 85 102 50 Z" fill="url(#pomSkinGrad)" stroke="#3f6212" stroke-width="2"/>
                    <path d="M 102 50 C 125 50 125 100 132 118 C 112 98 108 78 102 50 Z" fill="#fde047" opacity="0.75"/>

                    <path d="M 30 112 C 20 160 100 160 90 112 C 75 125 45 125 30 112 Z" fill="url(#pomSkinGrad)" stroke="#3f6212" stroke-width="2"/>
                </g>

                <g transform="translate(20, 20)">
                    <path d="M 30 50 C 60 30 110 35 128 60 C 120 72 95 75 65 62 L 30 70 Z" fill="#fca5a5" stroke="#e11d48" stroke-width="2"/>
                </g>
                <g transform="translate(180, 75)">
                    <path d="M 175 65 C 145 55 105 48 90 62 C 98 75 120 85 150 78 L 180 90 Z" fill="#fca5a5" stroke="#e11d48" stroke-width="2"/>
                </g>
            </svg>
        `;

        const q5IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="shopBgGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#1e293b"/>
                        <stop offset="100%" stop-color="#0f172a"/>
                    </linearGradient>
                    <linearGradient id="crateGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#d97706"/>
                        <stop offset="100%" stop-color="#78350f"/>
                    </linearGradient>
                </defs>
                <rect width="400" height="200" fill="url(#shopBgGrad)"/>
                
                <rect x="70" y="80" width="260" height="95" rx="8" fill="url(#crateGrad)" stroke="#451a03" stroke-width="3"/>
                <line x1="70" y1="110" x2="330" y2="110" stroke="#451a03" stroke-width="2"/>
                <line x1="70" y1="140" x2="330" y2="140" stroke="#451a03" stroke-width="2"/>

                <rect x="120" y="22" width="160" height="36" rx="18" fill="#16a34a" stroke="#bbf7d0" stroke-width="2"/>
                <text x="200" y="45" font-family="sans-serif" font-size="14" font-weight="bold" fill="#ffffff" text-anchor="middle">NAKED SHOPPING</text>

                <circle cx="110" cy="75" r="18" fill="#ef4444"/>
                <path d="M110 57 Q113 52 118 50" stroke="#78350f" stroke-width="2" fill="none"/>
                <circle cx="140" cy="78" r="17" fill="#dc2626"/>

                <circle cx="175" cy="72" r="19" fill="#f97316"/>
                <circle cx="210" cy="75" r="18" fill="#fb923c"/>

                <circle cx="245" cy="74" r="17" fill="#84cc16"/>
                <circle cx="280" cy="78" r="18" fill="#65a30d"/>

                <path d="M 290 60 C 330 50 350 110 320 130 C 290 140 270 100 290 60 Z" fill="#fef3c7" opacity="0.3" stroke="#fde047" stroke-width="2" stroke-dasharray="4 3"/>
            </svg>
        `;

        const q6IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="greenBgGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#064e3b"/>
                        <stop offset="50%" stop-color="#022c22"/>
                        <stop offset="100%" stop-color="#0f172a"/>
                    </linearGradient>
                    <linearGradient id="greenMoonGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#a7f3d0"/>
                        <stop offset="50%" stop-color="#34d399"/>
                        <stop offset="100%" stop-color="#059669"/>
                    </linearGradient>
                </defs>
                <rect width="400" height="200" fill="url(#greenBgGrad)"/>
                
                <circle cx="200" cy="70" r="35" fill="url(#greenMoonGrad)" filter="drop-shadow(0 0 15px #34d399)"/>
                <circle cx="200" cy="70" r="30" fill="#ecfdf5" opacity="0.9"/>
                
                <path d="M 160 70 C 150 50 170 40 180 55 C 170 65 160 70 160 70 Z" fill="#10b981"/>
                <path d="M 240 70 C 250 50 230 40 220 55 C 230 65 240 70 240 70 Z" fill="#10b981"/>
                
                <rect x="90" y="130" width="220" height="36" rx="18" fill="#047857" stroke="#6ee7b7" stroke-width="2"/>
                <text x="200" y="153" font-family="sans-serif" font-size="14" font-weight="bold" fill="#ffffff" text-anchor="middle">GREEN MOON FESTIVAL</text>
            </svg>
        `;

        const q7IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="cleanBgGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#0f172a"/>
                        <stop offset="100%" stop-color="#1e293b"/>
                    </linearGradient>
                    <linearGradient id="sprayGrad" x1="0" y1="0" x2="1" y2="1">
                        <stop offset="0%" stop-color="#38bdf8"/>
                        <stop offset="100%" stop-color="#0284c7"/>
                    </linearGradient>
                </defs>
                <rect width="400" height="200" fill="url(#cleanBgGrad)"/>
                
                <g transform="translate(100, 25)">
                    <rect x="110" y="60" width="50" height="85" rx="10" fill="url(#sprayGrad)" stroke="#e0f2fe" stroke-width="2"/>
                    <path d="M 125 60 L 125 40 L 145 40 L 145 60 Z" fill="#94a3b8"/>
                    <path d="M 145 40 L 170 35 L 170 48 L 145 48 Z" fill="#38bdf8"/>
                    
                    <path d="M 125 90 C 120 110 150 110 145 90 Z" fill="#84cc16"/>
                    <text x="135" y="125" font-family="sans-serif" font-size="10" font-weight="bold" fill="#ffffff" text-anchor="middle">CLEAN</text>

                    <path d="M 40 100 C 10 70 20 130 60 135 C 75 125 70 105 40 100 Z" fill="#84cc16" stroke="#4d7c0f" stroke-width="2"/>
                    <path d="M 45 105 C 25 80 30 120 55 125 Z" fill="#fef08a"/>

                    <path d="M 200 40 L 205 50 L 215 55 L 205 60 L 200 70 L 195 60 L 185 55 L 195 50 Z" fill="#fef08a"/>
                    <path d="M 230 80 L 233 87 L 240 90 L 233 93 L 230 100 L 227 93 L 220 90 L 227 87 Z" fill="#38bdf8"/>
                    <path d="M 80 50 L 83 57 L 90 60 L 83 63 L 80 70 L 77 63 L 70 60 L 77 57 Z" fill="#ffffff"/>
                </g>
            </svg>
        `;

        const q8IllustrationSVG = `
            <svg viewBox="0 0 400 200" class="w-full h-full object-cover">
                <defs>
                    <linearGradient id="calBgGrad" x1="0" y1="0" x2="0" y2="1">
                        <stop offset="0%" stop-color="#1e1b4b"/>
                        <stop offset="100%" stop-color="#0f172a"/>
                    </linearGradient>
                    <linearGradient id="calHeaderGrad" x1="0" y1="0" x2="1" y2="0">
                        <stop offset="0%" stop-color="#dc2626"/>
                        <stop offset="100%" stop-color="#f59e0b"/>
                    </linearGradient>
                </defs>
                <rect width="400" height="200" fill="url(#calBgGrad)"/>
                
                <!-- Calendar Card -->
                <rect x="110" y="20" width="180" height="160" rx="16" fill="#0d1127" stroke="#f59e0b" stroke-width="2.5" filter="drop-shadow(0 0 15px rgba(245,158,11,0.3))"/>
                
                <!-- Calendar Top Banner -->
                <path d="M110 36 C110 27 117 20 126 20 L274 20 C283 20 290 27 290 36 L290 65 L110 65 Z" fill="url(#calHeaderGrad)"/>
                <text x="200" y="48" font-family="sans-serif" font-size="16" font-weight="extrabold" fill="#ffffff" text-anchor="middle" letter-spacing="2">SEPTEMBER</text>

                <!-- Binder Rings -->
                <rect x="140" y="12" width="12" height="16" rx="6" fill="#e2e8f0"/>
                <rect x="248" y="12" width="12" height="16" rx="6" fill="#e2e8f0"/>

                <!-- Highlighted Date Number 25 -->
                <circle cx="200" cy="120" r="38" fill="#fef08a" opacity="0.2"/>
                <circle cx="200" cy="120" r="32" fill="#fbbf24" stroke="#f59e0b" stroke-width="2"/>
                <text x="200" y="132" font-family="sans-serif" font-size="34" font-weight="900" fill="#0f172a" text-anchor="middle">25</text>

                <!-- Moon Icon Decor -->
                <path d="M 250 85 C 245 80 248 70 255 68 C 250 72 250 80 255 82 Z" fill="#fef08a"/>
            </svg>
        `;

        // Web Audio API Sound Synthesizer
        let audioCtx = null;

        function initAudio() {
            if (!audioCtx) {
                audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            }
        }

        function startBGM() {
            if (bgmActive || !audioEnabled) return;
            bgmActive = true;
            try {
                initAudio();
                if (audioCtx && audioCtx.state === 'suspended') {
                    audioCtx.resume();
                }
                if (!bgmInterval) {
                    const notes = [261.63, 293.66, 329.63, 392.00, 440.00, 523.25];
                    bgmInterval = setInterval(() => {
                        if (!audioEnabled || !bgmActive || !audioCtx) return;
                        try {
                            const now = audioCtx.currentTime;
                            const freq = notes[Math.floor(Math.random() * notes.length)];
                            const osc = audioCtx.createOscillator();
                            const gain = audioCtx.createGain();
                            osc.type = 'sine';
                            osc.frequency.setValueAtTime(freq, now);
                            gain.gain.setValueAtTime(0.015, now);
                            gain.gain.exponentialRampToValueAtTime(0.0001, now + 1.8);
                            osc.connect(gain);
                            gain.connect(audioCtx.destination);
                            osc.start(now);
                            osc.stop(now + 1.8);
                        } catch (err) {}
                    }, 1800);
                }
            } catch (e) {
                console.log("Start BGM error:", e);
            }
        }

        function stopBGM() {
            bgmActive = false;
            if (bgmInterval) {
                clearInterval(bgmInterval);
                bgmInterval = null;
            }
        }

        function playSound(type) {
            if (!audioEnabled) return;
            try {
                initAudio();
                const now = audioCtx.currentTime;

                if (type === 'bow') {
                    const osc = audioCtx.createOscillator();
                    const gain = audioCtx.createGain();
                    osc.type = 'triangle';
                    osc.frequency.setValueAtTime(120, now);
                    osc.frequency.exponentialRampToValueAtTime(400, now + 0.15);
                    gain.gain.setValueAtTime(0.3, now);
                    gain.gain.exponentialRampToValueAtTime(0.01, now + 0.15);
                    osc.connect(gain);
                    gain.connect(audioCtx.destination);
                    osc.start(now);
                    osc.stop(now + 0.15);
                } 
                else if (type === 'whoosh') {
                    const bufferSize = audioCtx.sampleRate * 0.3;
                    const buffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
                    const data = buffer.getChannelData(0);
                    for (let i = 0; i < bufferSize; i++) {
                        data[i] = Math.random() * 2 - 1;
                    }
                    const noise = audioCtx.createBufferSource();
                    noise.buffer = buffer;
                    const filter = audioCtx.createBiquadFilter();
                    filter.type = 'bandpass';
                    filter.frequency.setValueAtTime(800, now);
                    filter.frequency.exponentialRampToValueAtTime(200, now + 0.3);
                    const gain = audioCtx.createGain();
                    gain.gain.setValueAtTime(0.2, now);
                    gain.gain.linearRampToValueAtTime(0.01, now + 0.3);
                    noise.connect(filter);
                    filter.connect(gain);
                    gain.connect(audioCtx.destination);
                    noise.start(now);
                } 
                else if (type === 'hit') {
                    [523.25, 659.25, 783.99, 1046.50].forEach((freq, idx) => {
                        const osc = audioCtx.createOscillator();
                        const gain = audioCtx.createGain();
                        osc.type = 'sine';
                        osc.frequency.setValueAtTime(freq, now + idx * 0.05);
                        gain.gain.setValueAtTime(0.15, now + idx * 0.05);
                        gain.gain.exponentialRampToValueAtTime(0.001, now + idx * 0.05 + 0.6);
                        osc.connect(gain);
                        gain.connect(audioCtx.destination);
                        osc.start(now + idx * 0.05);
                        osc.stop(now + idx * 0.05 + 0.6);
                    });
                }
                else if (type === 'modal') {
                    const osc = audioCtx.createOscillator();
                    const gain = audioCtx.createGain();
                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(440, now);
                    osc.frequency.exponentialRampToValueAtTime(880, now + 0.4);
                    gain.gain.setValueAtTime(0.2, now);
                    gain.gain.exponentialRampToValueAtTime(0.01, now + 0.4);
                    osc.connect(gain);
                    gain.connect(audioCtx.destination);
                    osc.start(now);
                    osc.stop(now + 0.4);
                }
                else if (type === 'applause') {
                    for (let i = 0; i < 22; i++) {
                        const delay = Math.random() * 0.9;
                        const duration = 0.06 + Math.random() * 0.1;
                        const bufferSize = audioCtx.sampleRate * duration;
                        const buffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
                        const data = buffer.getChannelData(0);
                        for (let j = 0; j < bufferSize; j++) {
                            data[j] = (Math.random() * 2 - 1) * Math.exp(-j / (bufferSize * 0.5));
                        }
                        const noise = audioCtx.createBufferSource();
                        noise.buffer = buffer;
                        const filter = audioCtx.createBiquadFilter();
                        filter.type = 'bandpass';
                        filter.frequency.setValueAtTime(1100 + Math.random() * 900, now + delay);
                        const gain = audioCtx.createGain();
                        gain.gain.setValueAtTime(0.25, now + delay);
                        gain.gain.exponentialRampToValueAtTime(0.001, now + delay + duration);
                        noise.connect(filter);
                        filter.connect(gain);
                        gain.connect(audioCtx.destination);
                        noise.start(now + delay);
                    }
                }
                else if (type === 'boo') {
                    const osc1 = audioCtx.createOscillator();
                    const osc2 = audioCtx.createOscillator();
                    const gain = audioCtx.createGain();
                    
                    osc1.type = 'sawtooth';
                    osc2.type = 'sine';
                    
                    osc1.frequency.setValueAtTime(170, now);
                    osc1.frequency.exponentialRampToValueAtTime(85, now + 0.85);
                    osc2.frequency.setValueAtTime(175, now);
                    osc2.frequency.exponentialRampToValueAtTime(88, now + 0.85);
                    
                    gain.gain.setValueAtTime(0.25, now);
                    gain.gain.exponentialRampToValueAtTime(0.01, now + 0.85);
                    
                    osc1.connect(gain);
                    osc2.connect(gain);
                    gain.connect(audioCtx.destination);
                    
                    osc1.start(now);
                    osc2.start(now);
                    osc1.stop(now + 0.85);
                    osc2.stop(now + 0.85);
                }
            } catch (e) {
                console.log("Audio play error:", e);
            }
        }

        function toggleAudio() {
            audioEnabled = !audioEnabled;
            const icon = document.getElementById('soundIcon');
            if (audioEnabled) {
                icon.className = 'fa-solid fa-music text-sm text-amber-300 animate-pulse';
                startBGM();
            } else {
                icon.className = 'fa-solid fa-volume-xmark text-sm text-red-400';
                stopBGM();
            }
        }

        const handleFirstInteraction = () => {
            if (audioEnabled && !bgmActive) {
                startBGM();
            }
            document.removeEventListener('click', handleFirstInteraction);
            document.removeEventListener('keydown', handleFirstInteraction);
        };
        document.addEventListener('click', handleFirstInteraction);
        document.addEventListener('keydown', handleFirstInteraction);

        const canvas = document.getElementById('skyCanvas');
        const ctx = canvas.getContext('2d');
        let stars = [];
        let particles = [];

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
            initStars();
        }

        function initStars() {
            stars = [];
            const count = Math.floor((canvas.width * canvas.height) / 3000);
            for (let i = 0; i < count; i++) {
                stars.push({
                    x: Math.random() * canvas.width,
                    y: Math.random() * canvas.height,
                    radius: Math.random() * 1.5 + 0.5,
                    alpha: Math.random(),
                    twinkleSpeed: Math.random() * 0.02 + 0.005,
                    color: Math.random() > 0.8 ? '#fef08a' : (Math.random() > 0.5 ? '#a5b4fc' : '#ffffff')
                });
            }
        }

        function createSparkles(x, y) {
            for (let i = 0; i < 35; i++) {
                const angle = Math.random() * Math.PI * 2;
                const speed = Math.random() * 4 + 1;
                particles.push({
                    x: x,
                    y: y,
                    vx: Math.cos(angle) * speed,
                    vy: Math.sin(angle) * speed,
                    radius: Math.random() * 3 + 1,
                    alpha: 1,
                    decay: Math.random() * 0.02 + 0.015,
                    color: i % 2 === 0 ? '#fef08a' : '#818cf8'
                });
            }
        }

        function renderCanvas() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);

            stars.forEach(star => {
                star.alpha += star.twinkleSpeed;
                if (star.alpha > 1 || star.alpha < 0.2) star.twinkleSpeed = -star.twinkleSpeed;

                ctx.beginPath();
                ctx.arc(star.x, star.y, star.radius, 0, Math.PI * 2);
                ctx.fillStyle = star.color;
                ctx.globalAlpha = Math.max(0.1, Math.min(1, star.alpha));
                ctx.fill();
            });

            for (let i = particles.length - 1; i >= 0; i--) {
                const p = particles[i];
                p.x += p.vx;
                p.y += p.vy;
                p.alpha -= p.decay;

                if (p.alpha <= 0) {
                    particles.splice(i, 1);
                    continue;
                }

                ctx.beginPath();
                ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
                ctx.fillStyle = p.color;
                ctx.globalAlpha = p.alpha;
                ctx.fill();
            }

            ctx.globalAlpha = 1;
            requestAnimationFrame(renderCanvas);
        }

        window.addEventListener('resize', resizeCanvas);

        function initMoons() {
            const moonsGrid = document.getElementById('moonsGrid');
            moonsGrid.innerHTML = '';
            moons = [];

            for (let i = 0; i < 9; i++) {
                const moonData = {
                    id: i,
                    active: true,
                    title: moonQuestions[i].title,
                    prompt: moonQuestions[i].prompt
                };
                moons.push(moonData);

                const moonEl = document.createElement('div');
                moonEl.id = `moon-${i}`;
                moonEl.className = 'relative flex flex-col items-center cursor-pointer group transition-transform duration-300';
                moonEl.onclick = () => { if (!isShooting && moonData.active) shootAtSpecificMoon(i); };

                moonEl.innerHTML = `
                    <div id="moonOrb-${i}" class="moon-glow w-16 h-16 md:w-20 md:h-20 rounded-full bg-gradient-to-tr from-red-500 via-amber-400 to-amber-200 flex items-center justify-center border-2 border-amber-200/80 shadow-xl relative overflow-hidden">
                        <div class="absolute w-5 h-5 rounded-full bg-amber-300/40 top-2 fill-current left-2"></div>
                        <div class="absolute w-7 h-7 rounded-full bg-red-600/30 bottom-2 right-2"></div>
                        <div class="absolute w-4 h-4 rounded-full bg-amber-200/50 bottom-5 left-5"></div>
                        
                        <span class="font-cinzel text-sm font-extrabold text-slate-900 z-10 drop-shadow">${i + 1}</span>
                    </div>
                    <span class="mt-2 text-[10px] md:text-xs font-cinzel text-amber-200/90 font-bold group-hover:text-amber-300 transition-colors text-center">
                        ${moonQuestions[i].title.replace("Moon of ", "")}
                    </span>
                `;
                moonsGrid.appendChild(moonEl);
            }
            updateHUD();
        }

        function updateHUD() {
            const activeMoonsCount = moons.filter(m => m.active).length;
            document.getElementById('moonsRemainingText').innerText = `${activeMoonsCount} / 9`;
            document.getElementById('arrowCountHUD').innerText = `${arrowsRemaining} Arrow${arrowsRemaining !== 1 ? 's' : ''}`;

            const quiverGroup = document.getElementById('quiverArrowIcons');
            if (quiverGroup) {
                const lines = quiverGroup.querySelectorAll('line');
                lines.forEach((line, index) => {
                    if (index < arrowsRemaining) {
                        line.style.display = 'block';
                    } else {
                        line.style.display = 'none';
                    }
                });
            }

            const svgReadyArrow = document.getElementById('svgReadyArrow');
            if (svgReadyArrow) {
                svgReadyArrow.style.display = arrowsRemaining > 0 ? 'block' : 'none';
            }

            const shootBtn = document.getElementById('shootBtn');
            if (arrowsRemaining <= 0 || activeMoonsCount === 0) {
                shootBtn.classList.add('opacity-50', 'cursor-not-allowed');
            } else {
                shootBtn.classList.remove('opacity-50', 'cursor-not-allowed');
            }
        }

        function shootArrow() {
            if (isShooting || arrowsRemaining <= 0) return;

            const targetIndex = moons.findIndex(m => m.active);
            if (targetIndex === -1) return;

            shootAtSpecificMoon(targetIndex);
        }

        function shootAtSpecificMoon(targetIndex) {
            if (isShooting || arrowsRemaining <= 0 || !moons[targetIndex].active) return;

            isShooting = true;
            playSound('bow');

            const archerChar = document.getElementById('archerCharacter');
            const bowArc = document.getElementById('bowArc');
            const bowString = document.getElementById('bowString');
            const pullingArm = document.getElementById('pullingArm');

            bowArc.setAttribute('d', 'M152 35 Q205 100 162 165');
            bowString.setAttribute('d', 'M152 35 L138 102 L162 165');
            pullingArm.setAttribute('d', 'M118 120 L130 108 L138 102');

            setTimeout(() => {
                playSound('whoosh');
                bowArc.setAttribute('d', 'M152 42 Q195 100 162 158');
                bowString.setAttribute('d', 'M152 42 L152 102 L162 158');
                pullingArm.setAttribute('d', 'M118 120 L138 108 L152 102');

                arrowsRemaining--;
                updateHUD();

                const moonOrb = document.getElementById(`moonOrb-${targetIndex}`);
                const targetRect = moonOrb.getBoundingClientRect();
                const archerRect = archerChar.getBoundingClientRect();

                const startX = archerRect.left + archerRect.width / 2 + 20;
                const startY = archerRect.top + 50;
                const endX = targetRect.left + targetRect.width / 2;
                const endY = targetRect.top + targetRect.height / 2;

                const arrowEl = document.createElement('div');
                arrowEl.className = 'fixed pointer-events-none z-30 transition-all duration-300 ease-out';
                arrowEl.style.left = `${startX}px`;
                arrowEl.style.top = `${startY}px`;
                
                const deltaX = endX - startX;
                const deltaY = endY - startY;
                const angle = Math.atan2(deltaY, deltaX) * (180 / Math.PI);

                arrowEl.innerHTML = `
                    <div style="transform: rotate(${angle}deg); transform-origin: left center;" class="flex items-center">
                        <div class="w-12 h-1 bg-gradient-to-r from-amber-400 via-amber-200 to-red-500 rounded-full shadow-lg shadow-amber-400"></div>
                        <div class="w-0 h-0 border-t-4 border-t-transparent border-b-4 border-b-transparent border-l-8 border-l-blue-500"></div>
                    </div>
                `;
                document.body.appendChild(arrowEl);

                requestAnimationFrame(() => {
                    arrowEl.style.left = `${endX}px`;
                    arrowEl.style.top = `${endY}px`;
                });

                setTimeout(() => {
                    arrowEl.remove();
                    playSound('hit');
                    createSparkles(endX, endY);
                    triggerMoonFall(targetIndex);
                }, 300);

            }, 250);
        }

        function triggerMoonFall(index) {
            moons[index].active = false;
            activeFallingMoonIndex = index;

            const moonOrb = document.getElementById(`moonOrb-${index}`);
            moonOrb.classList.remove('moon-glow');
            moonOrb.classList.add('falling-moon-anim');

            setTimeout(() => {
                showQuestionBox(index);
            }, 600);
        }

        function showQuestionBox(index) {
            playSound('modal');

            document.getElementById('modalMoonTag').innerText = `Q${index + 1}`;
            document.getElementById('modalQuestionTitle').innerText = "After you answer this question, you can shoot another moon in the sky.";
            
            const promptEl = document.getElementById('modalQuestionPrompt');
            if (promptEl) {
                promptEl.innerText = moonQuestions[index].prompt;
            }

            const quizIll = document.getElementById('quizIllustration');
            const prefixLabel = document.getElementById('answerPrefixLabel');
            const suffixLabel = document.getElementById('answerSuffixLabel');
            const quizInput = document.getElementById('quizAnswerInput');
            const quizFeedback = document.getElementById('quizFeedback');

            const currentQ = moonQuestions[index];

            if (currentQ.hasQuiz) {
                if (quizIll) {
                    quizIll.style.display = 'flex';
                    if (index === 0) quizIll.innerHTML = q1IllustrationSVG;
                    else if (index === 1) quizIll.innerHTML = q2IllustrationSVG;
                    else if (index === 2) quizIll.innerHTML = q3IllustrationSVG;
                    else if (index === 3) quizIll.innerHTML = q4IllustrationSVG;
                    else if (index === 4) quizIll.innerHTML = q5IllustrationSVG;
                    else if (index === 5) quizIll.innerHTML = q6IllustrationSVG;
                    else if (index === 6) quizIll.innerHTML = q7IllustrationSVG;
                    else if (index === 7) quizIll.innerHTML = q8IllustrationSVG;
                    else quizIll.style.display = 'none';
                }
                if (prefixLabel) prefixLabel.innerText = currentQ.prefix || "Answer:";
                if (suffixLabel) suffixLabel.innerText = currentQ.suffix !== undefined ? currentQ.suffix : "";
            } else {
                if (quizIll) quizIll.style.display = 'none';
                if (prefixLabel) prefixLabel.innerText = currentQ.prefix || "Answer:";
                if (suffixLabel) suffixLabel.innerText = currentQ.suffix !== undefined ? currentQ.suffix : "";
            }

            quizInput.value = journalData[index] || "";
            quizFeedback.innerHTML = '';

            const modal = document.getElementById('questionModal');
            const modalContent = document.getElementById('modalContent');

            modal.classList.remove('pointer-events-none', 'opacity-0');
            modal.classList.add('opacity-100');
            modalContent.classList.remove('scale-90');
            modalContent.classList.add('scale-100');

            setTimeout(() => { 
                quizInput.focus();
            }, 300);
        }

        function handleQuizInput(event) {
            if (event.key === 'Enter') {
                checkQuizAnswer();
                return;
            }
            const val = document.getElementById('quizAnswerInput').value.trim().toLowerCase();
            const currentQ = moonQuestions[activeFallingMoonIndex];
            if (currentQ && currentQ.hasQuiz && currentQ.correctAnswer && currentQ.correctAnswer.includes(val)) {
                checkQuizAnswer();
            }
        }

        function checkQuizAnswer() {
            const inputEl = document.getElementById('quizAnswerInput');
            const feedbackEl = document.getElementById('quizFeedback');
            const val = inputEl.value.trim().toLowerCase();

            if (!val) {
                feedbackEl.innerHTML = `<span class="text-amber-400">Please enter an answer first.</span>`;
                return;
            }

            const currentQ = moonQuestions[activeFallingMoonIndex];

            if (currentQ && currentQ.hasQuiz && currentQ.correctAnswer) {
                const isCorrect = currentQ.correctAnswer.includes(val);
                if (isCorrect) {
                    feedbackEl.innerHTML = `<span class="text-emerald-400 flex items-center space-x-1.5"><i class="fa-solid fa-circle-check text-base"></i><span>Correct! Answer is "${val}"! 🎉</span></span>`;
                    playSound('applause');
                } else {
                    const expected = currentQ.correctAnswer[0];
                    feedbackEl.innerHTML = `<span class="text-rose-500 flex items-center space-x-1.5"><i class="fa-solid fa-circle-xmark text-base"></i><span>Incorrect (❌). Try typing "${expected}"!</span></span>`;
                    playSound('boo');
                }
            } else {
                feedbackEl.innerHTML = `<span class="text-emerald-400 flex items-center space-x-1.5"><i class="fa-solid fa-circle-check text-base"></i><span>Response saved! ✨</span></span>`;
                playSound('modal');
            }
        }

        function closeQuestionBox() {
            if (activeFallingMoonIndex !== null) {
                const text = document.getElementById('quizAnswerInput').value.trim();
                journalData[activeFallingMoonIndex] = text;
            }

            const modal = document.getElementById('questionModal');
            const modalContent = document.getElementById('modalContent');

            modal.classList.remove('opacity-100');
            modal.classList.add('opacity-0', 'pointer-events-none');
            modalContent.classList.remove('scale-100');
            modalContent.classList.add('scale-90');

            if (activeFallingMoonIndex !== null) {
                const moonOrb = document.getElementById(`moonOrb-${activeFallingMoonIndex}`);
                if (moonOrb) {
                    moonOrb.style.opacity = '0.15';
                    moonOrb.style.filter = 'grayscale(1)';
                    moonOrb.classList.remove('falling-moon-anim');
                }
            }

            isShooting = false;
            activeFallingMoonIndex = null;
            updateHUD();

            const activeMoonsLeft = moons.filter(m => m.active).length;
            if (activeMoonsLeft === 0) {
                setTimeout(showCompletionModal, 600);
            }
        }

        function openJournal() {
            playSound('modal');
            const container = document.getElementById('journalEntriesList');
            container.innerHTML = '';

            moons.forEach((m, idx) => {
                const isShot = !m.active;
                const text = journalData[idx];

                const card = document.createElement('div');
                card.className = `p-4 rounded-xl border ${isShot ? 'bg-slate-900/90 border-indigo-500/30' : 'bg-slate-950/40 border-slate-800 opacity-60'} transition-all`;
                
                card.innerHTML = `
                    <div class="flex justify-between items-center mb-2">
                        <div class="flex items-center space-x-2">
                            <span class="w-6 h-6 rounded-full ${isShot ? 'bg-amber-400 text-slate-950' : 'bg-slate-800 text-slate-400'} text-xs font-bold font-cinzel flex items-center justify-center">
                                ${idx + 1}
                            </span>
                            <span class="font-cinzel text-sm font-bold ${isShot ? 'text-amber-200' : 'text-slate-400'}">
                                ${m.title}
                            </span>
                        </div>
                        <span class="text-[10px] font-mono ${isShot ? 'text-emerald-400' : 'text-slate-500'}">
                            ${isShot ? 'Fallen Moon' : 'In Night Sky'}
                        </span>
                    </div>
                    <p class="text-xs text-indigo-200/70 italic mb-2">"${m.prompt}"</p>
                    <div class="p-3 rounded-lg bg-slate-950/80 border border-slate-800 text-xs text-slate-200 font-sans">
                        ${text ? text : (isShot ? '<span class="text-slate-500 italic">No words recorded for this moon.</span>' : '<span class="text-slate-600 italic">Shoot this moon to record your reflection.</span>')}
                    </div>
                `;
                container.appendChild(card);
            });

            document.getElementById('journalCount').innerText = `${moons.filter(m => !m.active).length} of 9 Moons Fallen`;

            const jModal = document.getElementById('journalModal');
            jModal.classList.remove('pointer-events-none', 'opacity-0');
            jModal.classList.add('opacity-100');
        }

        function closeJournal() {
            const jModal = document.getElementById('journalModal');
            jModal.classList.remove('opacity-100');
            jModal.classList.add('opacity-0', 'pointer-events-none');
        }

        function showCompletionModal() {
            playSound('hit');
            const cModal = document.getElementById('completionModal');
            cModal.classList.remove('pointer-events-none', 'opacity-0');
            cModal.classList.add('opacity-100');
        }

        function closeCompletionModal() {
            const cModal = document.getElementById('completionModal');
            cModal.classList.remove('opacity-100');
            cModal.classList.add('opacity-0', 'pointer-events-none');
        }

        function resetGame() {
            arrowsRemaining = 9;
            journalData = Array(9).fill("");
            isShooting = false;
            activeFallingMoonIndex = null;
            closeCompletionModal();
            closeJournal();
            initMoons();
        }

        window.onload = function () {
            resizeCanvas();
            renderCanvas();
            initMoons();
        };
    </script>
</body>
</html>
