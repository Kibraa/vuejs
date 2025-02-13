<template>
    <main class="flex justify-center items-center min-h-screen bg-gray-900">
        <section>
            <form class="bg-gray-800 p-8 rounded-lg shadow-2xl space-y-6 w-96">
                <h2 class="text-center text-green-400 text-2xl font-bold">Connexion</h2>

                <div>
                    <label for="email" class="block text-gray-300 mb-2">Adresse Email</label>
                    <input type="email" id="email" name="email" placeholder="Entrez votre email" 
                        class="w-full p-3 bg-gray-700 text-white rounded-md focus:ring-2 focus:ring-green-400 outline-none transition" required>
                </div>

                <div>
                    <label for="password" class="block text-gray-300 mb-2">Mot de Passe</label>
                    <input type="password" id="password" name="password" placeholder="Entrez votre mot de passe" 
                        class="w-full p-3 bg-gray-700 text-white rounded-md focus:ring-2 focus:ring-green-400 outline-none transition" required>
                </div>

                <div class="flex gap-4">
                    <button type="submit" class="w-full p-3 bg-green-500 text-white rounded-md hover:bg-green-400 transition">
                        Se Connecter
                    </button>
                    <button type="reset" class="w-full p-3 bg-red-500 text-white rounded-md hover:bg-red-400 transition">
                        Annuler
                    </button>
                </div>

                <p class="text-center text-gray-400 text-sm">
                    Pas encore de compte ? <a href="#" class="text-green-400 hover:underline">Inscrivez-vous</a>
                </p>
            </form>
        </section>
    </main>
</template>