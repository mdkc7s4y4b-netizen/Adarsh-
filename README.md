<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Oops... My Bad (Send Help) 😭</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Comic+Neue:wght@400;700&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            comic: ['"Comic Neue"', 'cursive'],
            sans: ['Inter', 'system-ui', 'sans-serif']
          },
          animation: {
            'wobble': 'wobble 3s infinite',
            'shake': 'shake 0.8s cubic-bezier(.36,.07,.19,.97) both',
            'float': 'float 4s ease-in-out infinite'
          },
          keyframes: {
            wobble: { '0%,100%': { transform: 'rotate(-3deg)' }, '50%': { transform: 'rotate(3deg)' } },
            shake: { '10%,90%': { transform: 'translate3d(-2px,0,0)' }, '20%,80%': { transform: 'translate3d(4px,0,0)' }, '30%,50%,70%': { transform: 'translate3d(-6px,0,0)' }, '40%,60%': { transform: 'translate3d(6px,0,0)' } },
            float: { '0%,100%': { transform: 'translateY(0)' }, '50%': { transform: 'translateY(-15px)' } }
          }
        }
      }
    }
  </script>
</head>
<body class="bg-gradient-to-br from-yellow-100 via-pink-100 to-orange-100 min-h-screen flex items-center justify-center p-6 font-sans overflow-hidden">

  <!-- Floating chaos emojis -->
  <div class="absolute inset-0 pointer-events-none overflow-hidden">
    <div class="absolute top-10 left-10 text-6xl animate-float" style="animation-delay:0s;">😭</div>
    <div class="absolute bottom-20 right-20 text-7xl animate-float" style="animation-delay:1.5s;">🤡</div>
    <div class="absolute top-1/3 right-1/4 text-5xl animate-float" style="animation-delay:3s;">💀</div>
  </div>

  <main class="relative z-10 max-w-3xl text-center space-y-10">

    <!-- Meme overload images -->
    <div class="flex flex-wrap justify-center gap-6 animate-shake">
      <img 
        src="https://media.tenor.com/wSxKlGaNxOUAAAAe/sorry-stitch.png" 
        alt="Stitch begging sorry" 
        class="w-44 md:w-56 rounded-2xl shadow-2xl border-8 border-white transform hover:scale-110 transition"
      />
      <img 
        src="https://thumbs.dreamstime.com/b/apology-eyes-adorable-kitten-holding-i-m-sorry-sign-image-melts-hearts-tiny-peering-torn-edges-305639123.jpg" 
        alt="Kitten sorry sign" 
        class="w-44 md:w-56 rounded-2xl shadow-2xl border-8 border-white transform hover:scale-110 transition"
      />
      <img 
        src="https://thumbs.dreamstime.com/b/cute-begging-dog-illustration-hungry-food-treat-adorable-eyes-please-307640856.jpg" 
        alt="Begging puppy eyes" 
        class="w-44 md:w-56 rounded-2xl shadow-2xl border-8 border-white transform hover:scale-110 transition"
      />
    </div>

    <!-- Main title – pure clown energy -->
    <h1 class="text-6xl md:text-8xl font-comic font-bold text-red-600 drop-shadow-lg animate-wobble">
      BRO I'M SORRY OKAY?! 😭🤡
    </h1>

    <p class="text-2xl md:text-3xl text-gray-800 font-bold leading-relaxed max-w-2xl mx-auto">
      I messed up so hard even my future self is embarrassed.<br>
      Like… Olympic-level stupidity. Gold medal in clownery. 🏅
    </p>

    <div class="bg-white/60 backdrop-blur-lg rounded-3xl p-8 md:p-12 shadow-2xl border-4 border-red-300 animate-float">
      <p class="text-xl md:text-2xl text-gray-900 leading-relaxed font-medium">
        Things I did wrong (short list because my ego can't handle the full version):<br><br>
        • Said dumb thing #47<br>
        • Forgot important thing #12<br>
        • Acted like a potato when I should've been a functional human<br><br>
        <span class="block text-3xl font-bold text-purple-700 mt-6">
          Plot twist: I'm still a potato... but a sorry potato now 🍟💔
        </span>
      </p>
    </div>

    <!-- Final plea with meme energy -->
    <div class="space-y-8">
      <p class="text-3xl md:text-4xl font-comic text-pink-700 font-bold">
        Please forgive me?<br>
        I'll bribe you with memes, snacks, and zero more potato behavior (maybe)
      </p>

      <div class="flex justify-center gap-6 flex-wrap">
        <button onclick="alert('Virtual sorry hug deployed! 🤗 + extra memes incoming')" class="px-10 py-5 bg-gradient-to-r from-yellow-400 to-orange-500 text-white font-bold text-xl rounded-full shadow-xl hover:scale-110 transition transform">
          FORGIVE ME PLZ
        </button>
        <a href="mailto:you@example.com?subject=OK%20FINE%20YOU%27RE%20FORGIVEN%20(almost)" class="px-10 py-5 bg-gradient-to-r from-purple-500 to-pink-500 text-white font-bold text-xl rounded-full shadow-xl hover:scale-110 transition transform">
          Let's negotiate peace 🍕
        </a>
      </div>

      <p class="text-xl text-gray-700 italic mt-10">
        If no forgiveness → I'll just keep sending increasingly desperate cat pics until you crack 😂
      </p>
    </div>

    <footer class="pt-16 text-gray-600 text-lg">
      Sent from the clown dimension • Level 99 Apology Energy • 2026
    </footer>

  </main>

</body>
</html>
