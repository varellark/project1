<template>
    <div id="id">
        
        <nav class="text-sm font-semibold mb-6" aria-label="Breadcrumb">
              <ol class="list-none p-0 inline-flex">
                <li class="flex items-center text-blue-500">
                  <a href="/dashboard/home" class="text-gray-700">Dashboard</a>
                  <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
                </li>
                <li class="flex items-center">
                  <a href="/dashboard/home" class="text-gray-600">Home</a>
                  <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
                </li>
                <li class="flex items-center">
                  <a href="/dashboard/home/report" class="text-gray-600">Vulnerability Report</a>
                  <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
                </li>
                <li class="flex items-center">
                  <a href="#" class="text-gray-600">Id</a>
                </li>
              </ol>
        </nav>

  <div class="flex mb-4">
      <p class="font-bold text-4xl">CVE-2017-18269 in glibc</p>
  </div>  
  <div class="flex mb-4">
    <p class="font-bold text-2xl">Description</p>
  </div>
  <div class="flex mb-8">
    <p class="font-thin text-1xl">SSE2-optimized memmove implementation problem</p>
  </div>
    <div class="flex mb-4">
        <ul class=" list-outside">
          <li>
            <span class="font-bold">Severity :</span>
            <span class="font-thin"> Critical</span>
          </li>
        </ul>
    </div>
    <div class="flex mb-4">
        <ul class=" list-outside">
          <li>
            <span class="font-bold">Report Type </span>
            <span class="font-thin"> container_scanning</span>
          </li>
        </ul>
    </div>
    <div class="flex mb-4">
        <ul class=" list-outside">
          <li>
            <span class="font-bold">Scanner :</span>
            <span class="font-thin"> clear</span>
          </li>
        </ul>
    </div>
    <div class="flex mb-4">
        <ul class=" list-outside">
          <li>
            <span class="font-bold">image :</span>
            <span class="font-thin"> reg.botram.labs247.id/envtest/container-scanning--test/master:567aeddesaddsaidaziadef
</span>
          </li>
        </ul>
    </div>
    <div class="flex mb-4">
        <ul class=" list-outside">
          <li>
            <span class="font-bold">Namespace :</span>
            <span class="font-thin"> debian/9</span>
          </li>
        </ul>
    </div>

    <div class="flex mt-8">
    <p class="font-bold text-2xl">Links</p>
  </div>
  <div class="flex mt-3">
        <ul class=" list-outside">
          <li class="font-thin">https://security-tracker.debian.org/tracker/CVE-2017-18269</li>
        </ul>
    </div>

    <div class="flex mt-3">
    <p class="font-bold text-2xl">Identifier</p>
  </div>
  <div class="flex mt-3">
        <ul class=" list-outside">
          <li class="font-thin">CVE-2017-18269</li>
        </ul>
    </div>

    <div class="flex mt-3">
    <p class="font-bold text-2xl">Solution</p>
  </div>
  <div class="flex mt-3">
        <ul class=" list-outside">
          <li class="font-thin">Upgrade glibc from 2.24-11+deb9u3 to 2.24-11-deb9ud</li>
        </ul>
    </div> 
  
    </div>
  </template>
  
  <script>
  
  
  export default {
    name: 'DashboardId',
    data() {
        return {
        }
    }
  }
  
  </script>