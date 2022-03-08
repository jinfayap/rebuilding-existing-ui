<template>
  <div class="flex h-screen overflow-hidden bg-white relative">
    <div class="flex bg-black flex-col w-32 md:w-52 text-white mb-20">
      <nav class="px-6 text-sm flex flex-col h-full">
        <svg viewBox="0 0 1134 340" class="-mt-4 w-32 h-32 text-white">
          <title>Spotify</title>
          <path
            fill="currentColor"
            d="M8 171c0 92 76 168 168 168s168-76 168-168S268 4 176 4 8 79 8 171zm230 78c-39-24-89-30-147-17-14 2-16-18-4-20 64-15 118-8 162 19 11 7 0 24-11 18zm17-45c-45-28-114-36-167-20-17 5-23-21-7-25 61-18 136-9 188 23 14 9 0 31-14 22zM80 133c-17 6-28-23-9-30 59-18 159-15 221 22 17 9 1 37-17 27-54-32-144-35-195-19zm379 91c-17 0-33-6-47-20-1 0-1 1-1 1l-16 19c-1 1-1 2 0 3 18 16 40 24 64 24 34 0 55-19 55-47 0-24-15-37-50-46-29-7-34-12-34-22s10-16 23-16 25 5 39 15c0 0 1 1 2 1s1-1 1-1l14-20c1-1 1-1 0-2-16-13-35-20-56-20-31 0-53 19-53 46 0 29 20 38 52 46 28 6 32 12 32 22 0 11-10 17-25 17zm95-77v-13c0-1-1-2-2-2h-26c-1 0-2 1-2 2v147c0 1 1 2 2 2h26c1 0 2-1 2-2v-46c10 11 21 16 36 16 27 0 54-21 54-61s-27-60-54-60c-15 0-26 5-36 17zm30 78c-18 0-31-15-31-35s13-34 31-34 30 14 30 34-12 35-30 35zm68-34c0 34 27 60 62 60s62-27 62-61-26-60-61-60-63 27-63 61zm30-1c0-20 13-34 32-34s33 15 33 35-13 34-32 34-33-15-33-35zm140-58v-29c0-1 0-2-1-2h-26c-1 0-2 1-2 2v29h-13c-1 0-2 1-2 2v22c0 1 1 2 2 2h13v58c0 23 11 35 34 35 9 0 18-2 25-6 1 0 1-1 1-2v-21c0-1 0-2-1-2h-2c-5 3-11 4-16 4-8 0-12-4-12-12v-54h30c1 0 2-1 2-2v-22c0-1-1-2-2-2h-30zm129-3c0-11 4-15 13-15 5 0 10 0 15 2h1s1-1 1-2V93c0-1 0-2-1-2-5-2-12-3-22-3-24 0-36 14-36 39v5h-13c-1 0-2 1-2 2v22c0 1 1 2 2 2h13v89c0 1 1 2 2 2h26c1 0 1-1 1-2v-89h25l37 89c-4 9-8 11-14 11-5 0-10-1-15-4h-1l-1 1-9 19c0 1 0 3 1 3 9 5 17 7 27 7 19 0 30-9 39-33l45-116v-2c0-1-1-1-2-1h-27c-1 0-1 1-1 2l-28 78-30-78c0-1-1-2-2-2h-44v-3zm-83 3c-1 0-2 1-2 2v113c0 1 1 2 2 2h26c1 0 1-1 1-2V134c0-1 0-2-1-2h-26zm-6-33c0 10 9 19 19 19s18-9 18-19-8-18-18-18-19 8-19 18zm245 69c10 0 19-8 19-18s-9-18-19-18-18 8-18 18 8 18 18 18zm0-34c9 0 17 7 17 16s-8 16-17 16-16-7-16-16 7-16 16-16zm4 18c3-1 5-3 5-6 0-4-4-6-8-6h-8v19h4v-6h4l4 6h5zm-3-9c2 0 4 1 4 3s-2 3-4 3h-4v-6h4z"
          ></path>
        </svg>

        <ul class="space-y-2">
          <li class="text-white">
            <a href="#" class="flex items-center">
              <svg class="fill-current w-6 h-6" viewBox="0 0 24 24">
                <path d="M21 22V7.174l-9.001-5.195L3 7.214V22h7v-7h4v7z"></path>
              </svg>
              <span class="ml-4">Home</span></a
            >
          </li>
          <li>
            <a href="#" class="flex items-center">
              <svg class="fill-current w-6 h-6" viewBox="0 0 24 24">
                <path
                  d="M16.387 16.623A8.47 8.47 0 0019 10.5a8.5 8.5 0 10-8.5 8.5 8.454 8.454 0 005.125-1.73l4.401 5.153.76-.649-4.399-5.151zM10.5 18C6.364 18 3 14.636 3 10.5S6.364 3 10.5 3 18 6.364 18 10.5 14.636 18 10.5 18z"
                ></path></svg
              ><span class="ml-4">Search</span></a
            >
          </li>
          <li>
            <a href="#" class="flex items-center"
              ><svg class="fill-current w-6 h-6" viewBox="0 0 24 24">
                <path
                  d="M13.66 4.097l-.913.406 7.797 17.513.914-.406L13.66 4.097zM3 22h1V4H3v18zm6 0h1V4H9v18z"
                ></path></svg
              ><span class="ml-4">Your Library</span></a
            >
          </li>
        </ul>

        <ul class="mt-12 space-y-2">
          <li>
            <a href="#" class="flex items-center">
              <div class="bg-gray-300 flex items-center justify-center w-6 h-6">
                <svg
                  class="h-4 w-4 text-black"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="4"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M12 4v16m8-8H4"
                  />
                </svg>
              </div>
              <span class="ml-4">Create Playlist</span></a
            >
          </li>
          <li>
            <a href="#" class="flex items-center">
              <div
                class="bg-gradient-to-br from-indigo-800 to-white flex items-center justify-center w-6 h-6"
              >
                <svg
                  class="h-5 w-5 text-white"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z"
                    clip-rule="evenodd"
                  />
                </svg>
              </div>
              <span class="ml-4">Liked Songs</span></a
            >
          </li>
        </ul>

        <div
          class="text-gray-300 mt-auto mb-24 flex flex-col space-y-3 text-xs"
        >
          <a href="#" class="hover:underline">Cookies</a>
          <a href="#" class="hover:underline">Privacy</a>
        </div>
      </nav>
    </div>

    <div class="flex flex-col flex-1 w-0 overflow-hidden mb-20 pb-4">
      <main class="relative flex-1 overflow-y-auto">
        <nav
          class="sticky top-0 right-0 bg-black text-xs text-white h-16 px-6 flex items-center justify-between"
        >
          <div class="flex items-center space-x-3 text-gray-300">
            <button>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 w-4"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15 19l-7-7 7-7"
                />
              </svg>
            </button>
            <button>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 w-4"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M9 5l7 7-7 7"
                />
              </svg>
            </button>
          </div>

          <div class="md:space-x-4">
            <a
              href="#"
              class="uppercase font-bold tracking-wide hover:scale-105 inline-block"
              >Sign up</a
            >

            <a
              href="#"
              class="uppercase font-semibold tracking-wide bg-white px-2 py-1 md:px-6 md:py-2 text-black rounded-full inline-block hover:scale-105"
              >Log in</a
            >
          </div>
        </nav>

        <div
          class="main-content min-h-full px-4 py-6"
          style="background-color: #121212"
        >
          <section>
            <div class="flex items-center justify-between font-bold mb-8">
              <a
                class="text-2xl text-white block hover:underline cursor-pointer"
                >Treadsetter Tuesday</a
              >
              <a
                class="uppercase text-base text-gray-400 block hover:underline cursor-pointer"
                >See all</a
              >
            </div>

            <div
              class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 gap-6"
            >
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002c4c45b2c6f838a7dcfd8bb48"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Becoming Women
                </a>
                <p class="text-gray-300 text-base">
                  Time's up! Let's take your masks off
                </p>
              </article>
              <article
                class="bg-gray-500 rounded-md hover:bg-gray-400 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000020026567c14e693f5b55bce2a"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white"
                  >poses</a
                >
                <p class="text-gray-300 text-base">
                  Time to strike a couple of poses!
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002cbff0c1907c12683d1ff5100"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Hot Hits Singapore
                </a>
                <p class="text-gray-300 text-base">
                  The best tracks from the world of music. Cover: Tate McRae
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002c8ad2a320fe2582794f78a1a"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Equal Singapore ...
                </a>
                <p class="text-gray-300 text-base">
                  Listen to women from Singapore and Malay
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000024dcc1f5aa01fa5fc2e14a737"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  EQUAL Global
                </a>
                <p class="text-gray-300 text-base">
                  Listen to women from all over the world, at full...
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002590bff3d410d1c3b22e289a0"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Winter feels
                </a>
                <p class="text-gray-300 text-base">
                  It's starting to feel like winter again. Don't forget ...
                </p>
              </article>
            </div>
          </section>

          <section class="mt-6">
            <div class="flex items-center justify-between font-bold mb-8">
              <a
                class="text-2xl text-white block hover:underline cursor-pointer"
                >Charts</a
              >
            </div>

            <div
              class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 gap-6"
            >
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://charts-images.scdn.co/assets/locale_en/regional/daily/region_sg_default.jpg"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Top 50 - Singapore
                </a>
                <p class="text-gray-300 text-base">
                  Your daily update of the most played tracks right now -
                  Singapore.
                </p>
              </article>
              <article
                class="bg-gray-500 rounded-md hover:bg-gray-400 px-4 py-4"
              >
                <img
                  src="https://charts-images.scdn.co/assets/locale_en/regional/daily/region_global_default.jpg"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white"
                  >Top 50 - Global</a
                >
                <p class="text-gray-300 text-base">
                  Your daily update of the most played tracks right now -
                  Global.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002cbff0c1907c12683d1ff5100"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Hot Hits Singapore
                </a>
                <p class="text-gray-300 text-base">
                  The best tracks from the world of music. Cover: Tate McRae
                </p>
              </article>
            </div>
          </section>

          <section class="mt-6">
            <div class="flex items-center justify-between font-bold mb-8">
              <div>
                <a
                  class="text-2xl text-white block hover:underline cursor-pointer"
                  >Focus</a
                >

                <p class="text-gray-300 font-normal text-sm">
                  Music to help you concentrate
                </p>
              </div>
              <a
                class="uppercase text-base text-gray-400 block hover:underline cursor-pointer"
                >See all</a
              >
            </div>

            <div
              class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 gap-6"
            >
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002ca5a7517156021292e5663a6"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Peaceful Piano
                </a>
                <p class="text-gray-300 text-base">
                  Relax and indulge with beautiful piano pieces
                </p>
              </article>
              <article
                class="bg-gray-500 rounded-md hover:bg-gray-400 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002c8114f56f99e3a37159595f6"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white"
                  >lofi beats</a
                >
                <p class="text-gray-300 text-base">
                  Fly as a kite with beats to chill, relax, study, code, focus,
                  and sleep... 🪁
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002c7059110f5a17c6a5c353e2a"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Jazz in the Background
                </a>
                <p class="text-gray-300 text-base">
                  Soft jazz for all your activities.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002a461b85872ea87bb0de00128"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Piano in the Background
                </a>
                <p class="text-gray-300 text-base">
                  A calm piano soundtrack to all activities.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000028ed1a5002b96c2ea882541b2"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Peaceful Guitar
                </a>
                <p class="text-gray-300 text-base">
                  Unwind to these calm classical guitar pieces.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002e4eadd417a05b2546e866934"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Deep Focus
                </a>
                <p class="text-gray-300 text-base">
                  Keep calm and focus with ambient and post-rock music.
                </p>
              </article>
            </div>
          </section>

          <section class="mt-6">
            <div class="flex items-center justify-between font-bold mb-8">
              <div>
                <a
                  class="text-2xl text-white block hover:underline cursor-pointer"
                  >Mood</a
                >

                <p class="text-gray-300 font-normal text-sm">
                  Playlists to match your mood.
                </p>
              </div>
              <a
                class="uppercase text-base text-gray-400 block hover:underline cursor-pointer"
                >See all</a
              >
            </div>

            <div
              class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 gap-6"
            >
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002a4d88b5a7739e902775ccf99"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  悲傷釋放
                </a>
                <p class="text-gray-300 text-base">
                  在音樂的懷抱裡，你想哭就哭。 那天堂是 我爱過你的地方。
                </p>
              </article>
              <article
                class="bg-gray-500 rounded-md hover:bg-gray-400 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000025d1f50822b6d2a31b1fb3177"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white"
                  >少年时代</a
                >
                <p class="text-gray-300 text-base">
                  这是我门的少年配乐。学生时代的稚气、情窦初开的犹豫、单纯无瑕的友谊...每一首歌，都能带起一串青涩的回忆。
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002bd0e19e810bb4b55ab164a95"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Mood Booster
                </a>
                <p class="text-gray-300 text-base">
                  Get happy with today's dose of feel-good songs!
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000025af1070c80cd50dbbb4cfa19"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Happy Hits!
                </a>
                <p class="text-gray-300 text-base">
                  Hits to boost your mood and fill you with happiness!
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000028fc4fda51389e295befb4291"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Jiwang Kapak
                </a>
                <p class="text-gray-300 text-base">
                  Ku terkenang masa kita bersama.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002e126204e60890db835d406a6"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Good Times
                </a>
                <p class="text-gray-300 text-base">
                  The happiest hits to boost your day.
                </p>
              </article>
            </div>
          </section>

          <section class="mt-6">
            <div class="flex items-center justify-between font-bold mb-8">
              <a
                class="text-2xl text-white block hover:underline cursor-pointer"
                >Popular new Releases</a
              >

              <a
                class="uppercase text-base text-gray-400 block hover:underline cursor-pointer"
                >See all</a
              >
            </div>

            <div
              class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 gap-6"
            >
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f0000000247a1563ef5b00bf289f69dab"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  New Music Friday Singapore
                </a>
                <p class="text-gray-300 text-base">
                  The best newly released songs of the week. Cover: Camila
                  Cabello, Ed Sheeran
                </p>
              </article>
              <article
                class="bg-gray-500 rounded-md hover:bg-gray-400 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67616d00001e029cfb46c241db4f89bd648f85"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white"
                  >Trampoline (feat. Missy Elliott, BIA and Doechii)</a
                >
                <p class="text-gray-300 text-base">
                  <a href="#" class="hover:underline">David Guetta, </a>
                  <a href="#" class="hover:underline">Afrojack, </a>
                  <a href="#" class="hover:underline">Missy Elliott</a>
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67616d00001e02e1b6a49e03e13939383c1e6c"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Hello World
                </a>
                <p class="text-gray-300 text-base">
                  <a href="#" class="hover:underline">Alan Walker, </a>
                  <a href="#" class="hover:underline">Torine</a>
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67616d00001e02dd22d7c43aa6aa2593829d48"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Payback (feat. Icona Pop)
                </a>
                <p class="text-gray-300 text-base">
                  <a href="#" class="hover:underline">Cheat Codes, </a>
                  <a href="#" class="hover:underline">Icona Pop</a>
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67616d00001e0271f90288b6ef8d6f5884da79"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  WTSGD (with Alessia Cara)
                </a>
                <p class="text-gray-300 text-base">
                  <a href="#" class="hover:underline">CLAY, </a>
                  <a href="#" class="hover:underline">Alessia Cara</a>
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67616d00001e027d4ee9a7b3b6a4fb345b44e9"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Forgive Me
                </a>
                <p class="text-gray-300 text-base">
                  <a href="#" class="hover:underline">Sofi Tukker, </a>
                  <a href="#" class="hover:underline">Mahmut Orhan</a>
                </p>
              </article>
            </div>
          </section>

          <section class="mt-6">
            <div class="flex items-center justify-between font-bold mb-8">
              <a
                class="text-2xl text-white block hover:underline cursor-pointer"
                >Tuesday's gone with the wind</a
              >

              <a
                class="uppercase text-base text-gray-400 block hover:underline cursor-pointer"
                >See all</a
              >
            </div>

            <div
              class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 gap-6"
            >
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002e537d60cfc7ef6f5d2a5781a"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  It's a Hit!
                </a>
                <p class="text-gray-300 text-base">
                  The hottest songs you need to listen to right now. Cover:
                  Camila Cabello, Ed Sheeran
                </p>
              </article>
              <article
                class="bg-gray-500 rounded-md hover:bg-gray-400 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000025af1070c80cd50dbbb4cfa19"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white"
                  >Happy Hits!</a
                >
                <p class="text-gray-300 text-base">
                  Hits to boost your mood and fill you with happiness!
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002acaeb13e920b227f822acac2"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  最Hit華語榜
                </a>
                <p class="text-gray-300 text-base">
                  最新最 HITO 的華語流行歌曲就在這立即收聽！Cover: 周興哲 (Eric
                  Chou)
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002a66d7f79d3e1cc22caa5d7b6"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Garden Essentials
                </a>
                <p class="text-gray-300 text-base">
                  Artists and tracks that define Singapore; The Garden State.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000023462a4dbc851cd106d16491c"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Jazz Vibes
                </a>
                <p class="text-gray-300 text-base">
                  The original chill instrumental beats playlist.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f0000000217da49cad7db24acc4137404"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Causeway Trends
                </a>
                <p class="text-gray-300 text-base">
                  Trending tracks on both sides of the Causeway. Cover: Em
                  Beihold
                </p>
              </article>
            </div>
          </section>

          <section class="mt-6">
            <div class="flex items-center justify-between font-bold mb-8">
              <a
                class="text-2xl text-white block hover:underline cursor-pointer"
                >Soundtrack your home</a
              >

              <a
                class="uppercase text-base text-gray-400 block hover:underline cursor-pointer"
                >See all</a
              >
            </div>

            <div
              class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 gap-6"
            >
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000020627aa4e768cab5aaa0d4753"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Workspace
                </a>
                <p class="text-gray-300 text-base">
                  Soundtrack your workspace with this workday mixtape. i'm
                  tired.
                </p>
              </article>
              <article
                class="bg-gray-500 rounded-md hover:bg-gray-400 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000029ed927af72b644ee065cc980"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white"
                  >Work From Home</a
                >
                <p class="text-gray-300 text-base">
                  Clock in from the comfort of your own home with 8 hours of
                  music to carry you through the day.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000027cd8e0a374e7f43c04a16d95"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  上班輕聽
                </a>
                <p class="text-gray-300 text-base">
                  上班時間很長，就讓最新最動聽的國語歌陪你，舒服輕聽一起渡過吧！
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f0000000219de272c0d8d2d7167883873"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Chill Lah
                </a>
                <p class="text-gray-300 text-base">
                  Sit back and unwind to the most selamba songs around.
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f00000002c8114f56f99e3a37159595f6"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  lofi beats
                </a>
                <p class="text-gray-300 text-base">
                  Fly as a kite with beats to chill, relax, study, code, focus,
                  and sleep... 🪁
                </p>
              </article>
              <article
                class="rounded-md bg-gray-600 hover:bg-gray-500 px-4 py-4"
              >
                <img
                  src="https://i.scdn.co/image/ab67706f000000029a5ee6ffeed4ca86f805f47e"
                  alt=""
                  class="w-full rounded-md"
                />
                <a href="#" class="font-semibold text-lg mt-3 block text-white">
                  Light & Easy
                </a>
                <p class="text-gray-300 text-base">
                  The breeziest songs to get you through the day.
                </p>
              </article>
            </div>
          </section>
        </div>
      </main>
    </div>

    <footer
      class="h-32 md:h-24 w-full absolute bottom-0 left-0 bg-gradient-to-br from-indigo-800 to-pink-500 text-white px-4 py-2"
    >
      <h3 class="tracking-wider uppercase font-semibold text-sm">
        Preview of Spotify
      </h3>

      <div class="flex flex-col md:flex-row items-center justify-between">
        <p class="font-semibold w-full lg:w-3/5">
          Sign up to get unlimited songs and podcasts with occasional ads. No
          credit card needed
        </p>
        <div class="mt-2 lg:mt-0 w-full lg:w-2/5 text-center md:text-right">
          <button
            class="w-52 font-semibold rounded-full bg-white px-6 py-2 text-blue-500 uppercase hover:scale-105 md:mr-8"
          >
            Sign Up Free
          </button>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {}
</script>
<style></style>
