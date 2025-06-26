

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Cumpleaños de Aura Anyelina!</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&family=Chewy&display=swap" rel="stylesheet">
    <style>
        /* Custom font for a fun, Bluey-like feel */
        .font-chewy {
            font-family: 'Chewy', cursive;
        }
        body {
            font-family: 'Inter', sans-serif;
            /*background-color: #F0F8FF;  Light blue background, reminiscent of sky */
            background-image: url("https://i.etsystatic.com/35809767/r/il/ac6c28/6671301938/il_794xN.6671301938_2ra1.jpg");
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
        }
        .card-container {
          background-image: url("https://www.bluey.tv/wp-content/uploads/2025/03/Make-new.png");
            background-color: #FFFFFF; /* White card background */
            border: 4px solid #FFD700; /* Gold border for celebration */
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2); /* Stronger shadow for pop */
        }
        .button-primary {
            background-color: #FFA07A; /* Light Salmon, cheerful color */
            color: #FFFFFF;
            border: 2px solid #FF8C00; /* Darker orange border */
            transition: all 0.3s ease;
        }
        .button-primary:hover {
            background-color: #FF8C00; /* Darker orange on hover */
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        /* Carousel specific styles */
        .carousel-container {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 1rem; /* rounded-xl equivalent */
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
            background-color: #fef08a; /* bg-yellow-200 */
        }
        .carousel-images {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }
        .carousel-images img {
            width: 100%;
            height: 250px; /* Fixed height for consistency */
            object-fit: cover; /* Ensures images cover the area without distortion */
            flex-shrink: 0;
            border-radius: 1rem; /* rounded-xl equivalent */
        }
        .carousel-button {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background-color: rgba(0, 0, 0, 0.5);
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 9999px; /* full rounded */
            font-size: 1.5rem;
            transition: background-color 0.3s ease;
            z-index: 10;
        }
        .carousel-button:hover {
            background-color: rgba(0, 0, 0, 0.7);
        }
        .carousel-button.prev {
            left: 10px;
        }
        .carousel-button.next {
            right: 10px;
        }
    </style>
</head>
<body class="antialiased">
    <div class="container mx-auto p-6 card-container rounded-3xl max-w-xl w-full sm:p-8 md:p-10">
        <!-- Bluey-themed Header Section -->
        <header class="text-center mb-8">
            <p class="text-lg sm:text-2xl text-blue-600 font-semibold mb-2 font-chewy">ESTE EPISODIO DE</p>
            <h1 class="text-5xl sm:text-7xl font-chewy text-blue-800 mb-4 leading-tight drop-shadow-lg">BLUEY</h1>
            <h2 class="text-4xl sm:text-5xl font-chewy text-pink-600 mb-6 drop-shadow-md">SE LLAMA</h2>
            <p class="text-5xl sm:text-7xl font-chewy text-purple-700 mb-6 drop-shadow-xl animate-pulse">AURA ANYELINA</p>
        </header>

        <!-- Main Invitation Content -->
        <main class="text-gray-900 text-center">
            <p class="text-lg sm:text-4xl text-blue-900 font-semibold mb-2 font-chewy">
                ¡VEN A CELEBRAR MI <span class="text-red-600 font-extrabold text-3xl sm:text-4xl">3er</span> CUMPLEAÑOS!
            </p>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8 text-center">
                <!-- Date & Time -->
                <div class="bg-yellow-100 p-4 rounded-2xl shadow-md border border-yellow-300">
                    <p class="text-lg sm:text-2xl text-blue-600 font-semibold mb-2 font-chewy">Día de la Celebración:</p>
                    <p class="text-gray-800 text-xl font-semibold text-gray-800 font-semibold sm:text-2xl mb-2 font-chewy">SÁBADO 2</p>
                    <p class="text-gray-800 text-l sm:text-2xl mb-2 font-semibold mb-2 font-chewy">DE AGOSTO</p>
                </div>

                <!-- Ceremony Time -->
                <div class="bg-blue-100 p-4 rounded-2xl shadow-md border border-blue-300">
                    <p class="ftext-lg sm:text-2xl text-blue-600 font-semibold mb-2 font-chewy">La Misa es a las:</p>
                    <p class="text-xl sm:text-4xl font-chewy text-pink-600 mb-2 drop-shadow-md">13:00 HRS</p>
                    <p class="text-gray-600 text-l text-gray-800 text-lg mb-2 font-semibold mb-2 font-chewy">Santuario del Señor de las Misericordias, San Pedro Atocpan, Panchimalco, Milpa Alta, 12200 San Pedro Atocpan, CDMX</p>
                  <p class="text-gray-700 text-md mt-1 font-semibold mb-2 font-chewy"><a href="https://maps.app.goo.gl/CDaRXRMnErwNMWRu5">DALE CLICK PARA VER LA UBICACION EN EL MAPA</a></p>
                </div>
            </div>

            <!-- Party Time & Location -->
            <section class="mb-8 p-6 bg-pink-100 rounded-2xl border border-pink-300 shadow-lg">
                <h3 class="text-2xl sm:text-3xl font-chewy text-pink-800 mb-3 drop-shadow">¡La Fiesta Empieza!</h3>
                <p class="ftext-lg sm:text-3xl text-blue-600 font-semibold mb-2 font-chewy">A LAS <span class="text-xl sm:text-4xl font-chewy text-pink-600 mb-2 drop-shadow-md">15:30 HRS</span></p>
                <p class="text-gray-800 text-lg mb-2 font-semibold mb-2 font-chewy">
                    LUGAR DE LA FIESTA:
                </p>
                <p class="text-gray-900 text-l font-medium font-semibold mb-2 font-chewy">
                    San Lucas Xochimanca, 16300 Ciudad de México, CDMX
                </p>
                <p class="text-gray-700 text-sm mt-1 font-semibold mb-2 font-chewy"><a href="https://maps.app.goo.gl/Ur9D2QfJiqSChbdR8">DALE CLICK PARA VER LA UBICACION EN EL MAPA</a></p>
            </section>

            <!-- Photo Carousel Section -->
            <section class="mb-8 p-4 bg-yellow-50 rounded-2xl border border-yellow-200 shadow-md">
                <h3 class="text-xl sm:text-2xl font-chewy text-orange-700 mb-4 drop-shadow">Momentos para Recordar</h3>
                <div class="carousel-container relative mx-auto max-w-lg mb-4">
                    <div class="carousel-images" id="carouselImages">
                        <img src="https://placehold.co/600x250/FFC107/FFFFFF?text=Aura+1" alt="Aura celebrando su cumpleaños">
                        <img src="https://placehold.co/600x250/87CEEB/FFFFFF?text=Fiesta+2" alt="Niños jugando en la fiesta">
                        <img src="https://placehold.co/600x250/FF69B4/FFFFFF?text=Amigos+3" alt="Aura con amigos">
                        <img src="https://placehold.co/600x250/9370DB/FFFFFF?text=Diversion+4" alt="Juegos y diversión en el cumpleaños">
                    </div>
                    <button class="carousel-button prev" onclick="moveSlide(-1)">&#10094;</button>
                    <button class="carousel-button next" onclick="moveSlide(1)">&#10095;</button>
                </div>
                <p class="text-gray-600 text-sm italic">¡Desliza para ver más fotos de la diversión!</p>
            </section>

            <!-- RSVP Section -->
            <section class="mb-8 p-4 bg-green-100 rounded-xl border border-green-300 shadow-md">
                <h3 class="text-xl sm:text-2xl font-bold text-green-800 mb-3">¡No Faltes!</h3>
                <p class="text-gray-700 text-l mt-1 font-semibold mb-2 font-chewy">
                    Por favor, confirma tu asistencia para que podamos planear la diversión.
                </p>
                <a href="mailto:tu.correo@ejemplo.com?subject=Confirmacion%20Asistencia%20Cumpleaños%20Aura"
                   class="inline-block button-primary font-semibold py-3 px-6 rounded-full transform hover:scale-105 shadow-md">
                    Confirmar Asistencia
                </a>
                <p class="text-gray-700 text-l mt-1 font-semibold mb-2 font-chewy">También puedes contactarnos al NUMERO DE MI PAPA: 5565119674</p>
            </section>
        </main>

        <!-- Footer Section -->
        <footer class="text-center mt-10 text-gray-500 text-sm">
            <p>¡Esperamos verte allí para un día lleno de alegría y diversión!</p>
            <p>&copy; [Año] Familia de Aura Anyelina. Todos los derechos reservados.</p>
        </footer>
    </div>

    <script>
        const carouselImages = document.getElementById('carouselImages');
        const images = carouselImages.getElementsByTagName('img');
        let currentIndex = 0;
        const totalImages = images.length;

        // Function to show a specific slide
        function showSlide(index) {
            if (index >= totalImages) {
                currentIndex = 0; // Loop back to the first image
            } else if (index < 0) {
                currentIndex = totalImages - 1; // Loop back to the last image
            } else {
                currentIndex = index;
            }
            const offset = -currentIndex * 100;
            carouselImages.style.transform = `translateX(${offset}%)`;
        }

        // Function to move to the next or previous slide
        function moveSlide(direction) {
            showSlide(currentIndex + direction);
        }

        // Automatic slide change (optional)
        let slideInterval;

        function startSlideShow() {
            slideInterval = setInterval(() => {
                moveSlide(1);
            }, 3000); // Change image every 3 seconds
        }

        function stopSlideShow() {
            clearInterval(slideInterval);
        }

        // Start slideshow when the window loads
        window.onload = function() {
            showSlide(currentIndex); // Initialize the first slide
            startSlideShow();

            // Pause slideshow on hover
            const carouselContainer = document.querySelector('.carousel-container');
            carouselContainer.addEventListener('mouseenter', stopSlideShow);
            carouselContainer.addEventListener('mouseleave', startSlideShow);
        };
    </script>
</body>
</html>
