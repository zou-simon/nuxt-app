<template>
    <main class="md:grid md:grid-rows-3 md:grid-cols-4 md:grid-flow-col md:gap-4 md:min-h-screen p-4 pb-2 md:pb-4">
        <Head>
            <Title>Tokyo Yaki</Title>
        </Head>
        <div class="flex flex-col md:row-span-3 md:col-span-2 bg-center bg-cover md:grid md:content-evenly place-items-center p-4 mb-4 md:mb-0" id="bg-devanture">
            <div class="text-center mb-4">
                <h1 class="text-5xl md:text-7xl font-black uppercase">Tokyo Yaki</h1>
                <p class="text-md md:text-xl font-light tracking-wider">Restaurant Japonais</p>
            </div>

            <a href="https://maps.google.com/?q=Tokyo+Yaki+75020"
                class="uppercase bg-white text-black font-bold text-center border-4 border-black py-2 px-4 md:w-1/2 hover:bg-neutral-300">
                Y&nbsp;aller
            </a>
        </div>
        <div class="md:row-span-2 md:col-span-2 bg-primary p-4 md:p-8">
            <h2 class="text-xl md:text-2xl uppercase font-bold tracking-wider mb-1">À propos</h2>
            <div class="sm:text-lg md:text-xl lg:text-2xl space-y-6">
                <div>
                    <p>
                        253 Rue des Pyrénées, 75020 Paris
                    </p>
                    <a href="tel:+33143150371" class="hover:text-neutral-300 hover:underline">
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
                        Livraison dans le 20e à partir de 15 €
                    </p>
                    <p class="text-red-500">
                        -10% à emporter sauf les desserts et boissons
                    </p>
                </div>
            </div>
        </div>
        <div class="sticky md:static bottom-2 flex md:col-span-2 space-x-2 md:space-x-4 my-2 md:my-0">
            <NuxtLink to="#"
                activeClass="w-full group grid md:content-center md:justify-center md:bg-center md:bg-cover md:bg-primary md:bg-no-repeat hover:bg-contain" id="bg-chirashi">
                <span
                    class="uppercase bg-white text-black font-bold w-full md:w-auto text-center md:border-4 md:border-black p-2 md:py-3 md:px-6 group-hover:bg-neutral-300">
                    Commander
                </span>
            </NuxtLink>
            <NuxtLink to="#"
                activeClass="w-full group grid md:content-center md:justify-center md:bg-center md:bg-cover md:bg-primary md:bg-no-repeat hover:bg-contain" id="bg-brochettes">
                <span
                    class="uppercase bg-white text-black font-bold w-full md:w-auto text-center md:border-4 md:border-black p-2 md:py-3 md:px-6 group-hover:bg-neutral-300">
                    Menu
                </span>
            </NuxtLink>
        </div>
    </main>
</template>