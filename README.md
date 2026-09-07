<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beatriz Briceño-Picón | Familia, Hogar y Legado</title>
    
    <!-- Favicon -->
    <link rel="icon" href="mbi.png?v=1" type="image/png">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;1,400;1,600&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    
    <!-- Custom Tailwind Configuration -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        pine: { DEFAULT: '#115E3E', dark: '#0A3B26', light: '#1B8257' },
                        pastelYellow: { DEFAULT: '#FEF08A', hover: '#FDE047' },
                        charcoal: { 800: '#333333', 900: '#1A1A1A' },
                        softSand: '#FAF9F6' /* Un color cálido para el fondo */
                    },
                    fontFamily: {
                        sans: ['Montserrat', 'sans-serif'],
                        title: ['Montserrat', 'sans-serif'],
                        serif: ['Montserrat', 'sans-serif'],
                        cursiva: ['Dancing Script', 'cursive'],
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-softSand text-charcoal-900 font-sans antialiased selection:bg-pine selection:text-white flex flex-col min-h-screen">

    <!-- NAVIGATION BAR -->
    <header class="fixed w-full top-0 z-50 bg-white/95 backdrop-blur-md border-b border-gray-200 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 h-24 flex items-center justify-between">
            
            <div class="logo-container flex items-center">
                <!-- Enlace para volver a la página principal -->
                <a href="index.html" class="flex items-center text-pine hover:text-pine-light transition-colors font-bold uppercase tracking-widest text-xs">
                    <i data-lucide="arrow-left" class="w-5 h-5 mr-2"></i>
                    Volver a MBI Hoy
                </a>
            </div>
            
            <nav class="hidden lg:flex space-x-8 text-sm tracking-widest font-semibold uppercase text-charcoal-800">
                <a href="#perfil" class="hover:text-pine transition-colors">Perfil</a>
                <a href="#legado" class="hover:text-pine transition-colors">Legado de MBI</a>
                <a href="#hogar" class="hover:text-pine transition-colors">Familia y Hogar</a>
            </nav>

            <a href="mailto:beatriz.beamer@gmail.com" class="hidden lg:inline-flex items-center text-sm uppercase font-semibold tracking-widest px-6 py-3 bg-pastelYellow text-pine hover:bg-pine hover:text-white rounded-md transition-all duration-300 shadow-sm border border-transparent hover:border-pine">Contacto</a>

            <button id="mobile-menu-btn" class="lg:hidden p-2 text-pine focus:outline-none" aria-label="Abrir Menú">
                <i data-lucide="menu" class="w-8 h-8"></i>
            </button>
        </div>

        <!-- Menú Móvil -->
        <div id="mobile-menu" class="hidden bg-white border-b border-gray-200 px-6 py-6 space-y-5 shadow-lg">
            <a href="index.html" class="block text-sm font-bold uppercase tracking-widest text-pine mb-4">← Volver a MBI Hoy</a>
            <a href="#perfil" class="block text-sm font-semibold uppercase tracking-widest text-charcoal-800 hover:text-pine">Perfil</a>
            <a href="#legado" class="block text-sm font-semibold uppercase tracking-widest text-charcoal-800 hover:text-pine">Legado de MBI</a>
            <a href="#hogar" class="block text-sm font-semibold uppercase tracking-widest text-charcoal-800 hover:text-pine">Familia y Hogar</a>
        </div>
    </header>

    <!-- HERO SECTION (Elegante y cálido) -->
    <section class="relative pt-32 pb-16 lg:pt-48 lg:pb-24 bg-pine-dark text-white overflow-hidden">
        <div class="absolute inset-0 opacity-10 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')]"></div>
        <div class="max-w-5xl mx-auto px-6 lg:px-12 relative z-10 text-center">
            <span class="block text-pastelYellow font-bold tracking-[0.2em] uppercase text-sm mb-4">Humanista & Periodista</span>
            <h1 class="text-4xl md:text-6xl lg:text-7xl font-bold font-title tracking-tight mb-6">
                Beatriz Briceño-Picón
            </h1>
            <p class="text-lg md:text-2xl font-light text-gray-200 max-w-3xl mx-auto leading-relaxed">
                El hogar como primer bastión cívico y la custodia de un legado intelectual para las nuevas generaciones.
            </p>
        </div>
    </section>

    <!-- INTRO / PERFIL -->
    <section id="perfil" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-6 lg:px-12">
            <div class="flex flex-col md:flex-row gap-12 items-center">
                <div class="w-full md:w-1/3 shrink-0">
                    <img src="Bea.png" alt="Beatriz Briceño-Picón" class="w-full max-w-[280px] mx-auto rounded-2xl shadow-xl border-4 border-softSand object-cover aspect-[4/5]" onerror="this.src='https://via.placeholder.com/400x500?text=Beatriz'">
                </div>
                <div class="w-full md:w-2/3 space-y-6">
                    <i data-lucide="quote" class="w-12 h-12 text-pastelYellow mb-2"></i>
                    <p class="text-lg md:text-xl text-charcoal-800 leading-relaxed font-medium">
                        "Ha querido siempre entrelazar personas, instituciones, cátedras y empresas que trabajan por mantener la vigencia del pensamiento de su padre."
                    </p>
                    <p class="text-base text-gray-600 leading-relaxed">
                        Su empeño ha sido siempre fortalecer nuestra venezolanidad desde el hogar, la escuela, el campo y los medios de comunicación social, como vía para alcanzar el humanismo integral y solidario abierto a la trascendencia que nuestro mundo reclama.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ARTÍCULOS: LEGADO DE SU PADRE -->
    <section id="legado" class="py-20 bg-softSand border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="text-center space-y-4 mb-16">
                <span class="text-sm font-bold tracking-widest text-pine uppercase">Sobre Mario Briceño-Iragorry</span>
                <h2 class="font-title text-3xl sm:text-4xl font-extrabold text-charcoal-900 uppercase">La Memoria de mi Padre</h2>
                <div class="w-16 h-1 bg-pastelYellow mx-auto rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Artículo 1 -->
                <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 overflow-hidden border border-gray-100 flex flex-col">
                    <div class="h-48 bg-pine-light overflow-hidden">
                        <img src="mensaje.jpeg" alt="Artículo MBI" class="w-full h-full object-cover opacity-80 mix-blend-multiply" onerror="this.src='https://via.placeholder.com/600x400?text=Articulo'">
                    </div>
                    <div class="p-8 flex flex-col flex-grow">
                        <h3 class="text-xl font-bold text-charcoal-900 mb-3">Vigencia de "Mensaje sin Destino"</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6 flex-grow">Una mirada personal y reflexiva sobre cómo las palabras escritas por mi padre hace décadas siguen describiendo los retos de nuestra sociedad actual.</p>
                        <a href="#" class="text-pine font-bold uppercase tracking-widest text-xs inline-flex items-center hover:text-pastelYellow-hover transition-colors">
                            Leer Artículo <i data-lucide="arrow-right" class="w-4 h-4 ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Artículo 2 -->
                <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 overflow-hidden border border-gray-100 flex flex-col">
                    <div class="h-48 bg-pine-dark overflow-hidden">
                        <img src="fidel.webp" alt="Artículo MBI" class="w-full h-full object-cover opacity-80 mix-blend-multiply" onerror="this.src='https://via.placeholder.com/600x400?text=Articulo'">
                    </div>
                    <div class="p-8 flex flex-col flex-grow">
                        <h3 class="text-xl font-bold text-charcoal-900 mb-3">El hombre detrás del pensador</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6 flex-grow">Anécdotas cotidianas y el recuerdo de un padre que enseñaba con el ejemplo la ética y el amor profundo por Venezuela.</p>
                        <a href="#" class="text-pine font-bold uppercase tracking-widest text-xs inline-flex items-center hover:text-pastelYellow-hover transition-colors">
                            Leer Artículo <i data-lucide="arrow-right" class="w-4 h-4 ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Artículo 3 -->
                <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 overflow-hidden border border-gray-100 flex flex-col">
                    <div class="h-48 bg-pastelYellow overflow-hidden flex items-center justify-center">
                        <i data-lucide="book-open" class="w-20 h-20 text-pine opacity-20"></i>
                    </div>
                    <div class="p-8 flex flex-col flex-grow">
                        <h3 class="text-xl font-bold text-charcoal-900 mb-3">Defendiendo lo nuestro</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6 flex-grow">Un análisis sobre la importancia de conocer nuestras raíces históricas para no ceder ante la crisis moral del antipaís.</p>
                        <a href="#" class="text-pine font-bold uppercase tracking-widest text-xs inline-flex items-center hover:text-pastelYellow-hover transition-colors">
                            Leer Artículo <i data-lucide="arrow-right" class="w-4 h-4 ml-1"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ARTÍCULOS: FAMILIA Y HOGAR -->
    <section id="hogar" class="py-20 bg-white border-t border-gray-100">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="text-center space-y-4 mb-16">
                <span class="text-sm font-bold tracking-widest text-pine uppercase">El primer bastión cívico</span>
                <h2 class="font-title text-3xl sm:text-4xl font-extrabold text-charcoal-900 uppercase">Familia y Labores del Hogar</h2>
                <div class="w-16 h-1 bg-pastelYellow mx-auto rounded-full"></div>
                <p class="max-w-2xl mx-auto text-gray-600 mt-4 font-medium">Reflexiones sobre el cuidado cotidiano, la crianza y la administración del hogar como cimientos fundamentales de una sociedad sana.</p>
            </div>

            <!-- Layout alterno para variedad visual -->
            <div class="space-y-12 max-w-5xl mx-auto">
                
                <!-- Tema 1 -->
                <div class="flex flex-col md:flex-row gap-8 items-center bg-softSand p-6 md:p-8 rounded-2xl border border-gray-100">
                    <div class="w-full md:w-1/3 aspect-square bg-gray-200 rounded-xl overflow-hidden shrink-0">
                        <img src="https://images.unsplash.com/photo-1484154218962-a197022b5858?q=80&w=800&auto=format&fit=crop" alt="Cocina y hogar" class="w-full h-full object-cover">
                    </div>
                    <div class="w-full md:w-2/3 space-y-4">
                        <h3 class="text-2xl font-bold text-charcoal-900">El arte de hacer hogar</h3>
                        <p class="text-gray-600 leading-relaxed">El orden, la limpieza y la dedicación a los quehaceres diarios no son tareas menores, sino actos de profundo amor que construyen el refugio seguro donde se forma el carácter de los futuros ciudadanos.</p>
                        <div class="pt-2">
                            <a href="#" class="text-pine font-bold uppercase tracking-widest text-xs inline-flex items-center border-b-2 border-transparent hover:border-pine transition-all pb-1">
                                Leer reflexión completa <i data-lucide="arrow-right" class="w-4 h-4 ml-2"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Tema 2 -->
                <div class="flex flex-col md:flex-row-reverse gap-8 items-center bg-softSand p-6 md:p-8 rounded-2xl border border-gray-100">
                    <div class="w-full md:w-1/3 aspect-square bg-gray-200 rounded-xl overflow-hidden shrink-0">
                        <img src="https://images.unsplash.com/photo-1511895426328-dc8714191300?q=80&w=800&auto=format&fit=crop" alt="Familia" class="w-full h-full object-cover">
                    </div>
                    <div class="w-full md:w-2/3 space-y-4 text-left md:text-right">
                        <h3 class="text-2xl font-bold text-charcoal-900">Educar en valores desde la mesa</h3>
                        <p class="text-gray-600 leading-relaxed">La mesa familiar es la primera escuela de civismo. Es el lugar donde se aprende a escuchar, a compartir y donde se transmiten las tradiciones que nos dan identidad como pueblo.</p>
                        <div class="pt-2">
                            <a href="#" class="text-pine font-bold uppercase tracking-widest text-xs inline-flex items-center flex-row-reverse md:flex-row border-b-2 border-transparent hover:border-pine transition-all pb-1">
                                <i data-lucide="arrow-left" class="w-4 h-4 mr-2 hidden md:inline-block"></i>
                                Leer reflexión completa
                                <i data-lucide="arrow-right" class="w-4 h-4 ml-2 md:hidden"></i>
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-pine-dark text-white mt-auto border-t-4 border-pastelYellow">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 py-12 flex flex-col md:flex-row justify-between items-center gap-6">
            <div class="text-center md:text-left">
                <h3 class="font-title text-xl font-extrabold tracking-wider uppercase text-pastelYellow mb-2">Beatriz Briceño-Picón</h3>
                <p class="text-sm text-gray-300">Periodismo, Familia y Humanismo.</p>
            </div>
            <div class="flex flex-col items-center md:items-end gap-3">
                <a href="mailto:beatriz.beamer@gmail.com" class="flex items-center text-sm hover:text-pastelYellow transition-colors">
                    <i data-lucide="mail" class="w-4 h-4 mr-2"></i> beatriz.beamer@gmail.com
                </a>
                <a href="index.html" class="flex items-center text-sm font-bold uppercase tracking-widest text-pine-light hover:text-white transition-colors">
                    Ir a MBI Hoy <i data-lucide="external-link" class="w-4 h-4 ml-2"></i>
                </a>
            </div>
        </div>
        <div class="bg-black/20 text-center py-4">
            <p class="text-xs text-gray-400">© 2026 Beatriz Briceño-Picón. Todos los derechos reservados.</p>
        </div>
    </footer>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        lucide.createIcons();
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuBtn.addEventListener('click', () => { mobileMenu.classList.toggle('hidden'); });
    </script>
</body>
</html>
