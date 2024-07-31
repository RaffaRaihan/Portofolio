<template>
    <section class="main mx-[100px] flex justify-between">
        <div class="container w-[50%] mt-[67px] mb-[20px]">
            <h2 class="text-5xl font-bold text-stone-700">Hi, I'm <span class="text-purple-400">Raffa Raihan</span></h2>
            <h3 class="mt-[12px] text-[32px] font-semibold text-stone-700">Frontend Developer</h3>
            <p class="mt-[10px] mb-[30px] font-normal">Frontend merupakan salah satu bagian dari website yang 
                menampilkan tampilan untuk para pengguna. Pada bagian ini 
                dibuat dengan menggunakan 3 bahasa pemrograman web yaitu HyperText Markup Language (HTML), Cascading Style 
                Sheets (CSS), dan JavaScript.</p>
            <div class="flex gap-[20px]">
                <ButtonHire />
                <ButtonProject />
            </div>
            <Sosmed />
        </div>
        <div class="hero">
            <img class="w-[350px] h-auto rounded-[16px] border border-black" src="../assets/img/hero.jpg" alt="me">
        </div>
    </section>
</template>