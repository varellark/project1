<template>
    <div id="report">

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
                </li>
              </ol>
            </nav>

            <div class="lg:flex justify-between items-center mb-6">
            <p class="text-2xl font-semibold mb-2 lg:mb-0">Vulnerability Report</p>
            </div>

            <div class="flex flex-wrap items-center justify-center -mx-3 mb-8">
               
                <div class="flex flex-col border border-black bg-white rounded-lg h-40 w-40 m-2">
                    <div class="flex items-center justify-center bg-blue-400 h-12 w-38 rounded-tl-lg rounded-tr-lg">
                        <p class="font-semibold text-l">Critical</p>
                    </div>
                    <div class="flex items-center justify-center">
                        <p class="font-semibold text-5xl mt-4">9</p>
                    </div>
                </div>

                <div class="flex flex-col border border-black bg-white rounded-lg h-40 w-40 m-2">
                    <div class="flex items-center justify-center bg-blue-400 h-12 w-38 rounded-tl-lg rounded-tr-lg">
                        <p class="font-semibold text-l">High</p>
                    </div>
                    <div class="flex items-center justify-center">
                        <p class="font-semibold text-5xl mt-4">18</p>
                    </div>
                </div>

                <div class="flex flex-col border border-black bg-white rounded-lg h-40 w-40 m-2">
                    <div class="flex items-center justify-center bg-blue-400 h-12 w-38 rounded-tl-lg rounded-tr-lg">
                        <p class="font-semibold text-l">Medium</p>
                    </div>
                    <div class="flex items-center justify-center">
                        <p class="font-semibold text-5xl mt-4">27</p>
                    </div>
                </div>

                <div class="flex flex-col border border-black bg-white rounded-lg h-40 w-40 m-2">
                    <div class="flex items-center justify-center bg-blue-400 h-12 w-38 rounded-tl-lg rounded-tr-lg">
                        <p class="font-semibold text-l">Low</p>
                    </div>
                    <div class="flex items-center justify-center">
                        <p class="font-semibold text-5xl mt-4">0</p>
                    </div>
                </div>

                <div class="flex flex-col border border-black bg-white rounded-lg h-40 w-40 m-2">
                    <div class="flex items-center justify-center bg-blue-400 h-12 w-38 rounded-tl-lg rounded-tr-lg">
                        <p class="font-semibold text-l">Info</p>
                    </div>
                    <div class="flex items-center justify-center">
                        <p class="font-semibold text-5xl mt-4">10</p>
                    </div>
                </div>

                <div class="flex flex-col border border-black bg-white rounded-lg h-40 w-40 m-2">
                    <div class="flex items-center justify-center bg-blue-400 h-12 w-38 rounded-tl-lg rounded-tr-lg">
                        <p class="font-semibold text-l">Unknown</p>
                    </div>
                    <div class="flex items-center justify-center">
                        <p class="font-semibold text-5xl mt-4">0</p>
                    </div>
                </div>

            </div>

            <div class="relative border rounded-lg border-black bg-gradient-to-t from-green-400 to-blue-400 w-full h-22 mb-8">

                <div class="flex text-l text-left font-semibold mt-2 ml-2">
                    <p class="">Status</p>
                    <p class="pl-40">Severity</p>
                    <p class="pl-40 pr-12">Scanner</p>
                    <p class="px-20">Activity</p>
                    <p class="pl-20">Project</p>
                </div>

                <div class="flex space-x-5 ml-2 mb-2">
                    <div class="relative inline-block text-left">
                        <div>
                            <span class="shadow-sm">
                                <button @click="DropdownisOpen" type="button" class="inline-flex justify-center w-48 border border-black rounded-lg px-4 py-2 bg-white text-sm leading-5 font-medium text-black hover:text-blue-500 focus:outline-none focus:border-black focus:shadow-outline-blue active:bg-black active:text-black transition ease-in-out duration-150">
                                <span class="text-left ml-2">Select</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-2">
                                <path fill-rule="evenodd" d="M10 3a1 1 0 0 1 .707.293l4 4a1 1 0 0 1-1.414 1.414L10 5.414 6.707 8.707a1 1 0 1 1-1.414-1.414l4-4A1 1 0 0 1 10 3zm0 14a1 1 0 0 1-.707-.293l-4-4a1 1 0 0 1 1.414-1.414L10 14.586l3.293-3.293a1 1 0 0 1 1.414 1.414l-4 4A1 1 0 0 1 10 17z" clip-rule="evenodd" />
                                </svg>
                                </button>
                            </span>
                        </div>
                        <div class="origin-top-right absolute left-0 mt-2 w-56 shadow-lg">
                            <div class="bg-white shadow-xs">
                                <ul v-if="isOpen" class="py-1">
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 1</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 2</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 3</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="relative inline-block text-left">
                        <div>
                            <span class="shadow-sm">
                                <button @click="DropdownisOpen2" type="button" class="inline-flex justify-center w-48 border border-black rounded-lg px-4 py-2 bg-white text-sm leading-5 font-medium text-black hover:text-blue-500 focus:outline-none focus:border-black focus:shadow-outline-blue active:bg-black active:text-black transition ease-in-out duration-150">
                                <span class="text-left ml-2">Select</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-2">
                                <path fill-rule="evenodd" d="M10 3a1 1 0 0 1 .707.293l4 4a1 1 0 0 1-1.414 1.414L10 5.414 6.707 8.707a1 1 0 1 1-1.414-1.414l4-4A1 1 0 0 1 10 3zm0 14a1 1 0 0 1-.707-.293l-4-4a1 1 0 0 1 1.414-1.414L10 14.586l3.293-3.293a1 1 0 0 1 1.414 1.414l-4 4A1 1 0 0 1 10 17z" clip-rule="evenodd" />
                                </svg>
                                </button>
                            </span>
                        </div>
                        <div class="origin-top-right absolute left-0 mt-2 w-56 shadow-lg">
                            <div class="bg-white shadow-xs">
                                <ul v-if="isOpen2" class="py-1">
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 1</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 2</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 3</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="relative inline-block text-left">
                        <div>
                            <span class="shadow-sm">
                                <button @click="DropdownisOpen3" type="button" class="inline-flex justify-center w-48 border border-black rounded-lg px-4 py-2 bg-white text-sm leading-5 font-medium text-black hover:text-blue-500 focus:outline-none focus:border-black focus:shadow-outline-blue active:bg-black active:text-black transition ease-in-out duration-150">
                                <span class="text-left ml-2">Select</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-2">
                                <path fill-rule="evenodd" d="M10 3a1 1 0 0 1 .707.293l4 4a1 1 0 0 1-1.414 1.414L10 5.414 6.707 8.707a1 1 0 1 1-1.414-1.414l4-4A1 1 0 0 1 10 3zm0 14a1 1 0 0 1-.707-.293l-4-4a1 1 0 0 1 1.414-1.414L10 14.586l3.293-3.293a1 1 0 0 1 1.414 1.414l-4 4A1 1 0 0 1 10 17z" clip-rule="evenodd" />
                                </svg>
                                </button>
                            </span>
                        </div>
                        <div class="origin-top-right absolute left-0 mt-2 w-56 shadow-lg">
                            <div class="bg-white shadow-xs">
                                <ul v-if="isOpen3" class="py-1">
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 1</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 2</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 3</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    
                    <div class="relative inline-block text-left">
                        <div>
                            <span class="shadow-sm">
                                <button @click="DropdownisOpen4" type="button" class="inline-flex justify-center w-48 border border-black rounded-lg px-4 py-2 bg-white text-sm leading-5 font-medium text-black hover:text-blue-500 focus:outline-none focus:border-black focus:shadow-outline-blue active:bg-black active:text-black transition ease-in-out duration-150">
                                <span class="text-left ml-2">Select</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-2">
                                <path fill-rule="evenodd" d="M10 3a1 1 0 0 1 .707.293l4 4a1 1 0 0 1-1.414 1.414L10 5.414 6.707 8.707a1 1 0 1 1-1.414-1.414l4-4A1 1 0 0 1 10 3zm0 14a1 1 0 0 1-.707-.293l-4-4a1 1 0 0 1 1.414-1.414L10 14.586l3.293-3.293a1 1 0 0 1 1.414 1.414l-4 4A1 1 0 0 1 10 17z" clip-rule="evenodd" />
                                </svg>
                                </button>
                            </span>
                        </div>
                        <div class="origin-top-right absolute left-0 mt-2 w-56 shadow-lg">
                            <div class="bg-white shadow-xs">
                                <ul v-if="isOpen4" class="py-1">
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 1</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 2</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 3</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="relative inline-block text-left">
                        <div>
                            <span class="shadow-sm">
                                <button @click="DropdownisOpen5" type="button" class="inline-flex justify-center w-48 border border-black rounded-lg px-4 py-2 bg-white text-sm leading-5 font-medium text-black hover:text-blue-500 focus:outline-none focus:border-black focus:shadow-outline-blue active:bg-black active:text-black transition ease-in-out duration-150">
                                <span class="text-left ml-2">Select</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-2">
                                <path fill-rule="evenodd" d="M10 3a1 1 0 0 1 .707.293l4 4a1 1 0 0 1-1.414 1.414L10 5.414 6.707 8.707a1 1 0 1 1-1.414-1.414l4-4A1 1 0 0 1 10 3zm0 14a1 1 0 0 1-.707-.293l-4-4a1 1 0 0 1 1.414-1.414L10 14.586l3.293-3.293a1 1 0 0 1 1.414 1.414l-4 4A1 1 0 0 1 10 17z" clip-rule="evenodd" />
                                </svg>
                                </button>
                            </span>
                        </div>
                        <div class="origin-top-right absolute left-0 mt-2 w-56 shadow-lg">
                            <div class="bg-white shadow-xs">
                                <ul v-if="isOpen5" class="py-1">
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 1</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 2</a>
                                    </li>
                                    <li>
                                    <a href="#" class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 hover:text-gray-900 focus:outline-none focus:bg-gray-100 focus:text-gray-900">Opsi 3</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <table class="min-w-full">
  <thead>
    <tr>
      <th class="py-2 px-4 bg-green-400 border border-gray-900"><input type="checkbox" id="myCheckbox" class="form-checkbox h-5 w-5 text-indigo-600">
      <label for="myCheckbox"></label></th>
      <th class="py-2 px-4 bg-green-400 border border-gray-900">Detected</th>
      <th class="py-2 px-4 bg-green-400 border border-gray-900">Status</th>
      <th class="py-2 px-4 bg-green-400 border border-gray-900">Severity</th>
      <th class="py-2 px-4 bg-green-400 border border-gray-900">Description</th>
      <th class="py-2 px-4 bg-green-400 border border-gray-900">Scanner</th>
      <th class="py-2 px-4 bg-green-400 border border-gray-900">Identifier</th>
      <th class="py-2 px-4 bg-green-400 border border-gray-900">Activity</th>
    </tr>
  </thead>
  <tbody class="bg-white">
    <tr>
      <td class="py-2 px-4 border border-gray-900"><input type="checkbox" id="myCheckbox" class="form-checkbox h-5 w-5 text-indigo-600">
      <label for="myCheckbox"></label></td>
      <td class="py-2 px-4 border border-gray-900">2023-04-11</td>
      <td class="py-2 px-4 border border-gray-900">Detected</td>
      <td class="py-2 px-4 border border-gray-900">Critical</td>
      <td class="py-2 px-4 border border-gray-900">
          <a href="/dashboard/home/report/id" class="underline">Arbritary Code Exec</a></td>
      <td class="py-2 px-4 border border-gray-900">CVE</td>
      <td class="py-2 px-4 border border-gray-900">DAST</td>
      <td class="py-2 px-4 border border-gray-900"></td>
    </tr>
    <tr>
      <td class="py-2 px-4 border border-gray-900"><input type="checkbox" id="myCheckbox" class="form-checkbox h-5 w-5 text-indigo-600">
      <label for="myCheckbox"></label></td>
      <td class="py-2 px-4 border border-gray-900">2023-04-11</td>
      <td class="py-2 px-4 border border-gray-900">Detected</td>
      <td class="py-2 px-4 border border-gray-900">Medium</td>
      <td class="py-2 px-4 border border-gray-900">
        <a href="/dashboard/home/report/id" class="underline">Missing CSRF Token</a></td>
      <td class="py-2 px-4 border border-gray-900">CWE</td>
      <td class="py-2 px-4 border border-gray-900">SAST</td>
      <td class="py-2 px-4 border border-gray-900"></td>
    </tr>
    <tr>
      <td class="py-2 px-4 border border-gray-900"><input type="checkbox" id="myCheckbox" class="form-checkbox h-5 w-5 text-indigo-600">
      <label for="myCheckbox"></label></td>
      <td class="py-2 px-4 border border-gray-900">2023-04-11</td>
      <td class="py-2 px-4 border border-gray-900">Confirmed</td>
      <td class="py-2 px-4 border border-gray-900">Critical</td>
      <td class="py-2 px-4 border border-gray-900">
        <a href="/dashboard/home/report/id" class="underline">Arbritary Code Exec</a></td>
      <td class="py-2 px-4 border border-gray-900">CVE</td>
      <td class="py-2 px-4 border border-gray-900">DAST</td>
      <td class="py-2 px-4 border border-gray-900"></td>
    </tr>
    <tr>
      <td class="py-2 px-4 border border-gray-900"><input type="checkbox" id="myCheckbox" class="form-checkbox h-5 w-5 text-indigo-600">
      <label for="myCheckbox"></label></td>
      <td class="py-2 px-4 border border-gray-900">2023-04-11</td>
      <td class="py-2 px-4 border border-gray-900">Confirmed</td>
      <td class="py-2 px-4 border border-gray-900">Critical</td>
      <td class="py-2 px-4 border border-gray-900">
        <a href="/dashboard/home/report/id" class="underline">Arbritary Code Exec</a></td>
      <td class="py-2 px-4 border border-gray-900">CVE</td>
      <td class="py-2 px-4 border border-gray-900">DAST</td>
      <td class="py-2 px-4 border border-gray-900"></td>
    </tr>
    <tr>
      <td class="py-2 px-4 border border-gray-900"><input type="checkbox" id="myCheckbox" class="form-checkbox h-5 w-5 text-indigo-600">
      <label for="myCheckbox"></label></td>
      <td class="py-2 px-4 border border-gray-900">2023-04-11</td>
      <td class="py-2 px-4 border border-gray-900">Confirmed</td>
      <td class="py-2 px-4 border border-gray-900">Critical</td>
      <td class="py-2 px-4 border border-gray-900">
        <a href="/dashboard/home/report/id" class="underline">Arbritary Code Exec</a></td>
      <td class="py-2 px-4 border border-gray-900">CVE</td>
      <td class="py-2 px-4 border border-gray-900">DAST</td>
      <td class="py-2 px-4 border border-gray-900"></td>
    </tr>
    <tr>
      <td class="py-2 px-4 border border-gray-900"><input type="checkbox" id="myCheckbox" class="form-checkbox h-5 w-5 text-indigo-600">
      <label for="myCheckbox"></label></td>
      <td class="py-2 px-4 border border-gray-900">2023-04-11</td>
      <td class="py-2 px-4 border border-gray-900">Confirmed</td>
      <td class="py-2 px-4 border border-gray-900">Critical</td>
      <td class="py-2 px-4 border border-gray-900">
        <a href="/dashboard/home/report/id" class="underline">Arbritary Code Exec</a></td>
      <td class="py-2 px-4 border border-gray-900">CVE</td>
      <td class="py-2 px-4 border border-gray-900">DAST</td>
      <td class="py-2 px-4 border border-gray-900"></td>
    </tr>      
  </tbody>
</table>

  

    </div>



    
</template>

<script>


export default {
    name: 'DashboardReport',
    data() {
        return {
            isOpen: false,
            isOpen2: false,
            isOpen3: false,
            isOpen4: false,
            isOpen5: false,
        };
    },
    methods:{
        DropdownisOpen(){
            this.isOpen = !
            this.isOpen;
        },
        DropdownisOpen2(){
            this.isOpen2 = !
            this.isOpen2;
        },
        DropdownisOpen3(){
            this.isOpen3 = !
            this.isOpen3;
        },
        DropdownisOpen4(){
            this.isOpen4 = !
            this.isOpen4;
        },
        DropdownisOpen5(){
            this.isOpen5 = !
            this.isOpen5;
        },
    },
}

</script>