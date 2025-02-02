<template>
    <section class="max-w-md mx-auto mt-24">
        <div class="w-full bg-white rounded-lg md:mt-0 sm:max-w-md xl:p-0">
            <div class="p-6 space-y-4 md:space-y-6 sm:p-8">

                <div class="logo">
                    <img src="../assets/logo.jpg" alt="Vue Tailwind Logo" class="w-20 h-20 mx-auto">
                </div>

                <h1 class="text-xl font-bold leading-tight tracking-tight text-gray-900 md:text-2xl">Create an
                    account
                </h1>
                <form class="space-y-4 md:space-y-6" method="POST">
                    <div>
                        <label for="name" class="block text-gray-700 font-bold mb-2">Your full name</label>
                        <input type="text" name="name" id="name" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5" placeholder="Emelia Erickson" required>
                    </div>
                    <div>
                        <label for="username" class="block text-gray-700 font-bold mb-2">Username</label>
                        <input type="text" name="username" id="username" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5" placeholder="emelia_erickson24" required>
                    </div>
                    <div>
                        <label for="password" class="block text-gray-700 font-bold mb-2">Password</label>
                        <input type="password" name="password" id="password" placeholder="••••••••" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5" required>
                    </div>
                    <button type="submit" class="inline-block py-4 px-8 leading-none text-white bg-slate-800 hover:bg-blue-500 rounded shadow text-sm font-bold">Create an account</button>
                    <p class="text-sm font-light text-gray-500">Already have an account? <a
                        class="font-medium text-blue-600 hover:underline" href="/login">Sign in here</a>
                    </p>
                </form>
            </div>
        </div>
    </section>
</template>


<script>
export default {
  name: 'SignupForm'
}
</script>

<style scoped>

</style>