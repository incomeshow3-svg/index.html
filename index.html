<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VIEW1ON – Complete Video Sharing Platform</title>
  <script src="https://tailwindcss.com"></script>
  <link href="https://cloudflare.com" rel="stylesheet">
  <style>
    body { background-color: #0f0f0f; color: #ffffff; font-family: 'Segoe UI', sans-serif; }
    .no-scrollbar::-webkit-scrollbar { display: none; }
    .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
  </style>
</head>
<body class="pb-20">

  <!-- TOP HEADER -->
  <header class="sticky top-0 z-40 bg-[#0f0f0f]/95 backdrop-blur border-b border-gray-800 px-4 py-3 flex items-center justify-between">
    <div class="flex items-center gap-2">
      <div class="w-8 h-8 rounded-lg bg-gradient-to-tr from-red-600 to-rose-500 flex items-center justify-center font-bold text-white shadow">
        <i class="fa-solid fa-play text-xs"></i>
      </div>
      <span class="text-xl font-extrabold tracking-wide">VIEW<span class="text-red-500">1</span>ON</span>
    </div>

    <div class="hidden md:flex items-center bg-[#1e1e1e] rounded-full px-4 py-1.5 w-1/3 border border-gray-700">
      <input id="searchInput" type="text" placeholder="Search videos, shorts, creators..." class="bg-transparent w-full text-sm focus:outline-none text-white" onkeyup="window.filterVideos()" />
      <i class="fa-solid fa-magnifying-glass text-gray-400"></i>
    </div>

    <div class="flex items-center gap-3">
      <button onclick="window.openModal('supportModal')" class="bg-blue-600/20 hover:bg-blue-600/40 text-blue-400 border border-blue-500/40 px-3 py-1.5 rounded-full text-xs font-semibold flex items-center gap-1.5 transition">
        <i class="fa-solid fa-headset"></i> Support
      </button>
      <button onclick="alert('All notifications are up to date')" class="relative p-2 text-gray-300 hover:text-white">
        <i class="fa-regular fa-bell text-lg"></i>
        <span class="absolute top-1.5 right-1.5 w-2 h-2 bg-red-500 rounded-full"></span>
      </button>
      <button onclick="window.switchTab('account')" id="headerAvatar" class="w-8 h-8 rounded-full bg-red-600 font-bold text-xs flex items-center justify-center">
        U1
      </button>
    </div>
  </header>

  <!-- MOBILE SEARCH BAR -->
  <div class="md:hidden px-4 pt-3">
    <div class="flex items-center bg-[#1e1e1e] rounded-full px-4 py-2 border border-gray-800">
      <input id="mobileSearch" type="text" placeholder="Search VIEW1ON..." class="bg-transparent w-full text-sm focus:outline-none text-white" onkeyup="window.filterVideos()" />
      <i class="fa-solid fa-magnifying-glass text-gray-400 text-sm"></i>
    </div>
  </div>

  <!-- MAIN CONTENT -->
  <main class="max-w-6xl mx-auto px-4 pt-4">

    <!-- 1. HOME TAB -->
    <section id="tab-home" class="tab-section space-y-6">
      <div class="flex gap-2 overflow-x-auto no-scrollbar pb-1">
        <button onclick="window.setCategory('All')" class="bg-white text-black px-4 py-1.5 rounded-full text-xs font-semibold whitespace-nowrap">All</button>
        <button onclick="window.setCategory('Tech')" class="bg-[#222] text-gray-300 px-4 py-1.5 rounded-full text-xs font-semibold whitespace-nowrap">Tech</button>
        <button onclick="window.setCategory('Music')" class="bg-[#222] text-gray-300 px-4 py-1.5 rounded-full text-xs font-semibold whitespace-nowrap">Music</button>
        <button onclick="window.setCategory('Gaming')" class="bg-[#222] text-gray-300 px-4 py-1.5 rounded-full text-xs font-semibold whitespace-nowrap">Gaming</button>
        <button onclick="window.setCategory('Travel')" class="bg-[#222] text-gray-300 px-4 py-1.5 rounded-full text-xs font-semibold whitespace-nowrap">Travel</button>
      </div>

      <div>
        <div class="flex items-center gap-2 mb-3">
          <i class="fa-solid fa-bolt text-red-500"></i>
          <h2 class="font-bold text-base">VIEW1ON Shorts</h2>
        </div>
        <div id="shortsRow" class="grid grid-cols-2 sm:grid-cols-4 gap-3"></div>
      </div>

      <div>
        <h2 class="font-bold text-base mb-3">Recommended Videos</h2>
        <div id="videoGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5"></div>
      </div>
    </section>

    <!-- 2. SHORTS TAB -->
    <section id="tab-shorts" class="tab-section hidden">
      <div id="shortsPlayerContainer" class="max-w-sm mx-auto bg-[#181818] rounded-2xl overflow-hidden border border-gray-800 shadow-xl">
        <div class="p-8 text-center text-gray-400 text-sm">Select any Short from Home or upload a video ≤ 60 seconds.</div>
      </div>
    </section>

    <!-- 3. UPLOAD TAB (CLOUDINARY + AUTO DURATION) -->
    <section id="tab-upload" class="tab-section hidden max-w-xl mx-auto bg-[#181818] p-5 rounded-2xl border border-gray-800 space-y-4">
      <h2 class="text-lg font-bold flex items-center gap-2"><i class="fa-solid fa-cloud-arrow-up text-red-500"></i> Upload to VIEW1ON</h2>
      
      <div class="grid grid-cols-2 gap-3">
        <label class="cursor-pointer bg-[#252525] hover:bg-[#2f2f2f] border border-dashed border-gray-600 rounded-xl p-4 text-center">
          <i class="fa-solid fa-camera text-2xl text-red-400 mb-1"></i>
          <div class="text-xs font-semibold">Open Camera</div>
          <input type="file" accept="video/*" capture="environment" class="hidden" onchange="window.handleVideoSelect(event)" />
        </label>
        <label class="cursor-pointer bg-[#252525] hover:bg-[#2f2f2f] border border-dashed border-gray-600 rounded-xl p-4 text-center">
          <i class="fa-solid fa-photo-film text-2xl text-blue-400 mb-1"></i>
          <div class="text-xs font-semibold">Select Video</div>
          <input type="file" accept="video/*" class="hidden" onchange="window.handleVideoSelect(event)" />
        </label>
      </div>

      <div id="videoPreviewBox" class="hidden space-y-3">
        <video id="previewPlayer" controls class="w-full rounded-xl bg-black max-h-64"></video>
        <div class="flex items-center justify-between bg-[#222] px-3 py-2 rounded-lg text-xs">
          <span>Actual Duration: <strong id="detectedDuration" class="text-green-400">0s</strong></span>
          <span id="detectedTypeBadge" class="bg-red-600 px-2 py-0.5 rounded font-bold">VIDEO</span>
        </div>
      </div>

      <input id="upTitle" type="text" placeholder="Video Title *" class="w-full bg-[#222] border border-gray-700 rounded-lg px-3 py-2 text-sm" />
      <textarea id="upDesc" rows="2" placeholder="Description & #hashtags..." class="w-full bg-[#222] border border-gray-700 rounded-lg px-3 py-2 text-sm"></textarea>
      <div class="grid grid-cols-2 gap-3">
        <select id="upCat" class="bg-[#222] border border-gray-700 rounded-lg px-3 py-2 text-sm">
          <option value="Tech">Tech</option>
          <option value="Music">Music</option>
          <option value="Gaming">Gaming</option>
          <option value="Travel">Travel</option>
        </select>
        <select id="upVis" class="bg-[#222] border border-gray-700 rounded-lg px-3 py-2 text-sm">
          <option value="Public">Public</option>
          <option value="Private">Private</option>
        </select>
      </div>

      <div id="uploadProgressWrap" class="hidden space-y-1">
        <div class="w-full bg-gray-800 rounded-full h-2">
          <div id="uploadProgressBar" class="bg-red-600 h-2 rounded-full transition-all" style="width: 0%"></div>
        </div>
        <p id="uploadStatusText" class="text-xs text-gray-400 text-right">0%</p>
      </div>

      <button id="publishBtn" onclick="window.publishVideo()" class="w-full bg-red-600 hover:bg-red-700 py-2.5 rounded-xl font-bold text-sm transition">
        Upload & Publish
      </button>
    </section>

    <!-- 4. REAL-TIME FIREBASE CHAT TAB -->
    <section id="tab-chat" class="tab-section hidden max-w-3xl mx-auto bg-[#181818] rounded-2xl border border-gray-800 overflow-hidden">
      <div class="p-4 border-b border-gray-800 flex justify-between items-center">
        <div>
          <h2 class="font-bold text-base">Chat Inbox (<span id="chatOwnerLabel">Loading...</span>)</h2>
          <p class="text-[11px] text-gray-400">UID-isolated real-time messaging</p>
        </div>
        <span class="text-xs text-green-400 flex items-center gap-1"><span class="w-2 h-2 bg-green-400 rounded-full"></span> Connected</span>
      </div>
      <div id="chatMessages" class="p-4 h-72 overflow-y-auto space-y-3 bg-[#121212]"></div>
      <div class="p-3 bg-[#181818] border-t border-gray-800 flex gap-2">
        <input id="chatInput" type="text" placeholder="Type a message..." class="flex-1 bg-[#242424] rounded-full px-4 py-2 text-sm focus:outline-none" onkeypress="if(event.key==='Enter') window.sendMessage()" />
        <button onclick="window.sendMessage()" class="bg-red-600 px-4 py-2 rounded-full text-sm font-bold"><i class="fa-solid fa-paper-plane"></i></button>
      </div>
    </section>

    <!-- 5. PORTAL / MULTI-ACCOUNT MANAGEMENT TAB -->
    <section id="tab-account" class="tab-section hidden max-w-xl mx-auto space-y-4">
      <div class="bg-[#181818] p-5 rounded-2xl border border-gray-800 flex items-center gap-4">
        <div id="accBigAvatar" class="w-16 h-16 rounded-full bg-red-600 flex items-center justify-center text-xl font-bold">U1</div>
        <div class="flex-1">
          <h2 id="accName" class="text-lg font-bold">Guest User</h2>
          <p id="accHandle" class="text-xs text-gray-400">Sign in to sync across devices</p>
          <span id="accUidBadge" class="inline-block mt-1 bg-green-500/20 text-green-400 text-[10px] px-2 py-0.5 rounded font-semibold">Active Session</span>
        </div>
      </div>

      <!-- Add Another Account Form -->
      <div class="bg-[#181818] p-5 rounded-2xl border border-gray-800 space-y-3">
