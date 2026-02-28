# InfoCard
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InfoCard-ইনফোকার্ড  </title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;600;700&display=swap');
        
        body {
            background-color: #050505;
            color: #e5e5e5;
            font-family: 'Hind Siliguri', sans-serif;
            scroll-behavior: smooth;
        }

        /* প্রিমিয়াম গ্রেডিয়েন্ট ব্যাকগ্রাউন্ড */
        .premium-bg {
            background: radial-gradient(circle at top right, #1a0a0a, #050505);
        }

        .video-card {
            background: #111;
            border: 1px solid #222;
            transition: all 0.4s ease;
        }

        .video-card:hover {
            border-color: #ef4444;
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(239, 68, 68, 0.1);
        }

        /* কাস্টম স্ক্রলবার */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #050505;
        }
        ::-webkit-scrollbar-thumb {
            background: #333;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #ef4444;
        }
    </style>
</head>
<body class="premium-bg">

    <nav class="fixed w-full z-50 bg-black/90 backdrop-blur-lg border-b border-white/5 px-8 py-4 flex justify-between items-center">
        <div class="text-2xl font-black tracking-tighter text-white uppercase">
            Info<span class="text-red-600">Card</span>
        </div>
        
        <div class="hidden md:flex items-center gap-8 font-medium">
            <a href="#home" class="hover:text-red-500 transition">হোম</a>
            <a href="#docs" class="hover:text-red-500 transition">ডকুমেন্টারি</a>
            <a href="#team" class="hover:text-red-500 transition">টিম</a>
            <a href="#contact" class="hover:text-red-500 transition">যোগাযোগ</a>
        </div>

        <div class="flex items-center gap-5">
            <a href="https://facebook.com/facebook.com/share/1KvdUtziAE" target="_blank" class="text-xl text-blue-500 hover:text-white transition">
                <i class="fab fa-facebook-f"></i>
            </a>
            <a href="https://youtube.com/https://www.youtube.com/@InfoCard123" target="_blank" class="bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded flex items-center gap-2 text-sm font-bold transition">
                <i class="fab fa-youtube"></i> SUBSCRIBE
            </a>
        </div>
    </nav>

    <section id="home" class="min-h-screen flex items-center justify-center relative overflow-hidden px-6">
        <div class="absolute inset-0 opacity-20">
            <img src="https://images.unsplash.com/photo-1485846234645-a62644f84728?auto=format&fit=crop&w=1920&q=80" alt="bg" class="w-full h-full object-cover">
        </div>
        <div class="relative z-10 text-center max-w-3xl">
            <span class="text-red-600 font-bold tracking-widest uppercase mb-4 block">একটি স্বাধীন প্রোডাকশন</span>
            <h1 class="text-5xl md:text-8xl font-bold mb-6 text-white leading-tight">সঠিক তথ্য <br> জানুন </h1>
            <p class="text-gray-400 text-lg md:text-xl mb-10 leading-relaxed">
                আমরা কেবল ভিডিও বানাই না, আমরা প্রতিটি ঘটনার গভীরে গিয়ে প্রকৃত তথ্য আপনার সামনে তুলে ধরি। আমাদের ডকুমেন্টারিগুলো আপনাকে নতুনভাবে ভাবতে শেখাবে।
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#docs" class="bg-white text-black px-8 py-4 rounded-full font-bold hover:bg-red-600 hover:text-white transition duration-300">ভিডিওগুলো দেখুন</a>
                <a href="#contact" class="border border-white/20 px-8 py-4 rounded-full font-bold hover:bg-white/10 transition">আমাদের সাথে যুক্ত হোন</a>
            </div>
        </div>
    </section>

    <section id="docs" class="py-32 px-6 max-w-7xl mx-auto">
        <div class="flex justify-between items-end mb-16">
            <div>
                <h2 class="text-4xl font-bold text-white mb-2">সাম্প্রতিক কাজসমূহ</h2>
                <p class="text-red-500 font-semibold">By InfoCard</p>
            </div>
            <div class="hidden md:block h-1 w-32 bg-red-600 mb-4"></div>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
            <div class="video-card rounded-2xl overflow-hidden">
                <div class="aspect-video">
                    <iframe class="w-full h-full" src="https://www.youtube.com/embed/huqGbNLqp9Y&t=8s" frameborder="0" allowfullscreen></iframe>
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">পিলখানা: একটি জাতীয় ক্ষত I</h3>
                    <p class="text-gray-500 text-sm">কি ঘটে ছিল সেদিন?।</p>
                </div>
            </div>

            <div class="video-card rounded-2xl overflow-hidden">
                <div class="aspect-video">
                    <iframe class="w-full h-full" src="https://www.youtube.com/embed/eZ2bp58jHsc&t=1s" frameborder="0" allowfullscreen></iframe>
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">
ছায়া মমন্ত্রীসভা </h3>
                    <p class="text-gray-500 text-sm">গণতন্ত্রের অতন্দ্র প্রহিরী</p>
                </div>
            </div>

            <div class="video-card rounded-2xl overflow-hidden">
                <div class="aspect-video">
                    <iframe class="w-full h-full" src="https://www.youtube.com/embed/WeO7a6GG5zU&t=3s" frameborder="0" allowfullscreen></iframe>
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">
রোজার বিজ্ঞান</h3>
                    <p class="text-gray-500 text-sm">রোজার অলৌকিক বৈজ্ঞানিক ও স্বাস্থ্য উপকারিতা।।</p>
                </div>
            </div>
        </div>
    </section>

    <section id="team" class="py-32 px-6 bg-[#080808]">
                <h2 class="text-4xl font-bold text-white mb-4">পর্দার পেছনের কারিগর</h2>
                <p class="text-gray-500">অক্লান্ত পরিশ্রমের ফল আমাদের প্রতিটি কাজ।</p>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <div class="text-center group">
                    <div class="w-32 h-32 md:w-48 md:h-48 mx-auto rounded-full overflow-hidden border-4 border--red-600 transition duration-500 mb-6">
                        <img src="---------" alt="" class="w-full h-full object-cover">
                    </div>
                    <h4 class="text-xl font-bold text-white">Riyedul Islam</h4>
                    <p class="text-red-500 text-sm">Chif of Voice,Editing and research </p>
                </div>

                    </section>

    <footer id="contact" class="py-20 px-6 border-t border-white/5 bg-black">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-10">
            <div>
                <div class="text-3xl font-black text-white mb-4">Info<span class="text-red-600">Card</span></div>
                <p class="text-gray-500 max-w-xs">আমরা আমাদের কাজের মাধ্যমে নতুন সমাজ গড়ার প্রেরণা যোগাই। সত্যের সাথে থাকুন।</p>
            </div>
            
            <div class="flex flex-col items-center md:items-end">
                <div class="flex gap-6 mb-6">
                    <a href="#" class="text-2xl hover:text-red-600 transition"><i class="fab fa-youtube"></i></a>
                    <a href="#" class="text-2xl hover:text-blue-500 transition"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="text-2xl hover:text-sky-400 transition"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="text-2xl hover:text-pink-500 transition"><i class="fab fa-instagram"></i></a>
                </div>
                <p class="text-gray-600 text-sm">© ২০২৪ InfoCard। সর্বস্বত্ব সংরক্ষিত।</p>
            </div>
        </div>
    </footer>

</body>
</html>
