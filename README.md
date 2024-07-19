- 👋 Hi, I’m @swa555
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - Personal Communication Website</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900">
    <header class="bg-blue-600 text-white p-4">
        <nav class="container mx-auto flex justify-between">
            <a href="index.html" class="text-xl font-bold">Home</a>
            <div>
                <a href="about.html" class="mx-2">About</a>
                <a href="contact.html" class="mx-2">Contact</a>
            </div>
        </nav>
    </header>
    <main class="container mx-auto p-4">
        <section class="max-w-md mx-auto bg-white p-6 rounded shadow-md">
            <h1 class="text-2xl font-bold mb-4">Contact Me</h1>
            <form id="contactForm">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700">Name</label>
                    <input type="text" id="name" class="w-full p-2 border border-gray-300 rounded mt-1">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700">Email</label>
                    <input type="email" id="email" class="w-full p-2 border border-gray-300 rounded mt-1">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700">Message</label>
                    <textarea id="message" class="w-full p-2 border border-gray-300 rounded mt-1"></textarea>
                </div>
                <button type="submit" class="w-full bg-blue-600 text-white p-2 rounded">Send</button>
            </form>
        </section>
    </main>
    <footer class="bg-blue-600 text-white text-center p-4">
        &copy; 2024 Personal Communication Website. All rights reserved.
    </footer>
    <script src="scripts.js"></script>
</body>
</html>


<!---
swa555/swa555 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
