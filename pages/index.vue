<template>
    <div id="container" class="container mx-auto px-8 py-4">
        <section id="banner" class="bg-black text-white rounded-xl items-center justify-center font-montserrat p-3">
            <p class="text-center">Web aplikasi masih dalam tahap pengembangan - <span class="underline">pelajari lebih
                    lanjut</span></p>
        </section>
        <section id="hero"
            class="bg-black h-[700px] rounded-3xl bg-[url(/img/background.png)] bg-cover bg-center flex flex-col gap-4 items-center mt-4 px-12">
            <div class="bg-white rounded-lg w-full mt-7 p-3 flex items-center justify-between">
                <div class="flex items-center gap-12">
                    <p class="font-montserrat font-bold uppercase text-[#005696] text-lg border-r-2 pe-6 tracking-wide">U | Harassment</p>
                    <p class="font-montserrat font-semibold -ms-6 text-[#005696] tracking">Produk</p>
                    <p class="font-montserrat font-semibold text-[#005696] tracking">Fitur</p>
                    <p class="font-montserrat font-semibold text-[#005696] tracking">Kontak</p>
                </div>
                <div class="font-montserrat shadow-md rounded-lg py-1 px-3 text-md font-medium border-[1px] border-gray-100">Talk to developer</div>
            </div>
            <div class="flex flex-col gap-4 items-center justify-center px-40 mt-24">
                <p class="text-white font-montserrat font-semibold text-6xl text-center">U-Tapis Sistem Online
                    Pendeteksi
                    Penghinaan dan Pencemaran Nama Baik</p>
                <p class="text-center text-lg font-montserrat font-semibold px-40 text-white opacity-90">Deteksi
                    kejahatan
                    siber secara gratis, aman, dan cepat. Hindari normalisasi kejahatan, sigap melapor demi Indonesia
                    yang
                    merdeka.</p>
                <div class="flex gap-3">
                    <div
                        class="bg-[#4497E7] z-20 text-white p-3 rounded-2xl font-montserrat font-medium cursor-pointer">
                        Tentang Kami</div>
                    <div class="bg-white text-gray-600 p-3 rounded-2xl font-montserrat font-medium cursor-pointer">
                        Mengapa
                        U-Tapis</div>
                </div>
            </div>
        </section>
        <section id="input"
            class="mx-72 rounded-xl flex flex-col bg-white p-5 -mt-36 gap-5 border-[3px] border-gray-100">
            <div class="flex justify-between items-center">
                <p class="font-montserrat font-semibold">Deteksi Teks</p>
                <div class="text-gray-600 border-2 border-gray-200 flex items-center justify-center rounded-md p-1">
                    <Icon name="icon-park-outline:more" size="18" />
                </div>
            </div>
            <hr class="h-[2px] bg-gray-200 border-0">
            <textarea placeholder="Masukkan teks disini..."
                class="w-full rounded-xl p-3 text-gray-700 font-medium font-montserrat focus:outline-none focus:ring-2 focus:ring-[#2A70CE] transition duration-200 h-44 resize-none"></textarea>
            <div class="flex justify-between items-center">
                <div class="flex gap-3 text-gray-600">
                    <Icon name="fluent:arrow-reset-24-filled" size="18" />
                    <Icon name="tabler:copy" size="18" />
                </div>
                <div
                    class="bg-gradient-to-r from-[#2A70CE] to-[#4497E7] text-white p-3 shadow-md rounded-md font-semibold text-sm flex items-center justify-center gap-2">
                    <Icon name="fluent:sparkle-32-filled" size="18" />
                    <p>
                        Mulai Deteksi
                    </p>
                </div>
            </div>
        </section>
        <section id="support" class="flex flex-col">
            <p class="font-montserrat font-semibold text-xl text-gray-500 mt-24 text-center">Mendapatkan kepercayaan,
                dukungan penuh, dan <br> kolaborasi berkelanjutan dari</p>
            <div class="flex items-center justify-center gap-20">
                <img class="w-44"
                    src="https://seeklogo.com/images/U/universitas-multimedia-nusantara-umn-logo-6F686AD356-seeklogo.com.png"
                    alt="">
                <img class="w-44"
                    src="https://res.cloudinary.com/tia-img/image/fetch/t_company_avatar/https%3A%2F%2Fcdn.techinasia.com%2Fdata%2Fimages%2F06bef4f5fa8a57fb06b24429dba20da1.png"
                    alt="">
            </div>
        </section>
        <section id="why" class="flex flex-col mt-20 gap-5">
            <p class="font-montserrat text-4xl font-semibold text-center">Mengapa U-Tapis Harassment?</p>
            <p class="font-montserrat font-semibold text-xl text-gray-500 text-center">Didesain sebagai pelopor
                otomatisasi dalam dunia Jurnalistik, U-Tapis menjawab <br> kebutuhan berbagai instansi penegak hukum di
                Indonesia.</p>
            <div class="grid grid-cols-3 gap-5 mx-48 mt-10">
                <div
                    class="bg-white rounded-xl p-5 flex flex-col items-center gap-3 shadow-lg border-[3px] border-gray-100">
                    <Icon name="fluent:shield-24-filled" size="32" />
                    <p class="font-montserrat font-semibold text-lg">Keamanan</p>
                    <p class="text-gray-500 text-center">Dengan U-Tapis, Anda dapat memastikan keamanan digital dan
                        melindungi reputasi Anda dari konten yang merugikan.</p>
                </div>
                <div
                    class="bg-white rounded-xl p-5 flex flex-col items-center gap-3 shadow-lg border-[3px] border-gray-100">
                    <Icon name="fluent:sparkle-24-filled" size="32" />
                    <p class="font-montserrat font-semibold text-lg">Akurasi</p>
                    <p class="text-gray-500 text-center">U-Tapis menggunakan teknologi AI terkini untuk mendeteksi
                        konten yang mengandung penghinaan atau pencemaran nama baik secara akurat.</p>
                </div>
                <div
                    class="bg-white rounded-xl p-5 flex flex-col items-center gap-3 shadow-lg border-[3px] border-gray-100">
                    <Icon name="icon-park-solid:speed" size="32" />
                    <p class="font-montserrat font-semibold text-lg">Kecepatan</p>
                    <p class="text-gray-500 text-center">Dengan U-Tapis, Anda dapat mendeteksi konten yang merugikan
                        dalam hitungan detik, memastikan langkah hukum yang cepat dan tepat.</p>
                </div>
            </div>
        </section>
        <section
            id="footer"
        >
            <div class="flex items-center justify-center gap-5 mt-20">
                <img class="w-44"
                    src="https://seeklogo.com/images/U/universitas-multimedia-nusantara-umn-logo-6F686AD356-seeklogo.com.png"
                    alt="">
                <img class="w-44"
                    src="https://res.cloudinary.com/tia-img/image/fetch/t_company_avatar/https%3A%2F%2Fcdn.techinasia.com%2Fdata%2Fimages%2F06bef4f5fa8a57fb06b24429dba20da1.png"
                    alt="">
            </div>
            <div class="flex items-center justify-center gap-5 mt-10">
                <p class="font-montserrat font-semibold text-gray-500">© 2025 U-Tapis</p>
                <p class="font-montserrat font-semibold text-gray-500">Kebijakan Privasi</p>
                <p class="font-montserrat font-semibold text-gray-500">Syarat dan Ketentuan</p>
            </div>
        </section>
    </div>
</template>