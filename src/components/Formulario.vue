<script setup></script>

<template>
    <div class="md:w-1/2">
        <h2 class="font-black text-3xl text-center">Seguimiento Pacientes</h2>

        <p class="text-lg mt-5 text-center mb-10">
            Añade pacientes y
            <span class="text-indigo-600 font-bold"> Adminístralos </span>
        </p>

        <form class="bg-white shadow-md rounded-lg py-10 px-5 mb-10">

            <div class="mb-5">
                <label for="mascota" class="block text-gray-700 uppercasefont-bold">
                    Nombre Mascota
                </label>


                <input id="mascota" type="text" placeholder="Nombre de la mascota"
                    class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
                </input>
            </div>

            <div class="mb-5">
                <label for="propietario" class="block text-gray-700 uppercasefont-bold">
                    Nombre propietario
                </label>

                <input id="propietario" type="text" placeholder="Nombre del propietario"
                    class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
                </input>
            </div>

            <div class="mb-5">
                <label for="email" class="block text-gray-700 uppercasefont-bold">
                    Email propietario
                </label>

                <input id="email" type="email" placeholder="Email del propietario"
                    class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
                </input>
            </div>

            <div class="mb-5">
                <label for="alta" class="block text-gray-700 uppercasefont-bold">
                    Fecha dado de alta
                </label>

                <input id="alta" type="date" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
                </input>
            </div>

            <div class="mb-5">
                <label for="sintomas" class="block text-gray-700 uppercasefont-bold">
                    Síntomas
                </label>

                <textarea id="sintomas" placeholder="Describe los síntomas"
                    class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md h-40">
                </textarea>
            </div>

            <input
            type="submit"
            class="bg-indigo-600 w-full p-3 text-white uppercase font-bold hover:bg-indigo-600 cursor-pointer transition-colors"
           value="Registrar paciente"
            />

        </form>
    </div>
</template>
