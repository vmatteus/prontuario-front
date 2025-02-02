<template>
    <div class="max-w-md mx-auto mt-24">

        <div class="p-4">
            <h1 class="text-2xl font-bold leading-tight tracking-tight text-gray-900">Sign in to your account</h1>
        </div>

        <form class="p-4">
            <div class="mb-4">
                <label for="email" class="block text-gray-700 font-bold mb-2">Email</label>
                <input type="email" id="email" name="email" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5" placeholder="Enter your email address">
            </div>
            <div class="mb-4">
                <label for="password" class="block text-gray-700 font-bold mb-2">Password</label>
                <input type="password" id="password" name="password" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5" placeholder="Enter your password">
            </div>
            <div class="flex items-center justify-between">
                <a href="#"
                    class="text-gray-500 hover:text-blue-500 focus:outline-none focus:underline transition duration-150 ease-in-out">Forgot
                    Password?</a>
                <a href="/signup"
                    class="text-blue-500 hover:text-blue-700 focus:outline-none focus:underline transition duration-150 ease-in-out">Create
                    an account</a>
                <button type="submit" class="inline-block py-4 px-8 leading-none text-white bg-slate-800 hover:bg-blue-500 rounded shadow text-sm font-bold">Submit</button>
            </div>
        </form>        
    </div>
</template>

<script>
export default {
  name: 'LoginForm'
}
</script>

<style scoped>

</style>