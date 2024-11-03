<template>
  <section class="flex flex-col mt-12 px-4"> <!-- Padding sisi kanan dan kiri -->
    <div class="max-md:max-w-full">
      <div class="mt-10">
        <h2 data-layername="whatToReadNext" class="text-4xl font-bold tracking-tighter leading-none text-left text-black">
          What to read next
        </h2>
      </div>
      <div class="flex gap-5 max-md:flex-col">
        <article class="flex flex-col w-[33%] max-md:ml-0 max-md:w-full mx-2"> <!-- Menambahkan margin horizontal -->
          <div class="flex flex-col grow items-start font-bold text-gray-800 max-md:mt-10">
            <div class="flex flex-col grow mt-20 text-gray-800 max-md:mt-10">
              <img loading="lazy" src="@/assets/images/blog/two-women-in-front-of-dry-erase-board-1181533.png" />
              <time datetime="2021-08-23" data-layername="byJohnDoeLAug232021"
                class="mt-8 text-sm font-medium leading-none text-amber-300">
                By <span class="text-amber-300">John Doe</span> l Aug 23, 2021
              </time>
              <h3 data-layername="aUxCaseStudyCreatingAStudiousEnvironmentForStudents"
                class="mt-4 text-3xl tracking-tighter leading-10">
                A UX Case Study Creating a Studious Environment for Students:
              </h3>
              <p data-layername="duisAuteIrureDolorInReprehenderitInVoluptateVelitEsseCillumDoloreEuFugiatNullaPariaturExcepteurSintOccaecatCupidatatNonProident"
                class="self-stretch mt-4 text-base leading-7 opacity-70">
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                Excepteur sint occaecat cupidatat non proident.
              </p>
            </div>
          </div>
        </article>

        <article class="flex flex-col w-[33%] max-md:ml-0 max-md:w-full mx-2"> <!-- Menambahkan margin horizontal -->
          <div class="flex flex-col grow mt-20 text-gray-800 max-md:mt-10">
            <img loading="lazy" src="@/assets/images/blog/photo-of-people-doing-handshakes-3183197.png" />
            <time datetime="2021-08-23" data-layername="byJohnDoeLAug232021"
              class="self-start mt-8 text-sm font-medium leading-none text-amber-300">
              By <span class="text-amber-300">John Doe</span> l Aug 23, 2021
            </time>
            <h3 data-layername="aUxCaseStudyCreatingAStudiousEnvironmentForStudents"
              class="self-start mt-4 text-3xl font-bold tracking-tighter leading-10">
              A UX Case Study Creating a Studious Environment for Students:
            </h3>
            <p data-layername="duisAuteIrureDolorInReprehenderitInVoluptateVelitEsseCillumDoloreEuFugiatNullaPariaturExcepteurSintOccaecatCupidatatNonProident"
              class="mt-4 text-base leading-7 opacity-70">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
              Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>

        <article class="flex flex-col w-[33%] max-md:ml-0 max-md:w-full mx-2"> <!-- Menambahkan margin horizontal -->
          <div class="flex flex-col grow mt-20 text-gray-800 max-md:mt-10">
            <img loading="lazy" src="@/assets/images/blog/photo-of-woman-looking-at-man-3183173.png" />
            <time datetime="2021-08-23" data-layername="byJohnDoeLAug232021"
              class="self-start mt-8 text-sm font-medium leading-none text-amber-300">
              By <span class="text-amber-300">John Doe</span> l Aug 23, 2021
            </time>
            <h3 data-layername="aUxCaseStudyCreatingAStudiousEnvironmentForStudents"
              class="self-start mt-4 text-3xl font-bold tracking-tighter leading-10">
              A UX Case Study Creating a Studious Environment for Students:
            </h3>
            <p data-layername="duisAuteIrureDolorInReprehenderitInVoluptateVelitEsseCillumDoloreEuFugiatNullaPariaturExcepteurSintOccaecatCupidatatNonProident"
              class="mt-4 text-base leading-7 opacity-70">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
              Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>
      </div>
    </div>
    <hr data-layername="divider"
      class="mt-16 w-full border border-solid opacity-30 bg-zinc-500 border-zinc-500 min-h-[1px] max-md:mt-10 max-md:max-w-full" />
  </section>
</template>