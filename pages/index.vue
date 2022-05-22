<template>
    <div class="grid lg:grid-rows-3 lg:grid-flow-row gap-4 xs:gap-6 p-4 xs:p-6 h-screen">
        <div class="sm:col-span-2 md:col-span-1 row-span-5 lg:row-span-4 rounded-lg bg-center bg-cover grid content-evenly place-items-center p-4"
            style="background-image: url('/assets/devanture.jpg')">
            <div class="text-center">
                <h1 class="text-5xl md:text-7xl font-black uppercase">Tokyo Yaki</h1>
                <p class="text-md md:text-xl font-light tracking-wider">Restaurant Japonais</p>
            </div>

            <a href="https://maps.google.com/?q=Tokyo+Yaki+75020"
                class="uppercase bg-white text-black font-bold rounded-full text-center py-2 w-1/2 hover:scale-105 transition delay-100 duration-300 ease-in-out">
                Y aller
            </a>
        </div>
        <div class="sm:col-span-2 lg:row-span-2 rounded-lg bg-primary p-4 sm:p-6 md:p-8">
            <h2 class="text-2xl uppercase font-bold tracking-wider">À propos</h2>
            <div class="sm:text-lg md:text-xl lg:text-2xl space-y-6">
                <div>
                    <p>
                        253 Rue des Pyrénées, 75020 Paris
                    </p>
                    <a href="tel:+33143150371" class="hover:text-neutral-300">
                        +33 1 43 15 03 71
                    </a>
                </div>
                <div>
                    <p>
                        Ouvert tous les jours sauf dimanche midi
                    </p>
                    <p>Midi : 11h30 - 14h30</p>
                    <p>Soir : 18h30 - 23h00</p>
                </div>
                <div>
                    <p>
                        Livraison à partir de 15 €
                    </p>
                    <p class="text-red-500">
                        -10% à emporter sauf les desserts et boissons
                    </p>
                </div>
            </div>
        </div>
        <div class="sm:col-auto sm:row-span-2 md:row-span-4 lg:row-span-2 rounded-lg bg-primary grid content-center justify-items-center p-4">
            <a href="#"
                class="uppercase bg-white text-black font-bold rounded-full text-center p-2 w-3/4 hover:scale-105 transition delay-100 duration-300 ease-in-out">
                Commander
            </a>
        </div>
        <div class="sm:col-auto sm:row-span-2 md:row-span-4 lg:row-span-2 rounded-lg bg-primary grid content-center justify-items-center p-4">
            <a href="#"
                class="uppercase bg-white text-black font-bold rounded-full text-center p-2 w-3/4 hover:scale-105 transition delay-100 duration-300 ease-in-out">
                Menu
            </a>
        </div>
        <footer class="sm:col-span-2 md:col-span-3 rounded-lg bg-neutral-900 xs:text-center p-4">
            <a href="" class="hover:text-neutral-300">Mentions Légales</a>
            <p class="text-neutral-400">Copyright © {{ new Date().getFullYear() }} ZUL SAS. Tous droits réservés.</p>
        </footer>
    </div>
</template>