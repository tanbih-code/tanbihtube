<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   TanbihTube - Video Sharing Platform
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Roboto', sans-serif;
    }
  </style>
 </head>
 <body class="bg-white text-gray-900">
  <!-- Header -->
  <header class="fixed top-0 left-0 right-0 bg-white shadow z-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between h-16">
    <div class="flex items-center space-x-4">
     <button class="text-gray-700 text-2xl md:hidden focus:outline-none" id="menu-button">
      <i class="fas fa-bars">
      </i>
     </button>
     <a class="flex items-center space-x-1" href="#">
      <img alt="TanbihTube logo red square with white YT letters" class="h-8 w-8" height="32" src="https://storage.googleapis.com/a1aa/image/22b909cf-b6a8-4043-e325-eb3ed47643b8.jpg" width="32"/>
      <span class="font-bold text-xl text-red-600 select-none">
       TanbihTube
      </span>
     </a>
    </div>
    <form class="hidden sm:flex flex-grow max-w-xl mx-4">
     <input aria-label="Search videos" class="flex-grow border border-gray-300 rounded-l-full px-4 py-2 focus:outline-none focus:ring-2 focus:ring-red-600" placeholder="Search" type="text"/>
     <button aria-label="Search" class="bg-red-600 hover:bg-red-700 px-4 rounded-r-full text-white focus:outline-none focus:ring-2 focus:ring-red-600" type="submit">
      <i class="fas fa-search">
      </i>
     </button>
    </form>
    <div class="flex items-center space-x-4">
     <button aria-label="Create video" class="hidden md:inline-flex items-center justify-center w-10 h-10 rounded-full hover:bg-gray-200 focus:outline-none" title="Create video">
      <i class="fas fa-video text-gray-700 text-lg">
      </i>
     </button>
     <button aria-label="Apps" class="hidden md:inline-flex items-center justify-center w-10 h-10 rounded-full hover:bg-gray-200 focus:outline-none" title="Apps">
      <i class="fas fa-th text-gray-700 text-lg">
      </i>
     </button>
     <button aria-label="Notifications" class="hidden md:inline-flex items-center justify-center w-10 h-10 rounded-full hover:bg-gray-200 focus:outline-none" title="Notifications">
      <i class="fas fa-bell text-gray-700 text-lg">
      </i>
     </button>
     <button aria-label="User profile" class="w-10 h-10 rounded-full overflow-hidden focus:outline-none" title="User profile">
      <img alt="User profile avatar blue circle with white letter U" class="w-full h-full object-cover" height="40" src="https://storage.googleapis.com/a1aa/image/077fe23f-0833-4738-9fde-33a9eb8b81f5.jpg" width="40"/>
     </button>
    </div>
   </div>
   <!-- Mobile search bar -->
   <form class="sm:hidden px-4 pb-2 pt-1 flex items-center border-b border-gray-200">
    <input aria-label="Search videos" class="flex-grow border border-gray-300 rounded-l-full px-4 py-2 focus:outline-none focus:ring-2 focus:ring-red-600" placeholder="Search" type="text"/>
    <button aria-label="Search" class="bg-red-600 hover:bg-red-700 px-4 rounded-r-full text-white focus:outline-none focus:ring-2 focus:ring-red-600" type="submit">
     <i class="fas fa-search">
     </i>
    </button>
   </form>
  </header>
  <!-- Sidebar and main content wrapper -->
  <div class="pt-20 flex min-h-screen bg-gray-50">
   <!-- Sidebar -->
   <nav aria-label="Primary navigation" class="fixed top-16 left-0 bottom-0 w-64 bg-white border-r border-gray-200 overflow-y-auto transform -translate-x-full md:translate-x-0 transition-transform duration-300 ease-in-out z-40" id="sidebar">
    <ul class="py-4 space-y-1">
     <li>
      <a aria-current="page" class="flex items-center px-6 py-3 text-gray-900 font-semibold bg-gray-100 hover:bg-gray-200" href="#">
       <i class="fas fa-home mr-4 text-lg">
       </i>
       Home
      </a>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 text-gray-700 hover:bg-gray-100" href="#">
       <i class="fas fa-fire mr-4 text-lg">
       </i>
       Trending
      </a>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 text-gray-700 hover:bg-gray-100" href="#">
       <i class="fas fa-layer-group mr-4 text-lg">
       </i>
       Subscriptions
      </a>
     </li>
     <li>
      <hr class="my-2 border-gray-300"/>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 text-gray-700 hover:bg-gray-100" href="#">
       <i class="fas fa-bookmark mr-4 text-lg">
       </i>
       Library
      </a>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 text-gray-700 hover:bg-gray-100" href="#">
       <i class="fas fa-history mr-4 text-lg">
       </i>
       History
      </a>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 text-gray-700 hover:bg-gray-100" href="#">
       <i class="fas fa-clock mr-4 text-lg">
       </i>
       Watch Later
      </a>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 text-gray-700 hover:bg-gray-100" href="#">
       <i class="fas fa-thumbs-up mr-4 text-lg">
       </i>
       Liked Videos
      </a>
     </li>
     <li>
      <hr class="my-2 border-gray-300"/>
     </li>
     <li class="px-6 py-3 text-gray-600 uppercase text-xs tracking-wider font-semibold">
      Subscriptions
     </li>
     <li>
      <a class="flex items-center px-6 py-3 hover:bg-gray-100" href="#">
       <img alt="Channel avatar red circle with white letter A" class="w-8 h-8 rounded-full mr-3 object-cover" height="32" src="https://storage.googleapis.com/a1aa/image/6e80d6ad-10e6-495b-ce59-c662c1fcb5fe.jpg" width="32"/>
       <span class="text-gray-800">
        Awesome Channel
       </span>
      </a>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 hover:bg-gray-100" href="#">
       <img alt="Channel avatar green circle with white letter B" class="w-8 h-8 rounded-full mr-3 object-cover" height="32" src="https://storage.googleapis.com/a1aa/image/12ef017f-c067-47e0-1a23-0744647a4d8a.jpg" width="32"/>
       <span class="text-gray-800">
        Best Vlogs
       </span>
      </a>
     </li>
     <li>
      <a class="flex items-center px-6 py-3 hover:bg-gray-100" href="#">
       <img alt="Channel avatar blue circle with white letter C" class="w-8 h-8 rounded-full mr-3 object-cover" height="32" src="https://storage.googleapis.com/a1aa/image/d3724e56-7d60-46cf-5370-065849d81c77.jpg" width="32"/>
       <span class="text-gray-800">
        Creative Studio
       </span>
      </a>
     </li>
    </ul>
   </nav>
   <!-- Main content -->
   <main class="flex-grow ml-0 md:ml-64 p-4 max-w-7xl mx-auto">
    <!-- Featured video banner -->
    <section class="mb-8">
     <div class="relative rounded-lg overflow-hidden shadow-lg">
      <img alt="Featured video thumbnail showing a scenic mountain landscape with a large red play button overlay in the center" class="w-full h-auto object-cover" height="720" src="https://storage.googleapis.com/a1aa/image/d9ce4612-7aac-46bd-a4e5-d23603843dd0.jpg" width="1280"/>
      <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/80 to-transparent p-4 text-white">
       <h2 class="text-2xl font-bold mb-1">
        Explore the Beauty of Nature
       </h2>
       <p class="text-sm">
        MiniTube Originals • 1.2M views • 3 days ago
       </p>
      </div>
     </div>
    </section>
    <!-- Video grid -->
    <section>
     <h3 class="text-xl font-semibold mb-4">
      Recommended
     </h3>
     <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing a vibrant city skyline at sunset with orange and purple hues" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/b57f7cd7-54d2-4e8e-567a-99f7cc218ae5.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         12:34
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar orange circle with white letters V1" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/5682c4b0-467d-4ae1-a98f-29da94103220.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Exploring the City Lights: A Night Adventure
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          Urban Explorer • 1.1M views • 1 week ago
         </p>
        </div>
       </div>
      </article>
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing a mountain hiking trail with lush green trees and a clear blue sky" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/f0a90c4f-7df3-4ae1-bc7a-c2e9e8e7bf3b.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         8:20
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar blue circle with white letters V2" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/777ab251-c057-4c14-8124-8649e5215d50.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Hiking the Majestic Mountains: Tips &amp; Tricks
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          Nature Walks • 850K views • 4 days ago
         </p>
        </div>
       </div>
      </article>
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing a close-up of a chef preparing a colorful dish in a modern kitchen" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/ab3609f6-3a13-4caf-51c8-1fa11af3fa57.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         15:45
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar green circle with white letters V3" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/c732ef30-9492-4a38-6c58-424c4bbced6f.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Mastering the Art of Italian Cooking at Home
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          Chef's Table • 2.3M views • 2 weeks ago
         </p>
        </div>
       </div>
      </article>
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing a vibrant music concert with colorful stage lights and a cheering crowd" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/ca58ad29-ac7c-410f-b339-7a15f51d36d1.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         5:12
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar pink circle with white letters V4" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/6d31e73f-b70e-4328-932c-4e442617bd9d.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Live from the Festival: Best Moments
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          Music Mania • 3.7M views • 1 day ago
         </p>
        </div>
       </div>
      </article>
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing a modern smartphone on a desk with tech gadgets around" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/f55cb7da-3f54-4907-1062-f82b2c45412d.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         10:05
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar orange circle with white letters V5" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/0bc360cd-1191-4e7b-d3f9-cb43cb092c22.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Latest Smartphone Review: Features &amp; Performance
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          Tech Guru • 1.9M views • 3 days ago
         </p>
        </div>
       </div>
      </article>
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing an intense gaming scene with a player holding a controller and colorful game graphics" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/84497fa2-db2f-4584-6659-5775a7f83a33.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         22:18
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar purple circle with white letters V6" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/cbc81bdb-890e-4d8b-74ed-87a3c360c477.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Epic Gameplay Walkthrough: Level 10 Boss Fight
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          GameZone • 4.5M views • 5 days ago
         </p>
        </div>
       </div>
      </article>
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing a fitness instructor demonstrating a workout routine in a gym" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/f474e3fd-6fdc-4bc1-b458-528531c877a5.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         18:30
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar teal circle with white letters V7" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/2be6711f-4333-41db-0124-4a9966ea6e75.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Full Body Workout for Beginners at Home
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          FitLife • 1.3M views • 1 week ago
         </p>
        </div>
       </div>
      </article>
      <article class="group cursor-pointer">
       <div class="relative rounded-lg overflow-hidden shadow-md">
        <img alt="Video thumbnail showing a tropical beach with turquoise water and palm trees under a sunny sky" class="w-full h-auto object-cover" height="180" src="https://storage.googleapis.com/a1aa/image/b050b0d4-9a00-42ed-8947-4692662591c1.jpg" width="320"/>
        <span class="absolute bottom-2 right-2 bg-black bg-opacity-75 text-white text-xs px-1.5 py-0.5 rounded">
         9:45
        </span>
       </div>
       <div class="mt-2 flex items-start space-x-3">
        <img alt="Channel avatar tomato red circle with white letters V8" class="w-10 h-10 rounded-full object-cover flex-shrink-0" height="40" src="https://storage.googleapis.com/a1aa/image/c84b8c7f-7f32-4d6d-0b8e-73664129f40d.jpg" width="40"/>
        <div class="flex-1">
         <h4 class="text-sm font-semibold text-gray-900 group-hover:text-red-600 line-clamp-2">
          Top 10 Beaches to Visit This Summer
         </h4>
         <p class="text-xs text-gray-600 mt-1">
          Travel Guide • 2.1M views • 2 weeks ago
         </p>
        </div>
       </div>
      </article>
     </div>
    </section>
   </main>
  </div>
  <script>
   const menuButton = document.getElementById('menu-button');
    const sidebar = document.getElementById('sidebar');

    menuButton.addEventListener('click', () => {
      sidebar.classList.toggle('-translate-x-full');
    });

    // Close sidebar on window resize if desktop
    window.addEventListener('resize', () => {
      if (window.innerWidth >= 768) {
        sidebar.classList.remove('-translate-x-full');
      } else {
        sidebar.classList.add('-translate-x-full');
      }
    });
  </script>
 </body>
</html>
