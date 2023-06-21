<script setup>
</script>

<template>
    <main class="pt-20 max-w-6xl mx-auto">
        <section class="flex items-center gap-x-4 sm:gap-x-20 py-10 justify-center md:justify-normal flex-col sm:flex-row">
            <h2 class="text-blue-700 font-bold text-7xl max-w-6xl pb-4">Peliculas</h2>
            <div class="flex sm:gap-x-4 flex-col sm:flex-row">
                <p class="text-lg font-semibold underline underline-offset-8 decoration-pink-500 decoration-4 pb-5 sm:pb-0">En Cartelera
                </p>
                <p class="text-lg font-semibold">Proximos Estrenos</p>
            </div>
        </section>
        <section class="flex">
            <aside class="w-1/3 ps-5 sm:ps-20">
                <p class="text-lg font-bold mb-6">Ciudad</p>
                <ul class="flex flex-col gap-y-6 font-semibold">
                    <li><a href="#">Lima</a></li>
                    <li><a href="#">Arequipa</a></li>
                    <li><a href="#">Cajamarca</a></li>
                    <li><a href="#">Chiclayo</a></li>
                    <li><a href="#">Cusco</a></li>
                    <li><a href="#">Huancayo</a></li>
                    <li><a href="#">Huanuco</a></li>
                    <li><a href="#">Juliaca</a></li>
                    <li><a href="#">Piura</a></li>
                    <li><a href="#">Pucallpa</a></li>
                    <li><a href="#">Puno</a></li>
                    <li><a href="#">Tacna</a></li>
                    <li><a href="#">Trujillo</a></li>
                    <li><a href="#">Lima</a></li>
                </ul>
            </aside>
            <section class="w-2/3 ">
                <main class=" grid grid-cols-1 sm:grid-cols-2 gap-5 me-10 lg:grid-cols-3 lg:me-0 ">
                    <div class="">
                        <div class="relative hover:-translate-y-1">
                            <img src="../assets/HO00001697.jfif" alt="">
                            <div
                                class="absolute h-full w-full top-0 flex justify-center items-center gap-3 text-white font-semibold opacity-0 hover:opacity-100 hover:shadow-black shadow-lg">
                                <button class="bg-pink-600 py-1 px-2 rounded-xl hover:bg-pink-700">Comprar</button>
                                <button class="bg-blue-600 py-1 px-2 rounded-xl hover:bg-blue-700">Ver detalle</button>
                            </div>
                        </div>
                        <h3 class="font-semibold text-xl py-2">Boogeyman: Tu miedo es real</h3>
                        <p>Terror, 1h 40min, +14.</p>
                    </div>
                    <div>
                        <div class="relative hover:-translate-y-1">
                            <img src="../assets/HO00001613.jfif" alt="">
                            <div
                                class="absolute h-full w-full top-0 flex justify-center items-center gap-3 text-white font-semibold opacity-0 hover:opacity-100 hover:shadow-black shadow-lg">
                                <button class="bg-pink-600 py-1 px-2 rounded-xl hover:bg-pink-700">Comprar</button>
                                <button class="bg-blue-600 py-1 px-2 rounded-xl hover:bg-blue-700">Ver detalle</button>
                            </div>
                        </div>
                        <h3 class="font-semibold text-xl py-2">Cuando Ellas Quieren Mas</h3>
                        <p>Comedia, 1h 50min, +14.</p>
                    </div>
                    <div>
                        <div class="relative hover:-translate-y-1">
                            <img src="../assets/HO00001672.jfif" alt="">
                            <div
                                class="absolute h-full w-full top-0 flex justify-center items-center gap-3 text-white font-semibold opacity-0 hover:opacity-100 hover:shadow-black shadow-lg">
                                <button class="bg-pink-600 py-1 px-2 rounded-xl hover:bg-pink-700">Comprar</button>
                                <button class="bg-blue-600 py-1 px-2 rounded-xl hover:bg-blue-700">Ver detalle</button>
                            </div>
                        </div>
                        <h3 class="font-semibold text-xl py-2">EO</h3>
                        <p>Drama, 1h 26min, +14.</p>
                    </div>
                    <div>
                        <div class="relative hover:-translate-y-1">
                            <img src="../assets/HO00001564.jfif" alt="">
                            <div
                                class="absolute h-full w-full top-0 flex justify-center items-center gap-3 text-white font-semibold opacity-0 hover:opacity-100 hover:shadow-black shadow-lg">
                                <button class="bg-pink-600 py-1 px-2 rounded-xl hover:bg-pink-700">Comprar</button>
                                <button class="bg-blue-600 py-1 px-2 rounded-xl hover:bg-blue-700">Ver detalle</button>
                            </div>
                        </div>
                        <h3 class="font-semibold text-xl py-2">Guardian de las Galaxias VOL.3</h3>
                        <p>Accion, 2h 30min, APT.</p>
                    </div>
                    <div>
                        <div class="relative hover:-translate-y-1">
                            <img src="../assets/HO00001565.jfif" alt="">
                            <div
                                class="absolute h-full w-full top-0 flex justify-center items-center gap-3 text-white font-semibold opacity-0 hover:opacity-100 hover:shadow-black shadow-lg">
                                <button class="bg-pink-600 py-1 px-2 rounded-xl hover:bg-pink-700">Comprar</button>
                                <button class="bg-blue-600 py-1 px-2 rounded-xl hover:bg-blue-700">Ver detalle</button>
                            </div>
                        </div>
                        <h3 class="font-semibold text-xl py-2">La Sirenita</h3>
                        <p>Fantasia, 2h 15min, APT.</p>
                    </div>
                    <div>
                        <div class="relative hover:-translate-y-1">
                            <img src="../assets/HO00001614.jfif" alt="">
                            <div
                                class="absolute h-full w-full top-0 flex justify-center items-center gap-3 text-white font-semibold opacity-0 hover:opacity-100 hover:shadow-black shadow-lg">
                                <button class="bg-pink-600 py-1 px-2 rounded-xl hover:bg-pink-700">Comprar</button>
                                <button class="bg-blue-600 py-1 px-2 rounded-xl hover:bg-blue-700">Ver detalle</button>
                            </div>
                        </div>
                        <h3 class="font-semibold text-xl py-2">Rapidos Y Furiosos X</h3>
                        <p>Accion, 2h 30min, +14.</p>
                    </div>

                </main>
            </section>
        </section>
    </main>
</template>

<style scoped ></style>