<template>
  <div class="text-sm text-gray-900">
    <nav class="bg-black text-white px-4 py-3 flex items-center justify-between">
    <div class="flex items-center space-x-4">
      <a href="#" class="text-white hover:text-gray-400">
        <svg aria-hidden="true" viewBox="0 0 16 16"  data-view-component="true" class="h-8 w-8 fill-current">
    <path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path>
    </svg>
      </a>
      <div class="relative">
        <input type="text" class="rounded bg-gray-700 placeholder-white w-72 px-3 py-1" placeholder="Search or jump to....">
        <div class="absolute top-0 right-0 flex items-center h-full">
          <div class="border border-gray-600 rounded text.sm text-gray-400 px-2 mr-2 ">/</div>
        </div>
      </div>
      <ul class="flex items-center font-semibold space-x-4">
        <li><a href="#" class="hover:text-grey-400">Pull Request</a></li>
        <li><a href="#" class="hover:text-grey-400">Issues</a></li>
        <li><a href="#" class="hover:text-grey-400">Marketplace</a></li>
        <li><a href="#" class="hover:text-grey-400">Explore</a></li>
      </ul>
    </div>
    <div class="flex items-center space-x-4 text-white">
      <a href="#" class="relative hover:text-gray-400">
        <svg aria-hidden="true"  viewBox="0 0 16 16"  data-view-component="true" class="fill-current w-5 y-5">
    <path d="M8 16a2 2 0 001.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 008 16z"></path><path fill-rule="evenodd" d="M8 1.5A3.5 3.5 0 004.5 5v2.947c0 .346-.102.683-.294.97l-1.703 2.556a.018.018 0 00-.003.01l.001.006c0 .002.002.004.004.006a.017.017 0 00.006.004l.007.001h10.964l.007-.001a.016.016 0 00.006-.004.016.016 0 00.004-.006l.001-.007a.017.017 0 00-.003-.01l-1.703-2.554a1.75 1.75 0 01-.294-.97V5A3.5 3.5 0 008 1.5zM3 5a5 5 0 0110 0v2.947c0 .05.015.098.042.139l1.703 2.555A1.518 1.518 0 0113.482 13H2.518a1.518 1.518 0 01-1.263-2.36l1.703-2.554A.25.25 0 003 7.947V5z"></path>
    <div class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0"></div>
</svg>
      </a>
      <a href="#" class="flex items-center hover:text-gray-400">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
      <path stroke-linecap="round" stroke-linejoin="round" d="M12 4v16m8-8H4" /> </svg>
      <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 ml-1" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
        </svg>
      
      </a>
      <a href="#" class="relative flex items-center hover:text-gray-400">
        <img src="https://avatars.githubusercontent.com/u/88014180?s=40&amp;v=4" alt="@KyTechHosting" data-view-component="true" class="rounded-full w-6 h-6">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 ml-1" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
        </svg>
      </a>
      
       </div>
    </nav>

    <div class="repo-stats flex items-center justify-between p-6  text-gray-700 font-semibold">
      <div class="flex items-center space-x-1">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M8 11V7a4 4 0 118 0m-4 8v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2z" />
      </svg>
        <p class="text-blue-600 text-xl">Tailwind</p>
        <span>/</span>
        <p class="text-blue-600 text-xl">Tailwind</p>
        <div class="flex items-center rounded-2xl text-sm border border-gray-400 outline-1 w-18 h-6 py-1 px-1 justify-center">Private</div>
      </div>
      <div class="flex items-center space-x-2">
        <div class="flex items-center border text-gray-800 border-gray-300 rounded-md h-7 w-32 hover:text-gray-500">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
          <path stroke-linecap="round" stroke-linejoin="round" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z" />
          </svg>
          <span class="flex items-center ml-1">Unwatch</span>
          <span class="flex items-center ml-1 rounded-full h-4 w-4 bg-gray-300 justify-center">1</span>
          <span class="flex items-center mr-1"><svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 ml-1" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
        </svg></span>
        </div>
        <div class="flex items-center border border-gray-300 rounded-md h-7 w-28 text-gray-500">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
          </svg>
          <span class="flex items-center ml-1">Fork</span>
          <span class="flex items-center ml-1 rounded-full h-4 w-4 bg-gray-300 justify-center">1</span>
          <span class="flex items-center mr-1"><svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 ml-1" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
        </svg></span>
        </div>
        <div class="flex items-center border border-gray-300 rounded-md h-7 w-28 text-gray-800 hover:text-gray-300">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z" />
          </svg>
          <span class="flex items-center ml-1">Fork</span>
          <span class="flex items-center ml-1 rounded-full h-4 w-4 bg-gray-300 justify-center">1</span>
          <span class="flex items-center mr-1"><svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 ml-1" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
        </svg></span>
        </div>
      </div>
    
      </div>
    </div>
</template>
