<template>
  <div class="text-sm text-gray-900">
    <nav class="bg-gray-900 flex items-center justify-between px-10 py-4">
      <div class="flex items-center space-x-3">
        <a href="#">
          <svg
            viewBox="0 0 16 16"
            class="h-9 w-9 fill-current text-white hover:text-gray-300"
          >
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>
        </a>

        <div class="relative">
          <input
            type="text"
            class="border border-gray-600 rounded bg-gray-900 placeholder-gray-300 px-2 py-1 w-72 text-white"
            placeholder="Search or jump to..."
          />

          <div class="absolute top-0 right-0 h-full flex items-center">
            <div class="border border-gray-600 rounded text-gray-600 px-1 mr-2">
              /
            </div>
          </div>
        </div>

        <ul class="text-white flex items-center space-x-2">
          <li>
            <a href="#" class="hover:text-gray-300 font-semibold"
              >Pull requests</a
            >
          </li>
          <li>
            <a href="#" class="hover:text-gray-300 font-semibold">Issues</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-300 font-semibold"
              >MarketPlace</a
            >
          </li>
          <li>
            <a href="#" class="hover:text-gray-300 font-semibold">Explore</a>
          </li>
        </ul>
      </div>

      <div class="flex items-center space-x-2 text-white">
        <a href="#" class="hover:text-gray-300">
          <svg
            class="h-5 w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
            />
          </svg>
        </a>

        <div class="flex items-center hover:text-gray-300 cursor-pointer">
          <div class="relative">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 4v16m8-8H4"
              />
            </svg>

            <div
              class="rounded-full bg-blue-500 w-2 h-2 absolute top-0 right-0"
            ></div>
          </div>

          <svg
            class="h-3 w-3 ml-1"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </div>

        <div class="flex items-center hover:text-gray-300 cursor-pointer">
          <div class="relative">
            <img
              src="https://avatars.githubusercontent.com/u/42379721?s=96&v=4"
              alt="image"
              class="h-5 w-5 rounded-full"
            />

            <div
              class="rounded-full bg-blue-500 w-2 h-2 absolute top-0 -right-0.5"
            ></div>
          </div>

          <svg
            class="h-3 w-3 ml-1"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </div>
      </div>
    </nav>

    <section class="flex items-center justify-between px-10 py-3 bg-gray-100">
      <div class="flex items-center space-x-2">
        <svg viewBox="0 0 16 16" class="mr-2 w-4 h-4 fill-current">
          <path
            fill-rule="evenodd"
            d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"
          ></path>
        </svg>

        <div>
          <a href="#" class="text-blue-500 text-xl hover:underline">jinfayap</a>
          <span class="text-xl">/</span>
          <a
            href="#"
            class="text-blue-500 font-semibold text-xl hover:underline"
            >quizzy</a
          >
        </div>

        <span
          class="rounded-full border border-gray-300 text-gray-600 font-semibold px-2 py-0.5 text-xs"
          >Public</span
        >
      </div>

      <div class="flex items-center space-x-3">
        <div
          class="flex items-center border border-gray-300 px-2 py-1 rounded cursor-pointer"
        >
          <svg
            fill="currentColor"
            viewBox="0 0 16 16"
            class="mr-2 text-gray-500 w-4 h-4"
          >
            <path
              fill-rule="evenodd"
              d="M4.456.734a1.75 1.75 0 012.826.504l.613 1.327a3.081 3.081 0 002.084 1.707l2.454.584c1.332.317 1.8 1.972.832 2.94L11.06 10l3.72 3.72a.75.75 0 11-1.061 1.06L10 11.06l-2.204 2.205c-.968.968-2.623.5-2.94-.832l-.584-2.454a3.081 3.081 0 00-1.707-2.084l-1.327-.613a1.75 1.75 0 01-.504-2.826L4.456.734zM5.92 1.866a.25.25 0 00-.404-.072L1.794 5.516a.25.25 0 00.072.404l1.328.613A4.582 4.582 0 015.73 9.63l.584 2.454a.25.25 0 00.42.12l5.47-5.47a.25.25 0 00-.12-.42L9.63 5.73a4.581 4.581 0 01-3.098-2.537L5.92 1.866z"
            ></path>
          </svg>

          <span class="font-semibold text-xs">Pin</span>
        </div>

        <div
          class="flex items-center border border-gray-300 px-2 py-1 rounded cursor-pointer space-x-2"
        >
          <svg
            class="w-4 h-4"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
            />
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"
            />
          </svg>

          <span class="font-semibold text-xs">Unwatch</span>

          <div
            class="w-4 h-4 rounded-full bg-gray-200 flex items-center justify-center font-semibold"
          >
            1
          </div>

          <svg
            class="h-3 w-3 ml-1"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </div>

        <div
          class="flex items-center border border-gray-300 px-2 py-1 rounded cursor-pointer space-x-2"
        >
          <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
            <path
              fill-rule="evenodd"
              d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"
            ></path>
          </svg>

          <span class="font-semibold text-xs">Fork</span>

          <div
            class="w-4 h-4 rounded-full bg-gray-200 flex items-center justify-center font-semibold"
          >
            0
          </div>
        </div>

        <div class="flex items-center">
          <div
            class="flex items-center border border-gray-300 px-2 py-1 rounded-l cursor-pointer space-x-2"
          >
            <svg
              fill="none"
              class="w-4 h-4"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z"
              />
            </svg>
            <span class="font-semibold text-xs">Star</span>
            <div
              class="w-4 h-4 rounded-full bg-gray-200 flex items-center justify-center font-semibold"
            >
              0
            </div>
          </div>

          <div
            class="border border-gray-300 border-l-0 rounded-r px-2 py-1 cursor-pointer"
          >
            <svg
              class="h-4 w-4"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M19 9l-7 7-7-7"
              />
            </svg>
          </div>
        </div>
      </div>
    </section>

    <section>
      <ul
        class="border-b border-gray-400 bg-gray-100 flex space-x-4 px-10 pt-3"
      >
        <li class="font-semibold">
          <a href="#" class="flex items-center border-b-2 border-red-600 pb-3">
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M4.72 3.22a.75.75 0 011.06 1.06L2.06 8l3.72 3.72a.75.75 0 11-1.06 1.06L.47 8.53a.75.75 0 010-1.06l4.25-4.25zm6.56 0a.75.75 0 10-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 101.06 1.06l4.25-4.25a.75.75 0 000-1.06l-4.25-4.25z"
              ></path>
            </svg>
            <span class="ml-2">Code</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path d="M8 9.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
              <path
                fill-rule="evenodd"
                d="M8 0a8 8 0 100 16A8 8 0 008 0zM1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0z"
              ></path>
            </svg>
            <span class="ml-2">Issues</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"
              ></path>
            </svg>
            <span class="ml-2">Pull requests</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"
              ></path>
            </svg>
            <span class="ml-2">Actions</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v3.585a.746.746 0 010 .83v8.085A1.75 1.75 0 0114.25 16H6.309a.748.748 0 01-1.118 0H1.75A1.75 1.75 0 010 14.25V6.165a.746.746 0 010-.83V1.75zM1.5 6.5v7.75c0 .138.112.25.25.25H5v-8H1.5zM5 5H1.5V1.75a.25.25 0 01.25-.25H5V5zm1.5 1.5v8h7.75a.25.25 0 00.25-.25V6.5h-8zm8-1.5h-8V1.5h7.75a.25.25 0 01.25.25V5z"
              ></path>
            </svg>
            <span class="ml-2">Projects</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"
              ></path>
            </svg>
            <span class="ml-2">Wiki</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"
              ></path>
            </svg>
            <span class="ml-2">Security</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"
              ></path>
            </svg>
            <span class="ml-2">Insights</span></a
          >
        </li>

        <li>
          <a
            href="#"
            class="flex items-center pb-3 border-b-2 hover:border-gray-300"
          >
            <svg fill="currentColor" viewBox="0 0 16 16" class="w-4 h-4">
              <path
                fill-rule="evenodd"
                d="M7.429 1.525a6.593 6.593 0 011.142 0c.036.003.108.036.137.146l.289 1.105c.147.56.55.967.997 1.189.174.086.341.183.501.29.417.278.97.423 1.53.27l1.102-.303c.11-.03.175.016.195.046.219.31.41.641.573.989.014.031.022.11-.059.19l-.815.806c-.411.406-.562.957-.53 1.456a4.588 4.588 0 010 .582c-.032.499.119 1.05.53 1.456l.815.806c.08.08.073.159.059.19a6.494 6.494 0 01-.573.99c-.02.029-.086.074-.195.045l-1.103-.303c-.559-.153-1.112-.008-1.529.27-.16.107-.327.204-.5.29-.449.222-.851.628-.998 1.189l-.289 1.105c-.029.11-.101.143-.137.146a6.613 6.613 0 01-1.142 0c-.036-.003-.108-.037-.137-.146l-.289-1.105c-.147-.56-.55-.967-.997-1.189a4.502 4.502 0 01-.501-.29c-.417-.278-.97-.423-1.53-.27l-1.102.303c-.11.03-.175-.016-.195-.046a6.492 6.492 0 01-.573-.989c-.014-.031-.022-.11.059-.19l.815-.806c.411-.406.562-.957.53-1.456a4.587 4.587 0 010-.582c.032-.499-.119-1.05-.53-1.456l-.815-.806c-.08-.08-.073-.159-.059-.19a6.44 6.44 0 01.573-.99c.02-.029.086-.075.195-.045l1.103.303c.559.153 1.112.008 1.529-.27.16-.107.327-.204.5-.29.449-.222.851-.628.998-1.189l.289-1.105c.029-.11.101-.143.137-.146zM8 0c-.236 0-.47.01-.701.03-.743.065-1.29.615-1.458 1.261l-.29 1.106c-.017.066-.078.158-.211.224a5.994 5.994 0 00-.668.386c-.123.082-.233.09-.3.071L3.27 2.776c-.644-.177-1.392.02-1.82.63a7.977 7.977 0 00-.704 1.217c-.315.675-.111 1.422.363 1.891l.815.806c.05.048.098.147.088.294a6.084 6.084 0 000 .772c.01.147-.038.246-.088.294l-.815.806c-.474.469-.678 1.216-.363 1.891.2.428.436.835.704 1.218.428.609 1.176.806 1.82.63l1.103-.303c.066-.019.176-.011.299.071.213.143.436.272.668.386.133.066.194.158.212.224l.289 1.106c.169.646.715 1.196 1.458 1.26a8.094 8.094 0 001.402 0c.743-.064 1.29-.614 1.458-1.26l.29-1.106c.017-.066.078-.158.211-.224a5.98 5.98 0 00.668-.386c.123-.082.233-.09.3-.071l1.102.302c.644.177 1.392-.02 1.82-.63.268-.382.505-.789.704-1.217.315-.675.111-1.422-.364-1.891l-.814-.806c-.05-.048-.098-.147-.088-.294a6.1 6.1 0 000-.772c-.01-.147.039-.246.088-.294l.814-.806c.475-.469.679-1.216.364-1.891a7.992 7.992 0 00-.704-1.218c-.428-.609-1.176-.806-1.82-.63l-1.103.303c-.066.019-.176.011-.299-.071a5.991 5.991 0 00-.668-.386c-.133-.066-.194-.158-.212-.224L10.16 1.29C9.99.645 9.444.095 8.701.031A8.094 8.094 0 008 0zm1.5 8a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM11 8a3 3 0 11-6 0 3 3 0 016 0z"
              ></path>
            </svg>
            <span class="ml-2">Settings</span></a
          >
        </li>
      </ul>
    </section>

    <section>
      <div class="container max-w-7xl flex mx-auto mt-6">
        <div class="w-3/4 px-4 flex flex-col">
          <div class="branch-items flex items-center justify-between">
            <div class="flex space-x-2">
              <div
                class="flex items-center border border-gray-300 bg-gray-100 px-2 py-1 rounded cursor-pointer space-x-1"
              >
                <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
                  <path
                    fill-rule="evenodd"
                    d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                  ></path>
                </svg>

                <span class="font-semibold text-xs">main</span>

                <svg
                  class="h-3 w-3 ml-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M19 9l-7 7-7-7"
                  />
                </svg>
              </div>

              <div
                class="flex items-center px-2 py-1 rounded cursor-pointer space-x-1 hover:text-blue-500"
              >
                <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
                  <path
                    fill-rule="evenodd"
                    d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                  ></path>
                </svg>

                <span class="font-semibold text-xs">1</span>
                <span class="font-semibold text-xs text-gray-400">branch</span>
              </div>

              <div
                class="flex items-center px-2 py-1 rounded cursor-pointer space-x-1 hover:text-blue-500"
              >
                <svg viewBox="0 0 16 16" class="h-4 w-4 fill-current">
                  <path
                    fill-rule="evenodd"
                    d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
                  ></path>
                </svg>

                <span class="font-semibold text-xs">0</span>
                <span class="font-semibold text-xs text-gray-400">tags</span>
              </div>
            </div>

            <div class="flex items-center space-x-2">
              <div
                class="flex items-center border border-gray-300 bg-gray-100 px-2 py-1 rounded cursor-pointer"
              >
                <span class="font-semibold text-xs">Go to file</span>
              </div>

              <div
                class="flex items-center border border-gray-300 bg-gray-100 px-2 py-1 rounded cursor-pointer space-x-1"
              >
                <span class="font-semibold text-xs">Add file</span>

                <svg
                  class="h-3 w-3 ml-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M19 9l-7 7-7-7"
                  />
                </svg>
              </div>

              <div
                class="flex items-center bg-green-400 hover:bg-green-500 px-2 py-1 rounded cursor-pointer space-x-1"
              >
                <span class="font-semibold text-xs text-white">Code</span>

                <svg
                  class="h-3 w-3 ml-1 fill-current text-gray-400"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M19 9l-7 7-7-7"
                  />
                </svg>
              </div>
            </div>
          </div>

          <div class="my-4 border border-gray-300 rounded bg-gray-100">
            <div
              class="flex items-center justify-between border-b border-gray-300 py-3 px-2"
            >
              <div class="space-x-2 flex items-center">
                <img
                  src="https://avatars.githubusercontent.com/u/42379721?s=96&v=4"
                  alt="image"
                  class="h-5 w-5 rounded-full"
                />

                <a href="#" class="font-semibold text-xs">jinfayap</a>
                <a herf="#" class="text-xs">Production</a>
              </div>

              <div class="flex items-center space-x-2">
                <a href="#" class="text-xs">17adb3c</a>
                <a href="#" class="text-xs">2 days ago</a>
                <div
                  class="flex items-center px-2 py-1 rounded cursor-pointer space-x-1 hover:text-blue-500"
                >
                  <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
                    <path
                      fill-rule="evenodd"
                      d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"
                    ></path>
                  </svg>

                  <span class="font-semibold text-xs">60</span>
                  <span class="font-semibold text-xs text-gray-400"
                    >commits</span
                  >
                </div>
              </div>
            </div>

            <div class="bg-white divide-y">
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>

                  <a href="#" class="hover:underline hover:text-blue-500"
                    >app</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Fix restriction to pages and display of information to correct
                  user</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>

              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >bootstrap</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>

              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >config</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Spatie Permission and Role Permission Test</a
                >

                <span class="w-1/4 text-right">11 days ago</span>
              </article>

              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >database</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Tweak seeder</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>

              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >public</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4"
                  >Production</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>

              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >resources</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4"
                  >Production</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >routes</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Tweaks to Controller</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >storage</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg
                    class="h-4 w-4 fill-blue-500"
                    fill="#54aeff"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >tests</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Fix restriction to pages and display of information to correct
                  user</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>

              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >.editorconfig</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Create and Edit Pages</a
                >

                <span class="w-1/4 text-right">18 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >.env.example</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >.gitattributes</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >.gitignore</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >.styleci.yml</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >Procfile</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Add Procfile for Heroku</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >README.md</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Add Procfile for Heroku</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >artisan</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >composer.json</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Update Test</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >composer.lock</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Update composer</a
                >

                <span class="w-1/4 text-right">2 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >package-lock.json</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Vue flash message</a
                >

                <span class="w-1/4 text-right">15 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >package.json</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Vue flash message</a
                >

                <span class="w-1/4 text-right">15 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >phpunit.xml</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Quiz Test</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >server.php</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Laravel Breeze Init and Vue3 Installation</a
                >

                <span class="w-1/4 text-right">19 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >tailwind.config.js</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Reusable Modal and create question with modal</a
                >

                <span class="w-1/4 text-right">17 days ago</span>
              </article>
              <article
                class="flex justify-between py-1 px-2 items-center hover:bg-gray-100"
              >
                <div class="flex items-center space-x-3 w-1/4">
                  <svg viewBox="0 0 16 16" class="w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                    ></path>
                  </svg>
                  <a href="#" class="hover:underline hover:text-blue-500"
                    >webpack.mix.js</a
                  >
                </div>

                <a href="#" class="hover:underline hover:text-blue-500 w-2/4">
                  Create and Edit Pages</a
                >

                <span class="w-1/4 text-right">18 days ago</span>
              </article>
            </div>
          </div>

          <div class="border border-gray-300 bg-white rounded mt-2 px-2 py-2">
            <div
              class="flex items-center justify-between border-gray-300 border-b"
            >
              <div class="flex items-center">
                <button class="p-2 hover:bg-gray-100 rounded">
                  <svg viewBox="0 0 16 16" class="fill-current w-4 h-4">
                    <path
                      fill-rule="evenodd"
                      d="M2 4a1 1 0 100-2 1 1 0 000 2zm3.75-1.5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zM3 8a1 1 0 11-2 0 1 1 0 012 0zm-1 6a1 1 0 100-2 1 1 0 000 2z"
                    ></path>
                  </svg>
                </button>

                <a
                  href="#"
                  class="font-bold ml-3 hover:underline hover:text-blue-500"
                  >README.md</a
                >
              </div>

              <button class="p-2 hover:bg-gray-100 rounded">
                <svg viewBox="0 0 16 16" class="fill-current w-4 h-4">
                  <path
                    fill-rule="evenodd"
                    d="M11.013 1.427a1.75 1.75 0 012.474 0l1.086 1.086a1.75 1.75 0 010 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 01-.927-.928l.929-3.25a1.75 1.75 0 01.445-.758l8.61-8.61zm1.414 1.06a.25.25 0 00-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 000-.354l-1.086-1.086zM11.189 6.25L9.75 4.81l-6.286 6.287a.25.25 0 00-.064.108l-.558 1.953 1.953-.558a.249.249 0 00.108-.064l6.286-6.286z"
                  ></path>
                </svg>
              </button>
            </div>
            <!-- eslint-disable vue/no-v-html -->
            <div class="prose max-w-none p-2" v-html="readme"></div>
            <!--eslint-enable-->
          </div>
        </div>

        <div class="side-bar w-1/4">
          <div class="flex flex-col space-y-3">
            <div class="flex items-center justify-between pr-1">
              <span class="font-semibold">About</span>
              <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
                <path
                  fill-rule="evenodd"
                  d="M7.429 1.525a6.593 6.593 0 011.142 0c.036.003.108.036.137.146l.289 1.105c.147.56.55.967.997 1.189.174.086.341.183.501.29.417.278.97.423 1.53.27l1.102-.303c.11-.03.175.016.195.046.219.31.41.641.573.989.014.031.022.11-.059.19l-.815.806c-.411.406-.562.957-.53 1.456a4.588 4.588 0 010 .582c-.032.499.119 1.05.53 1.456l.815.806c.08.08.073.159.059.19a6.494 6.494 0 01-.573.99c-.02.029-.086.074-.195.045l-1.103-.303c-.559-.153-1.112-.008-1.529.27-.16.107-.327.204-.5.29-.449.222-.851.628-.998 1.189l-.289 1.105c-.029.11-.101.143-.137.146a6.613 6.613 0 01-1.142 0c-.036-.003-.108-.037-.137-.146l-.289-1.105c-.147-.56-.55-.967-.997-1.189a4.502 4.502 0 01-.501-.29c-.417-.278-.97-.423-1.53-.27l-1.102.303c-.11.03-.175-.016-.195-.046a6.492 6.492 0 01-.573-.989c-.014-.031-.022-.11.059-.19l.815-.806c.411-.406.562-.957.53-1.456a4.587 4.587 0 010-.582c.032-.499-.119-1.05-.53-1.456l-.815-.806c-.08-.08-.073-.159-.059-.19a6.44 6.44 0 01.573-.99c.02-.029.086-.075.195-.045l1.103.303c.559.153 1.112.008 1.529-.27.16-.107.327-.204.5-.29.449-.222.851-.628.998-1.189l.289-1.105c.029-.11.101-.143.137-.146zM8 0c-.236 0-.47.01-.701.03-.743.065-1.29.615-1.458 1.261l-.29 1.106c-.017.066-.078.158-.211.224a5.994 5.994 0 00-.668.386c-.123.082-.233.09-.3.071L3.27 2.776c-.644-.177-1.392.02-1.82.63a7.977 7.977 0 00-.704 1.217c-.315.675-.111 1.422.363 1.891l.815.806c.05.048.098.147.088.294a6.084 6.084 0 000 .772c.01.147-.038.246-.088.294l-.815.806c-.474.469-.678 1.216-.363 1.891.2.428.436.835.704 1.218.428.609 1.176.806 1.82.63l1.103-.303c.066-.019.176-.011.299.071.213.143.436.272.668.386.133.066.194.158.212.224l.289 1.106c.169.646.715 1.196 1.458 1.26a8.094 8.094 0 001.402 0c.743-.064 1.29-.614 1.458-1.26l.29-1.106c.017-.066.078-.158.211-.224a5.98 5.98 0 00.668-.386c.123-.082.233-.09.3-.071l1.102.302c.644.177 1.392-.02 1.82-.63.268-.382.505-.789.704-1.217.315-.675.111-1.422-.364-1.891l-.814-.806c-.05-.048-.098-.147-.088-.294a6.1 6.1 0 000-.772c-.01-.147.039-.246.088-.294l.814-.806c.475-.469.679-1.216.364-1.891a7.992 7.992 0 00-.704-1.218c-.428-.609-1.176-.806-1.82-.63l-1.103.303c-.066.019-.176.011-.299-.071a5.991 5.991 0 00-.668-.386c-.133-.066-.194-.158-.212-.224L10.16 1.29C9.99.645 9.444.095 8.701.031A8.094 8.094 0 008 0zm1.5 8a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM11 8a3 3 0 11-6 0 3 3 0 016 0z"
                ></path>
              </svg>
            </div>

            <div class="flex space-x-2 items-center">
              <svg viewBox="0 0 16 16" class="fill-current w-4 h-4">
                <path
                  fill-rule="evenodd"
                  d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"
                ></path>
              </svg>
              <a href="#" class="text-blue-500 font-semibold hover:underline"
                >laraquizzy.herokuapp.com/</a
              >
            </div>

            <a href="#" class="flex space-x-2 items-center hover:text-blue-500">
              <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
                <path
                  fill-rule="evenodd"
                  d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"
                ></path>
              </svg>
              <span>Readme</span>
            </a>
            <a href="#" class="flex space-x-2 items-center hover:text-blue-500">
              <svg
                fill="none"
                class="w-4 h-4"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z"
                />
              </svg>
              <span>0 stars</span>
            </a>
            <a href="#" class="flex space-x-2 items-center hover:text-blue-500">
              <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
                <path
                  fill-rule="evenodd"
                  d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"
                ></path>
              </svg>
              <span>1 watching</span>
            </a>
            <a href="#" class="flex space-x-2 items-center hover:text-blue-500">
              <svg viewBox="0 0 16 16" class="fill-current w-4 h-4">
                <path
                  fill-rule="evenodd"
                  d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"
                ></path>
              </svg>
              <span>0 forks</span>
            </a>
          </div>

          <hr class="my-4" />

          <div>
            <h2 class="font-semibold">Releases</h2>
            <p class="mt-4 text-xs">No releases published</p>
            <a href="#" class="text-xs text-blue-500 hover:underline"
              >Create a new release</a
            >
          </div>

          <hr class="my-4" />

          <div>
            <h2 class="font-semibold">Packages</h2>
            <p class="mt-4 text-xs">No packages published</p>
            <a href="#" class="text-xs text-blue-500 hover:underline"
              >Publish your first package</a
            >
          </div>

          <hr class="my-4" />

          <div>
            <h2 class="font-semibold">Languages</h2>

            <div class="w-full flex space-x-1 h-1.5 mt-2">
              <div class="bg-purple-700 rounded-l" style="width: 60%"></div>
              <div class="bg-green-700" style="width: 20%"></div>
              <div class="bg-red-500" style="width: 18.5%"></div>
              <div class="bg-yellow-300" style="width: 1.1%"></div>
              <div class="bg-green-300" style="width: 0.2%"></div>
              <div class="bg-gray-800 rounded-r" style="width: 0.1%"></div>
            </div>

            <div class="flex flex-wrap mt-2">
              <span class="flex items-center space-x-1 mr-2">
                <div class="w-2 h-2 rounded-full bg-purple-700"></div>
                <span class="font-semibold text-xs">PHP</span>
                <span class="text-gray-500 text-xs">60.1%</span>
              </span>

              <span class="flex items-center space-x-1 mr-2">
                <div class="w-2 h-2 rounded-full bg-green-700"></div>
                <span class="font-semibold text-xs">Vue</span>
                <span class="text-gray-500 text-xs">20%</span>
              </span>

              <span class="flex items-center space-x-1 mr-2">
                <div class="w-2 h-2 rounded-full bg-red-500"></div>
                <span class="font-semibold text-xs">Vue</span>
                <span class="text-gray-500 text-xs">18.5%</span>
              </span>
              <span class="flex items-center space-x-1 mr-2">
                <div class="w-2 h-2 rounded-full bg-yellow-300"></div>
                <span class="font-semibold text-xs">Javascript</span>
                <span class="text-gray-500 text-xs">1.2%</span>
              </span>
              <span class="flex items-center space-x-1 mr-2">
                <div class="w-2 h-2 rounded-full bg-green-300"></div>
                <span class="font-semibold text-xs">Shell</span>
                <span class="text-gray-500 text-xs">0.2%</span>
              </span>
              <span class="flex items-center space-x-1 mr-2">
                <div class="w-2 h-2 rounded-full bg-gray-800"></div>
                <span class="font-semibold text-xs">CSS</span>
                <span class="text-gray-500 text-xs">0.0%</span>
              </span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <hr class="my-4 max-w-7xl mx-auto px-4" />

    <footer class="max-w-7xl mx-auto px-4 flex items-center py-6">
      <div class="flex space-x-2">
        <a href="#">
          <svg
            viewBox="0 0 16 16"
            class="h-4 w-4 fill-current hover:text-gray-300"
          >
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>
        </a>

        <span class="text-xs text-gray-400">&copy; 2020 Github, Inc.</span>
      </div>
      <div class="ml-12 space-x-8">
        <a href="#" class="text-blue-500 hover:underline">Terms</a>
        <a href="#" class="text-blue-500 hover:underline">Privacy</a>
        <a href="#" class="text-blue-500 hover:underline">Security</a>
        <a href="#" class="text-blue-500 hover:underline">Docs</a>
        <a href="#" class="text-blue-500 hover:underline">Contact Github</a>
        <a href="#" class="text-blue-500 hover:underline">Pricing</a>
        <a href="#" class="text-blue-500 hover:underline">API</a>
        <a href="#" class="text-blue-500 hover:underline">Training</a>
        <a href="#" class="text-blue-500 hover:underline">Blog</a>
        <a href="#" class="text-blue-500 hover:underline">About</a>
      </div>
    </footer>
  </div>
</template>
<script>
import github from './githubReadme.md'
export default {
  computed: {
    readme() {
      return github
    },
  },
}
</script>

<style>
img {
  display: inline-block;
}
</style>
