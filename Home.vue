<template>
  <div id="home">

        <nav class="text-sm font-semibold mb-6" aria-label="Breadcrumb">
            <ol class="list-none p-0 inline-flex">
              <li class="flex items-center text-blue-500">
                <a href="#" class="text-gray-700">Dashboard</a>
                <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
              </li>
              <li class="flex items-center">
                <a href="#" class="text-gray-600">Home</a>
              </li>
            </ol>
          </nav>

          <!-- <div class="lg:flex justify-between items-center mb-6">
            <p class="text-2xl font-semibold mb-2 lg:mb-0">Vulnerability Report</p>
          </div> -->

      <div class="border border-rounded-xl border-gray-900 bg-gray-100 p-6 mb-4 flex items-center rounded-xl">
          <img src="@/assets/recycle.png" class="w-16 h-16 mr-4 rounded-full" />
              <div class="flex flex-col">
                <a href="/dashboard/home/report"> 
                  <p class="text-l text-gray-800 hover:text-blue-500">Product / YavAi247 / dataset-management-api</p>
                </a>
                  <p class="text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="flex items-center">
                      <span class="bg-red-600 rounded-full w-3 h-3 mr-2"></span>
                      <span class="text-gray-800 text-sm">Java</span>
                  </div>
              </div>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-auto">
              <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
              </svg><p class="ml-1">199</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M9.401 3.003c1.155-2 4.043-2 5.197 0l7.355 12.748c1.154 2-.29 4.5-2.599 4.5H4.645c-2.309 0-3.752-2.5-2.598-4.5L9.4 3.003zM12 8.25a.75.75 0 01.75.75v3.75a.75.75 0 01-1.5 0V9a.75.75 0 01.75-.75zm0 8.25a.75.75 0 100-1.5.75.75 0 000 1.5z" clip-rule="evenodd" />
              </svg><p class="ml-1">25</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M7.72 12.53a.75.75 0 010-1.06l7.5-7.5a.75.75 0 111.06 1.06L9.31 12l6.97 6.97a.75.75 0 11-1.06 1.06l-7.5-7.5z" clip-rule="evenodd" />
              </svg>
      </div>
      <div class="border border-rounded-xl border-gray-900 bg-gray-100 p-6 mb-4 flex items-center rounded-xl">
          <img src="@/assets/recycle.png" class="w-16 h-16 mr-4 rounded-full" />
              <div class="flex flex-col">
                <a href="/dashboard/home/report"> 
                  <p class="text-l text-gray-800 hover:text-blue-500">Product / YavAi247 / end2end-frontend</p>
                </a>
                  <p class="text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="flex items-center">
                      <span class="bg-yellow-400 rounded-full w-3 h-3 mr-2"></span>
                      <span class="text-gray-800 text-sm">Javascript</span>
                  </div>
              </div>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-auto">
              <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
              </svg><p class="ml-1">199</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M9.401 3.003c1.155-2 4.043-2 5.197 0l7.355 12.748c1.154 2-.29 4.5-2.599 4.5H4.645c-2.309 0-3.752-2.5-2.598-4.5L9.4 3.003zM12 8.25a.75.75 0 01.75.75v3.75a.75.75 0 01-1.5 0V9a.75.75 0 01.75-.75zm0 8.25a.75.75 0 100-1.5.75.75 0 000 1.5z" clip-rule="evenodd" />
              </svg><p class="ml-1">25</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M7.72 12.53a.75.75 0 010-1.06l7.5-7.5a.75.75 0 111.06 1.06L9.31 12l6.97 6.97a.75.75 0 11-1.06 1.06l-7.5-7.5z" clip-rule="evenodd" />
              </svg>
      </div>
      <div class="border border-rounded-xl border-gray-900 bg-gray-100 p-6 mb-4 flex items-center rounded-xl">
          <img src="@/assets/recycle.png" class="w-16 h-16 mr-4 rounded-full" />
              <div class="flex flex-col">
                <a href="/dashboard/home/report"> 
                  <p class="text-l text-gray-800 hover:text-blue-500">Product / YavAi247 / feature-store-api</p>
                </a>
                  <p class="text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="flex items-center">
                      <span class="bg-blue-400 rounded-full w-3 h-3 mr-2"></span>
                      <span class="text-gray-800 text-sm">Python</span>
                  </div>
              </div>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-auto">
              <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
              </svg><p class="ml-1">199</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M9.401 3.003c1.155-2 4.043-2 5.197 0l7.355 12.748c1.154 2-.29 4.5-2.599 4.5H4.645c-2.309 0-3.752-2.5-2.598-4.5L9.4 3.003zM12 8.25a.75.75 0 01.75.75v3.75a.75.75 0 01-1.5 0V9a.75.75 0 01.75-.75zm0 8.25a.75.75 0 100-1.5.75.75 0 000 1.5z" clip-rule="evenodd" />
              </svg><p class="ml-1">25</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M7.72 12.53a.75.75 0 010-1.06l7.5-7.5a.75.75 0 111.06 1.06L9.31 12l6.97 6.97a.75.75 0 11-1.06 1.06l-7.5-7.5z" clip-rule="evenodd" />
              </svg>
      </div>
      <div class="border border-rounded-xl border-gray-900 bg-gray-100 p-6 mb-4 flex items-center rounded-xl">
          <img src="@/assets/recycle.png" class="w-16 h-16 mr-4 rounded-full" />
              <div class="flex flex-col">
                <a href="/dashboard/home/report"> 
                  <p class="text-l text-gray-800 hover:text-blue-500">Product / YavAi247 / lorem-ipsum</p>
                </a>
                  <p class="text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="flex items-center">
                      <span class="bg-red-600 rounded-full w-3 h-3 mr-2"></span>
                      <span class="text-gray-800 text-sm">Java</span>
                  </div>
              </div>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-auto">
              <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
              </svg><p class="ml-1">199</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M9.401 3.003c1.155-2 4.043-2 5.197 0l7.355 12.748c1.154 2-.29 4.5-2.599 4.5H4.645c-2.309 0-3.752-2.5-2.598-4.5L9.4 3.003zM12 8.25a.75.75 0 01.75.75v3.75a.75.75 0 01-1.5 0V9a.75.75 0 01.75-.75zm0 8.25a.75.75 0 100-1.5.75.75 0 000 1.5z" clip-rule="evenodd" />
              </svg><p class="ml-1">25</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M7.72 12.53a.75.75 0 010-1.06l7.5-7.5a.75.75 0 111.06 1.06L9.31 12l6.97 6.97a.75.75 0 11-1.06 1.06l-7.5-7.5z" clip-rule="evenodd" />
              </svg>
      </div>
      <div class="border border-rounded-xl border-gray-900 bg-gray-100 p-6 mb-4 flex items-center rounded-xl">
          <img src="@/assets/recycle.png" class="w-16 h-16 mr-4 rounded-full" />
              <div class="flex flex-col">
                <a href="/dashboard/home/report"> 
                  <p class="text-l text-gray-800 hover:text-blue-500">Product / YavAi247 / lorem-ipsum</p>
                </a>
                  <p class="text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="flex items-center">
                      <span class="bg-red-600 rounded-full w-3 h-3 mr-2"></span>
                      <span class="text-gray-800 text-sm">Java</span>
                  </div>
              </div>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-auto">
              <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
              </svg><p class="ml-1">199</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M9.401 3.003c1.155-2 4.043-2 5.197 0l7.355 12.748c1.154 2-.29 4.5-2.599 4.5H4.645c-2.309 0-3.752-2.5-2.598-4.5L9.4 3.003zM12 8.25a.75.75 0 01.75.75v3.75a.75.75 0 01-1.5 0V9a.75.75 0 01.75-.75zm0 8.25a.75.75 0 100-1.5.75.75 0 000 1.5z" clip-rule="evenodd" />
              </svg><p class="ml-1">25</p>

              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="30" height="30" class="w-9 h-9 ml-6">
              <path fill-rule="evenodd" d="M7.72 12.53a.75.75 0 010-1.06l7.5-7.5a.75.75 0 111.06 1.06L9.31 12l6.97 6.97a.75.75 0 11-1.06 1.06l-7.5-7.5z" clip-rule="evenodd" />
              </svg>
      </div>
  </div>
</template>

<script>


export default {
  name: 'DashboardHome',
  data() {
      return {
      }
  }
}

</script>