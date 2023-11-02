<template>
  <div>
    <header>
      <div class="overflow-hidden bg-blue-950 relative">
        <img class="h-32 float-left mt-5 mb-5 ml-7 mr-5" src="./assets/images/chelseaLogo.png" />
        <h1 class="text-4xl font-bold text-[#a88e44] mt-12">CHELSEA FOOTBALL CLUB</h1>
        <h1 class="text-2xl font-semibold text-[#a88e44]">FANBASE</h1>
        <img class="h-32 absolute right-8 top-5" src="./assets/images/mascotlogo.png" />
      </div>

      <div class="bg-[#a88e44] flex justify-evenly h-12 pt-3 font-bold text-white text-base">
        <NuxtLink to="/Home">BERANDA</NuxtLink>
        <NuxtLink to="/News">BERITA</NuxtLink>
        <NuxtLink to="/Highlights">CUPLIKAN</NuxtLink>
        <NuxtLink to="/Schedule">JADWAL PERTANDINGAN</NuxtLink>
      </div>
    </header>

    <main>
      <NuxtPage />
    </main>

    <footer>
      <section class="bg-blue-950 h-full">
            <div class="overflow-hidden mb-10">
                <img class="h-20 ml-16 float-left mt-10" src="./assets/images/chelseaLogo.png" />
                <img class="h-20 mr-16 float-right mt-10" src="./assets/images/f1.png" />
                <img class="h-20 mr-10 float-right mt-10" src="./assets/images/f2.png" />

            </div>

            <div class="flex flex-wrap gap-x-60 mb-16">
                <div class="ml-20">
                    <h3 class="font-bold text-lg text-white mb-9" >CHELSEA FANBASE</h3>

                    <nav>
                        <ul class="text-base text-white font-semibold">
                            <li><NuxtLink to="/">Gowa</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Jalan Poros Malino</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Sulawesi Selatan</NuxtLink></li>
                        </ul>
                    </nav>
                </div>

                <div class="ml-9">
                    <h3 class="font-bold text-lg text-white mb-9" >TENTANG</h3>

                    <nav class="">
                        <ul class="text-base text-white font-semibold">
                            <li><NuxtLink to="https://www.chelseafc.com/en/about-the-club">Tentang Club</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Kontak Kami</NuxtLink></li><br/>
                        </ul>
                    </nav>
                </div>

                <div class="ml-9">
                    <h3 class="font-bold text-lg text-white mb-9">DIDUKUNG OLEH</h3>
                    <div class="flex flex-wrap gap-3" >
                        <img class="h-24" src="./assets/images/conan.png" />
                        <img class="h-24" src="./assets/images/giyu.png" />
                        <img class="h-24" src="./assets/images/geto.png" />
                    </div>
                </div>
            </div>

            <div class="flex flex-row gap-10">
                <div class="flex flex-wrap gap-x-5 ml-20 pb-5">
                    <NuxtLink to="https://www.facebook.com/ChelseaFC/" target="_blank"><img class="h-5" src="./assets/images/fb.png" /></NuxtLink>
                    <NuxtLink to="https://twitter.com/chelseafc" target="_blank"><img class="h-5" src="./assets/images/twitter.png" /></NuxtLink>
                    <NuxtLink to="https://www.instagram.com/chelseafc/" target="_blank"><img class="h-5" src="./assets/images/ig.png" /></NuxtLink>
                    <NuxtLink to="https://www.youtube.com/chelseafc" target="_blank"><img class="h-5" src="./assets/images/yt.png" /></NuxtLink>
                </div>

                <div>
                    <p class="font-semibold text-white text-sm">© 2023 Chelsea Football Club Fanbase</p>
                </div>
            </div>

        </section>
    </footer>
  </div>
</template>
