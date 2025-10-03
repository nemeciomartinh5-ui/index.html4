<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Plan de Vida y Liderazgo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .section-card {
            background-color: white;
            border-radius: 0.75rem;
            padding: 2rem;
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .section-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
        }
        .fade-in {
            animation: fadeInAnimation 1s ease-in forwards;
            opacity: 0;
        }
        @keyframes fadeInAnimation {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header y Navegación -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold text-blue-600">Mi Perfil Profesional</h1>
            <div class="hidden md:flex space-x-6">
                <a href="#foda" class="text-gray-600 hover:text-blue-600 transition duration-300">Análisis FODA</a>
                <a href="#smart" class="text-gray-600 hover:text-blue-600 transition duration-300">Objetivos SMART</a>
                <a href="#relaciones" class="text-gray-600 hover:text-blue-600 transition duration-300">Agenda de Relaciones</a>
                <a href="#reflexion" class="text-gray-600 hover:text-blue-600 transition duration-300">Reflexión Final</a>
            </div>
            <!-- Menú Móvil (Opcional) -->
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-600 hover:text-blue-600 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </nav>
        <div id="mobile-menu" class="hidden md:hidden px-6 pt-2 pb-4">
            <a href="#foda" class="block py-2 text-gray-600 hover:text-blue-600">Análisis FODA</a>
            <a href="#smart" class="block py-2 text-gray-600 hover:text-blue-600">Objetivos SMART</a>
            <a href="#relaciones" class="block py-2 text-gray-600 hover:text-blue-600">Agenda de Relaciones</a>
            <a href="#reflexion" class="block py-2 text-gray-600 hover:text-blue-600">Reflexión Final</a>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">
        
        <!-- Sección de Bienvenida -->
        <section class="text-center mb-16 fade-in">
            <h2 class="text-4xl font-bold text-gray-900 mb-4">Plan de Vida y Liderazgo</h2>
            <p class="text-lg text-gray-600 max-w-3xl mx-auto">Un espacio para definir mi crecimiento personal y profesional, alineando mis fortalezas con mis metas para construir un futuro con propósito.</p>
        </section>

        <!-- Análisis FODA -->
        <section id="foda" class="mb-16 fade-in" style="animation-delay: 0.2s;">
            <div class="section-card">
                <h3 class="text-3xl font-bold mb-2 text-blue-700">Análisis FODA Personal</h3>
                <p class="text-gray-600 mb-6">Mi misión es [**Describe aquí tu misión personal o profesional de forma concisa. Ej: "Utilizar mis habilidades de comunicación y empatía para liderar equipos innovadores y generar un impacto positivo en la industria tecnológica."**]. Este análisis FODA me permite alinear mis acciones con este propósito.</p>
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- Fortalezas -->
                    <div class="bg-green-50 p-6 rounded-lg border border-green-200">
                        <h4 class="font-bold text-xl mb-3 text-green-800">Fortalezas</h4>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Liderazgo y gestión de equipos.</li>
                            <li>Resolución creativa de problemas.</li>
                            <li>Habilidad para la comunicación asertiva.</li>
                            <li>Adaptabilidad y aprendizaje rápido.</li>
                        </ul>
                    </div>
                    <!-- Oportunidades -->
                    <div class="bg-blue-50 p-6 rounded-lg border border-blue-200">
                        <h4 class="font-bold text-xl mb-3 text-blue-800">Oportunidades</h4>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Crecimiento del sector tecnológico en LATAM.</li>
                            <li>Posibilidad de tomar cursos de especialización en IA.</li>
                            <li>Networking en eventos de la industria.</li>
                            <li>Mentoría de líderes con más experiencia.</li>
                        </ul>
                    </div>
                    <!-- Debilidades -->
                    <div class="bg-yellow-50 p-6 rounded-lg border border-yellow-200">
                        <h4 class="font-bold text-xl mb-3 text-yellow-800">Debilidades</h4>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Tendencia a la procrastinación en tareas administrativas.</li>
                            <li>Dificultad para delegar tareas de alta responsabilidad.</li>
                            <li>Conocimientos técnicos básicos en programación.</li>
                            <li>Poca experiencia en gestión de presupuestos.</li>
                        </ul>
                    </div>
                    <!-- Amenazas -->
                    <div class="bg-red-50 p-6 rounded-lg border border-red-200">
                        <h4 class="font-bold text-xl mb-3 text-red-800">Amenazas</h4>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Alta competencia en el mercado laboral.</li>
                            <li>Cambios rápidos en las tecnologías emergentes.</li>
                            <li>Incertidumbre económica global.</li>
                            <li>Equilibrio entre vida laboral y personal.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Objetivos SMART -->
        <section id="smart" class="mb-16 fade-in" style="animation-delay: 0.4s;">
            <div class="section-card">
                <h3 class="text-3xl font-bold mb-6 text-blue-700">Mis 8 Objetivos SMART</h3>
                <div class="space-y-4">
                    <!-- Ejemplo de Objetivo SMART -->
                    <div class="p-4 border-l-4 border-blue-500 bg-blue-50 rounded-r-lg">
                        <p><strong>1. Desarrollo Profesional:</strong> Completar la certificación de "Project Management Professional (PMP)" para Diciembre de 2024, estudiando 5 horas semanales y realizando un examen de prueba al mes.</p>
                    </div>
                    <div class="p-4 border-l-4 border-green-500 bg-green-50 rounded-r-lg">
                        <p><strong>2. Habilidades Técnicas:</strong> Aprender los fundamentos de Python y desarrollar un pequeño proyecto personal (ej. un web scraper) en los próximos 6 meses para fortalecer mi perfil técnico.</p>
                    </div>
                    <div class="p-4 border-l-4 border-yellow-500 bg-yellow-50 rounded-r-lg">
                        <p><strong>3. Networking:</strong> Asistir a 3 eventos de la industria y conectar con 15 profesionales nuevos en LinkedIn en el próximo trimestre, iniciando al menos 5 conversaciones significativas.</p>
                    </div>
                     <div class="p-4 border-l-4 border-purple-500 bg-purple-50 rounded-r-lg">
                        <p><strong>4. Liderazgo:</strong> Asumir la coordinación de un proyecto interno en mi trabajo actual en los próximos 4 meses, aplicando metodologías ágiles para mejorar la eficiencia del equipo en un 10%.</p>
                    </div>
                    <div class="p-4 border-l-4 border-red-500 bg-red-50 rounded-r-lg">
                        <p><strong>5. Finanzas Personales:</strong> Ahorrar el 15% de mi ingreso mensual durante los próximos 12 meses para crear un fondo de emergencia equivalente a 3 meses de gastos.</p>
                    </div>
                    <div class="p-4 border-l-4 border-indigo-500 bg-indigo-50 rounded-r-lg">
                        <p><strong>6. Bienestar Físico:</strong> Realizar ejercicio físico 3 veces por semana (correr 5km o 45 min de gimnasio) durante los próximos 6 meses para mejorar mi energía y salud general.</p>
                    </div>
                    <div class="p-4 border-l-4 border-pink-500 bg-pink-50 rounded-r-lg">
                        <p><strong>7. Crecimiento Intelectual:</strong> Leer un libro de no ficción (liderazgo, tecnología, etc.) al mes durante todo el año, y escribir un breve resumen de las ideas principales.</p>
                    </div>
                    <div class="p-4 border-l-4 border-gray-500 bg-gray-100 rounded-r-lg">
                        <p><strong>8. Contribución Social:</strong> Dedicar 10 horas al mes como voluntario en una ONG local relacionada con la educación tecnológica para niños durante el próximo semestre.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Agenda de Relaciones Estratégicas -->
        <section id="relaciones" class="mb-16 fade-in" style="animation-delay: 0.6s;">
            <div class="section-card">
                <h3 class="text-3xl font-bold mb-6 text-blue-700">Agenda de Relaciones Estratégicas</h3>
                <div class="overflow-x-auto">
                    <table class="min-w-full bg-white border border-gray-200">
                        <thead class="bg-gray-100">
                            <tr>
                                <th class="text-left font-semibold py-3 px-4">Contacto</th>
                                <th class="text-left font-semibold py-3 px-4">Datos Relevantes</th>
                                <th class="text-left font-semibold py-3 px-4">Acciones para Fortalecer Vínculo</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-gray-200">
                            <tr>
                                <td class="py-3 px-4 font-medium">Ana Torres</td>
                                <td class="py-3 px-4 text-gray-600">Mentora y Directora de Proyectos en Tech Solutions. Experta en metodologías ágiles.</td>
                                <td class="py-3 px-4 text-gray-600">Agendar una llamada trimestral para ponernos al día. Compartirle artículos de interés sobre liderazgo.</td>
                            </tr>
                            <tr>
                                <td class="py-3 px-4 font-medium">Carlos Vega</td>
                                <td class="py-3 px-4 text-gray-600">Ex-compañero de universidad. Fundador de una startup de IA.</td>
                                <td class="py-3 px-4 text-gray-600">Invitarlo a un café el próximo mes para hablar sobre tendencias de IA. Felicitarlo por los logros de su empresa.</td>
                            </tr>
                            <tr>
                                <td class="py-3 px-4 font-medium">Laura Méndez</td>
                                <td class="py-3 px-4 text-gray-600">Gerente de RRHH en Innovate Corp. Contacto clave para futuras oportunidades laborales.</td>
                                <td class="py-3 px-4 text-gray-600">Interactuar con sus publicaciones en LinkedIn. Enviarle mi CV actualizado y ponerme a su disposición.</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

        <!-- Reflexión Final del Curso -->
        <section id="reflexion" class="fade-in" style="animation-delay: 0.8s;">
            <div class="section-card">
                <h3 class="text-3xl font-bold mb-6 text-blue-700">Reflexión Final del Curso</h3>
                <div class="space-y-4 text-gray-600 leading-relaxed">
                    <p>[**Aquí puedes escribir tu reflexión.**]</p>
                    <p>Ejemplo: Este curso ha sido un viaje transformador en mi autoconocimiento y desarrollo como líder. La elaboración de mi misión y el análisis FODA me dieron una claridad que antes no tenía sobre mis verdaderas fortalezas y cómo puedo apalancarlas para alcanzar mis metas. Me di cuenta de que, aunque tengo una gran capacidad para la resolución de problemas, debo trabajar activamente en mi habilidad para delegar y confiar más en mi equipo.</p>
                    <p>Definir mis objetivos con la metodología SMART los convirtió de sueños abstractos a planes de acción concretos y medibles. Ahora tengo una hoja de ruta clara para los próximos meses. La sección de relaciones estratégicas me hizo consciente de la importancia de cultivar mi red de contactos de manera intencional, no solo como una herramienta para buscar empleo, sino como una fuente de aprendizaje y colaboración. En definitiva, salgo de este curso con más confianza, un plan definido y las herramientas necesarias para liderar mi propio crecimiento de manera proactiva.</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-white mt-16 border-t">
        <div class="container mx-auto px-6 py-4 text-center text-gray-500">
            <p>&copy; 2024 [Tu Nombre Completo]. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script>
        // Script para el menú móvil
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Script para cerrar el menú al hacer clic en un enlace
        const mobileMenuLinks = mobileMenu.getElementsByTagName('a');
        for (let link of mobileMenuLinks) {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        }
    </script>

</body>
</html>
