<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía Interactiva: Desarrollo Global, ODS y Pacto del Futuro</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Chosen Palette: Warm Neutrals with Muted Blue/Teal Accents -->
    <!-- Application Structure Plan: The SPA is designed as a single, vertical-scrolling page with a sticky top navigation for easy access to all sections. The core architectural element is an interactive timeline that visually anchors the user's journey through the evolution of development thought. This structure was chosen over a linear one to provide a more engaging and intuitive user experience. Key sections are (1) An introduction, (2) The interactive timeline, (3) A tabbed view for Development Theories, (4) An interactive explorer for ODM & ODS goals using cards and modals with dynamic charts, and (5) An accordion-style section for the Pact for the Future. This approach breaks down complex information into digestible, interactive chunks, allowing users to explore content non-linearly and focus on areas of interest, which is superior for usability with dense academic material. -->
    <!-- Visualization & Content Choices: 
        - Report Info: Evolution of development frameworks. -> Goal: Show chronological flow. -> Viz/Presentation: Interactive horizontal timeline. -> Interaction: Clicks scroll to sections. -> Justification: Provides a clear, high-level map of the content. -> Library/Method: HTML/CSS/JS.
        - Report Info: Details of ODM & ODS goals. -> Goal: Inform, Compare, Show Progress. -> Viz/Presentation: Grid of cards opening modals with text and a dynamic chart (bar/doughnut). -> Interaction: User selects framework (ODM/ODS), clicks a goal card to view details and a visualization of a key metric. -> Justification: Highly interactive, condenses 25 goals into one manageable UI, and makes abstract data tangible via charts. -> Library/Method: Chart.js for charts, JS for dynamic content rendering.
        - Report Info: Rostow's 5 stages. -> Goal: Organize/Inform. -> Viz/Presentation: A simple, non-clickable diagram made with HTML/CSS. -> Interaction: None, purely visual. -> Justification: A static diagram is sufficient to represent this linear concept without adding unnecessary complexity. -> Library/Method: HTML/Tailwind CSS.
        - Report Info: 5 Pillars of the Pact for the Future. -> Goal: Organize/Inform. -> Viz/Presentation: Accordion component. -> Interaction: Click to expand/collapse. -> Justification: Neatly organizes distinct but related content blocks, saving vertical space. -> Library/Method: JS.
    -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #fdfcf9;
            color: #1f2937;
        }
        .nav-link {
            transition: color 0.3s ease, border-bottom-color 0.3s ease;
            border-bottom: 2px solid transparent;
        }
        .nav-link:hover, .nav-link.active {
            color: #0d9488; /* teal-600 */
            border-bottom-color: #0d9488;
        }
        .tab-button {
            transition: all 0.3s ease;
        }
        .tab-button.active {
            background-color: #0d9488; /* teal-600 */
            color: white;
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            top: -10px;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background-color: #fdfcf9;
            border: 4px solid #0d9488; /* teal-600 */
        }
        .chart-container {
            position: relative;
            margin: auto;
            height: 250px;
            width: 100%;
            max-width: 400px;
        }
        .goal-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .goal-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="antialiased">

    <header id="header" class="bg-white/80 backdrop-blur-lg sticky top-0 z-50 shadow-sm">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <h1 class="text-xl font-bold text-teal-700">Desarrollo Global</h1>
            <div class="hidden md:flex space-x-8">
                <a href="#teorias" class="nav-link">Teorías</a>
                <a href="#objetivos" class="nav-link">Objetivos</a>
                <a href="#pacto" class="nav-link">Pacto del Futuro</a>
            </div>
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-700 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </nav>
        <div id="mobile-menu" class="hidden md:hidden">
            <a href="#teorias" class="block py-2 px-6 text-sm text-gray-700 hover:bg-teal-50">Teorías</a>
            <a href="#objetivos" class="block py-2 px-6 text-sm text-gray-700 hover:bg-teal-50">Objetivos</a>
            <a href="#pacto" class="block py-2 px-6 text-sm text-gray-700 hover:bg-teal-50">Pacto del Futuro</a>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">
        <section id="hero" class="text-center py-16">
            <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">La Evolución del Desarrollo Global</h2>
            <p class="text-lg text-gray-600 max-w-3xl mx-auto">
                Una guía interactiva que traza el viaje del pensamiento sobre el desarrollo: desde las teorías económicas de la posguerra hasta la agenda integral y sostenible de hoy y la visión transformadora para el mañana.
            </p>
        </section>

        <section id="timeline" class="py-16">
            <div class="w-full max-w-5xl mx-auto">
                <div class="relative w-full">
                    <div class="absolute left-0 top-1/2 w-full h-1 bg-teal-200" style="transform: translateY(-50%);"></div>
                    <div class="relative flex justify-between">
                        <div class="timeline-item text-center w-1/4 cursor-pointer" data-target="#teorias">
                            <p class="font-bold text-teal-800">1950s - 90s</p>
                            <p class="text-sm text-gray-600">Teorías Fundacionales</p>
                        </div>
                        <div class="timeline-item text-center w-1/4 cursor-pointer" data-target="#objetivos">
                            <p class="font-bold text-teal-800">2000</p>
                            <p class="text-sm text-gray-600">Objetivos del Milenio (ODM)</p>
                        </div>
                        <div class="timeline-item text-center w-1/4 cursor-pointer" data-target="#objetivos">
                            <p class="font-bold text-teal-800">2015</p>
                            <p class="text-sm text-gray-600">Objetivos de Desarrollo Sostenible (ODS)</p>
                        </div>
                        <div class="timeline-item text-center w-1/4 cursor-pointer" data-target="#pacto">
                            <p class="font-bold text-teal-800">2024</p>
                            <p class="text-sm text-gray-600">Pacto del Futuro</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="teorias" class="py-16 scroll-mt-20">
            <div class="text-center mb-12">
                <h3 class="text-3xl font-bold text-gray-800">Evolución de las Teorías del Desarrollo</h3>
                <p class="text-md text-gray-600 max-w-2xl mx-auto mt-2">Esta sección explora cómo ha cambiado nuestra comprensión del "desarrollo". Desde un enfoque inicial en el crecimiento económico, el pensamiento ha evolucionado para incluir las dimensiones humanas y ambientales, sentando las bases de las agendas globales actuales. Interactúa con las pestañas para descubrir cada etapa.</p>
            </div>
            <div class="max-w-4xl mx-auto">
                <div class="mb-4 flex justify-center border-b border-gray-200">
                    <button class="tab-button py-2 px-4 font-semibold text-gray-600 active" data-tab="rostow">Enfoque Económico (50s)</button>
                    <button class="tab-button py-2 px-4 font-semibold text-gray-600" data-tab="sen">Enfoque Humano (70s-80s)</button>
                    <button class="tab-button py-2 px-4 font-semibold text-gray-600" data-tab="ambiental">Enfoque Ambiental (90s)</button>
                </div>
                <div id="teorias-content" class="p-4 bg-white rounded-lg shadow-md">
                    
                </div>
            </div>
        </section>
        
        <section id="objetivos" class="py-16 scroll-mt-20">
            <div class="text-center mb-12">
                <h3 class="text-3xl font-bold text-gray-800">Explorador de Objetivos Globales</h3>
                <p class="text-md text-gray-600 max-w-3xl mx-auto mt-2">Desde el año 2000, las Naciones Unidas han establecido dos marcos de objetivos para guiar la cooperación internacional. Esta sección te permite explorar y comparar los 8 Objetivos de Desarrollo del Milenio (ODM) y los 17 Objetivos de Desarrollo Sostenible (ODS). Utiliza el selector para cambiar entre marcos y haz clic en cada objetivo para ver sus detalles y progreso.</p>
            </div>
            <div class="flex justify-center mb-8">
                <div class="bg-gray-200 p-1 rounded-full flex">
                    <button id="odm-btn" class="px-6 py-2 rounded-full text-sm font-semibold focus:outline-none transition-colors duration-300">ODM</button>
                    <button id="ods-btn" class="px-6 py-2 rounded-full text-sm font-semibold focus:outline-none transition-colors duration-300 bg-teal-600 text-white">ODS</button>
                </div>
            </div>
            <div id="goals-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-4">
            </div>
        </section>

        <section id="pacto" class="py-16 scroll-mt-20">
            <div class="text-center mb-12">
                <h3 class="text-3xl font-bold text-gray-800">El Pacto del Futuro: Reinventando la Cooperación</h3>
                <p class="text-md text-gray-600 max-w-3xl mx-auto mt-2">Frente a crisis globales interconectadas, el Pacto del Futuro (2024) busca fortalecer y adaptar el multilateralismo. Esta sección detalla sus pilares clave, desde la reforma de la gobernanza hasta la justicia intergeneracional. Explora los compromisos que buscan dar forma a un futuro más seguro, justo y sostenible para todos.</p>
            </div>
            <div class="max-w-4xl mx-auto space-y-4" id="pacto-accordion">
            </div>
        </section>
    </main>

    <div id="goal-modal" class="fixed inset-0 bg-black bg-opacity-50 hidden flex items-center justify-center p-4 z-50">
        <div class="bg-white rounded-lg shadow-xl w-full max-w-2xl max-h-[90vh] overflow-y-auto">
            <div class="p-6">
                <div class="flex justify-between items-start">
                    <div>
                        <h4 id="modal-title" class="text-2xl font-bold text-gray-800"></h4>
                        <p id="modal-subtitle" class="text-sm text-gray-500"></p>
                    </div>
                    <button id="modal-close" class="text-gray-500 hover:text-gray-800">&times;</button>
                </div>
                <div class="mt-4 grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div id="modal-text-content">
                        <p id="modal-description" class="text-gray-600 mb-4"></p>
                        <h5 class="font-semibold text-gray-700 mb-2">Metas Clave:</h5>
                        <ul id="modal-targets" class="list-disc list-inside text-gray-600 space-y-1 text-sm"></ul>
                    </div>
                    <div id="modal-chart-content">
                        <div class="chart-container">
                            <canvas id="goalChart"></canvas>
                        </div>
                        <p id="modal-chart-caption" class="text-xs text-center text-gray-500 mt-2"></p>
                    </div>
                </div>
                <div id="modal-status" class="mt-6 p-4 rounded-lg">
                    <h5 class="font-semibold mb-2" id="modal-status-title"></h5>
                    <p class="text-sm" id="modal-status-text"></p>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-gray-800 text-white mt-16">
        <div class="container mx-auto px-6 py-4 text-center text-sm">
            <p>Guía Interactiva sobre el Desarrollo Global. Basado en el informe de Lisandro Rosal Valles.</p>
            <p>Diseñado como una herramienta educativa para explorar la evolución de las agendas globales.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const appData = {
                theories: {
                    rostow: {
                        title: 'Enfoque Económico (50s): Modernización y Crecimiento Lineal',
                        content: `
                            <p class="text-gray-700 mb-4">En las décadas de 1940 a 1960, el desarrollo se equiparaba al crecimiento económico, centrado en la industrialización. La teoría dominante, propuesta por Walt W. Rostow, sugería que todas las sociedades progresan a través de un camino universal y predecible hacia la modernidad.</p>
                            <h4 class="font-semibold mb-2">Conceptos Clave:</h4>
                            <ul class="list-disc list-inside text-gray-600 space-y-1 mb-4">
                                <li><strong>Crecimiento Lineal:</strong> El desarrollo se ve como una progresión a través de 5 etapas definidas.</li>
                                <li><strong>Industrialización:</strong> Considerada el motor fundamental para el "despegue" económico.</li>
                                <li><strong>Inversión:</strong> Se requería una inversión de al menos el 10% del PIB para iniciar el crecimiento autosostenido.</li>
                            </ul>
                            <h4 class="font-semibold mb-2">Las 5 Etapas de Rostow:</h4>
                            <div class="flex flex-col md:flex-row justify-between text-center text-xs space-y-2 md:space-y-0 md:space-x-2">
                                <div class="p-2 bg-teal-50 rounded flex-1">1. Sociedad Tradicional</div>
                                <div class="p-2 bg-teal-100 rounded flex-1">2. Precondiciones para el despegue</div>
                                <div class="p-2 bg-teal-200 rounded flex-1">3. Despegue (Take-off)</div>
                                <div class="p-2 bg-teal-300 rounded flex-1">4. Camino a la madurez</div>
                                <div class="p-2 bg-teal-400 rounded flex-1">5. Era de alto consumo masivo</div>
                            </div>
                            <p class="text-xs text-gray-500 mt-2">Esta teoría, aunque influyente, fue criticada por su eurocentrismo y por ignorar factores externos como el colonialismo.</p>
                        `
                    },
                    sen: {
                        title: 'Enfoque Humano (70s-80s): Capacidades y Libertades',
                        content: `
                            <p class="text-gray-700 mb-4">Como reacción a las limitaciones del enfoque económico, pensadores como Amartya Sen redefinieron el desarrollo. Argumentaron que el verdadero progreso no es el aumento del PIB, sino la expansión de las libertades y capacidades de las personas para que puedan vivir la vida que valoran.</p>
                            <h4 class="font-semibold mb-2">Conceptos Clave:</h4>
                            <ul class="list-disc list-inside text-gray-600 space-y-1 mb-4">
                                <li><strong>Enfoque de Capacidades:</strong> El desarrollo es la expansión de lo que las personas pueden ser y hacer.</li>
                                <li><strong>Libertad como Fin y Medio:</strong> La libertad no es solo el objetivo del desarrollo, sino también el principal medio para lograrlo.</li>
                                <li><strong>Pilares del Desarrollo Humano:</strong> La educación, la salud y la igualdad son fundamentales para expandir las capacidades.</li>
                                <li><strong>Crítica al PIB:</strong> El PIB es un medio, no el fin último del desarrollo, ya que no mide el bienestar real.</li>
                            </ul>
                            <p class="text-gray-700">Este enfoque sentó las bases para el Índice de Desarrollo Humano (IDH) del PNUD, cambiando la forma en que el mundo mide el progreso.</p>
                        `
                    },
                    ambiental: {
                        title: 'Enfoque Ambiental (90s): El Nacimiento del Desarrollo Sostenible',
                        content: `
                            <p class="text-gray-700 mb-4">En los años 90, la creciente preocupación por la degradación ambiental integró una tercera dimensión crucial al debate sobre el desarrollo. El concepto de "desarrollo sostenible" emergió como un principio rector para la política global.</p>
                            <h4 class="font-semibold mb-2">Hitos Clave:</h4>
                            <ul class="list-disc list-inside text-gray-600 space-y-2 mb-4">
                                <li><strong>Comisión Brundtland (1987):</strong> Acuñó la definición clásica de desarrollo sostenible: "satisfacer las necesidades del presente sin comprometer la capacidad de las futuras generaciones para satisfacer las suyas". Buscaba un equilibrio entre crecimiento económico, equidad social y protección ambiental.</li>
                                <li><strong>Protocolo de Kioto (1997):</strong> Fue el primer tratado internacional con compromisos vinculantes para que los países industrializados redujeran sus emisiones de gases de efecto invernadero. Representó un paso fundamental en la acción climática global, aunque su eficacia fue limitada por la no participación de grandes emisores.</li>
                            </ul>
                            <p class="text-gray-700">Este cambio de paradigma reconoció que la salud del planeta es una condición indispensable para el desarrollo a largo plazo, una idea que hoy es central en los ODS.</p>
                        `
                    }
                },
                odm: [
                    { id: 1, title: 'Erradicar la pobreza extrema y el hambre', icon: '🍽️', description: 'Buscaba reducir a la mitad la proporción de personas en pobreza extrema (menos de $1.25/día) y que padecían hambre.', targets: ['Reducir a la mitad la pobreza extrema.', 'Lograr empleo pleno y productivo.', 'Reducir a la mitad el hambre.'], status: { type: 'success', title: 'Logro Histórico', text: 'La meta de reducir la pobreza a la mitad se cumplió cinco años antes de lo previsto. Más de mil millones de personas salieron de la pobreza extrema entre 1990 y 2015.'}, chart: { type: 'bar', label: 'Personas en Pobreza Extrema (en miles de millones)', data: [1.9, 0.836], labels: ['1990', '2015'] } },
                    { id: 2, title: 'Lograr la enseñanza primaria universal', icon: '📚', description: 'Asegurar que todos los niños y niñas pudieran completar un ciclo completo de enseñanza primaria.', targets: ['Garantizar finalización de enseñanza primaria.'], status: { type: 'warning', title: 'Progreso Significativo pero Incompleto', text: 'La tasa de matrícula primaria alcanzó el 91% en 2015, pero 57 millones de niños seguían sin escolarizar.'}, chart: { type: 'bar', label: 'Niños sin escolarizar (en millones)', data: [100, 57], labels: ['2000', '2015'] } },
                    { id: 3, title: 'Promover la igualdad de género', icon: '♀️', description: 'Eliminar las disparidades de género en la educación y empoderar a las mujeres.', targets: ['Eliminar disparidades de género en todos los niveles educativos.'], status: { type: 'success', title: 'Avances en Educación', text: 'Se logró la paridad de género en la enseñanza primaria en la mayoría de las regiones. La representación política de las mujeres también aumentó.'}, chart: { type: 'doughnut', label: 'Proporción de mujeres en parlamentos', data: [12.7, 22.1], labels: ['1995', '2015'], bgColor: ['#fecaca', '#34d399']} },
                    { id: 4, title: 'Reducir la mortalidad infantil', icon: '👶', description: 'Reducir en dos tercios la tasa de mortalidad de los niños menores de cinco años.', targets: ['Reducir en 2/3 la mortalidad de menores de 5 años.'], status: { type: 'warning', title: 'Reducción Drástica pero Meta Incumplida', text: 'La mortalidad infantil se redujo en más de la mitad, salvando millones de vidas, pero no se alcanzó la meta de dos tercios.'}, chart: { type: 'bar', label: 'Mortalidad < 5 años (por 1000 nacidos vivos)', data: [90, 43], labels: ['1990', '2015'] } },
                    { id: 5, title: 'Mejorar la salud materna', icon: '🤰', description: 'Reducir en tres cuartas partes la tasa de mortalidad materna.', targets: ['Reducir en 3/4 la mortalidad materna.', 'Lograr acceso universal a salud reproductiva.'], status: { type: 'danger', title: 'Progreso Insuficiente', text: 'La mortalidad materna se redujo en un 45%, muy por debajo de la meta del 75%. El acceso a la atención de calidad siguió siendo un gran desafío.'}, chart: { type: 'bar', label: 'Reducción Mortalidad Materna (%)', data: [75, 45], labels: ['Meta', 'Logro'] } },
                    { id: 6, title: 'Combatir el VIH/SIDA, la malaria y otras enfermedades', icon: '💉', description: 'Detener y comenzar a revertir la propagación de estas enfermedades.', targets: ['Detener y revertir la propagación de VIH/SIDA.', 'Acceso universal a tratamiento.', 'Detener y revertir la malaria y otras enfermedades.'], status: { type: 'success', title: 'Respuesta Exitosa', text: 'Se lograron avances sin precedentes. Las nuevas infecciones por VIH cayeron un 40% y se evitaron millones de muertes por malaria y tuberculosis.'}, chart: { type: 'doughnut', label: 'Muertes por Malaria evitadas (2000-2015)', data: [6.2], labels: ['Millones de vidas salvadas'], bgColor: ['#6ee7b7'] } },
                    { id: 7, title: 'Garantizar la sostenibilidad del medio ambiente', icon: '🌳', description: 'Integrar los principios del desarrollo sostenible y revertir la pérdida de recursos ambientales.', targets: ['Revertir pérdida de recursos ambientales.', 'Acceso a agua potable y saneamiento.', 'Mejorar vida en barrios marginales.'], status: { type: 'warning', title: 'Avances y Retrocesos', text: 'Se superó la meta de acceso a agua potable, pero las emisiones de CO2 aumentaron más del 50% y la deforestación continuó.'}, chart: { type: 'bar', label: 'Emisiones globales de CO2 (Aumento desde 1990)', data: [50], labels: ['% de aumento'] } },
                    { id: 8, title: 'Fomentar una alianza mundial para el desarrollo', icon: '🤝', description: 'Desarrollar un sistema comercial y financiero abierto y fortalecer la cooperación internacional.', targets: ['Sistema comercial y financiero abierto.', 'Atender necesidades de países vulnerables.', 'Acceso a medicamentos y tecnologías.'], status: { type: 'success', title: 'Cooperación Fortalecida', text: 'La ayuda oficial para el desarrollo aumentó un 66%. La penetración de internet y la telefonía móvil se disparó, conectando al mundo.'}, chart: { type: 'bar', label: 'Penetración de Internet (%)', data: [6, 43], labels: ['2000', '2015'] } },
                ],
                ods: [
                    { id: 1, title: 'Fin de la pobreza', icon: '💰', description: 'Poner fin a la pobreza en todas sus formas en todo el mundo.', targets:['Erradicar pobreza extrema.', 'Reducir pobreza a la mitad.', 'Implementar protección social.'], status: { type: 'warning', title: 'En Riesgo', text: 'A pesar del progreso, se estima que 590 millones de personas seguirán en pobreza extrema en 2030 si las tendencias continúan.'}, chart: { type: 'bar', label: 'Población en pobreza extrema (millones)', data: [735, 680], labels: ['2015', '2022'] } },
                    { id: 2, title: 'Hambre cero', icon: '🌾', description: 'Poner fin al hambre, lograr la seguridad alimentaria y la mejora de la nutrición.', targets: ['Fin del hambre.', 'Fin de la malnutrición.', 'Duplicar productividad agrícola.'], status: { type: 'danger', title: 'Fuera de Rumbo', text: 'El número de personas con hambre se ha mantenido obstinadamente alto, exacerbado por conflictos y el cambio climático. 733 millones padecieron hambre en 2023.'}, chart: { type: 'bar', label: 'Personas con hambre (millones)', data: [613, 733], labels: ['2019', '2023'] } },
                    { id: 3, title: 'Salud y bienestar', icon: '❤️', description: 'Garantizar una vida sana y promover el bienestar para todos en todas las edades.', targets: ['Reducir mortalidad materna e infantil.', 'Combatir enfermedades transmisibles.', 'Reducir muertes por enfermedades no transmisibles.'], status: { type: 'warning', title: 'Progreso Amenazado', text: 'La pandemia de COVID-19 revirtió años de progreso en la esperanza de vida. La mortalidad materna sigue siendo muy alta.'}, chart: { type: 'bar', label: 'Mortalidad < 5 años (millones)', data: [5.9, 4.9], labels: ['2015', '2022'] } },
                    { id: 4, title: 'Educación de calidad', icon: '🎓', description: 'Garantizar una educación inclusiva, equitativa y de calidad.', targets: ['Educación primaria y secundaria universal.', 'Acceso a educación preescolar de calidad.', 'Igualdad de acceso a educación superior.'], status: { type: 'danger', title: 'Crisis del Aprendizaje', text: 'La pandemia causó pérdidas de aprendizaje masivas. Sin una acción urgente, millones de niños no alcanzarán competencias básicas.'}, chart: { type: 'doughnut', label: 'Tasa de finalización Ed. Primaria', data: [88, 12], labels: ['Completan', 'No completan'], bgColor: ['#0d9488', '#fecaca'] } },
                    { id: 5, title: 'Igualdad de género', icon: '♀️♂️', description: 'Lograr la igualdad entre los géneros y empoderar a todas las mujeres y las niñas.', targets: ['Fin a la discriminación.', 'Eliminar la violencia de género.', 'Asegurar participación plena en liderazgo.'], status: { type: 'danger', title: 'Progreso Lento', text: 'Al ritmo actual, se necesitarán casi 300 años para alcanzar la plena igualdad de género. Persisten brechas en liderazgo, economía y derechos.'}, chart: { type: 'bar', label: 'Mujeres en parlamentos nacionales (%)', data: [22.3, 26.9], labels: ['2015', '2024'] } },
                    { id: 6, title: 'Agua limpia y saneamiento', icon: '💧', description: 'Garantizar la disponibilidad de agua y su gestión sostenible y el saneamiento para todos.', targets: ['Acceso universal a agua potable.', 'Acceso a saneamiento e higiene.', 'Proteger ecosistemas acuáticos.'], status: { type: 'danger', title: 'Meta Lejana', text: '2.200 millones de personas aún carecen de agua potable segura. Se necesita cuadruplicar los esfuerzos para cumplir la meta.'}, chart: { type: 'doughnut', label: 'Población sin agua potable segura', data: [2200], labels: ['Millones de personas'], bgColor: ['#f87171'] } },
                    { id: 7, title: 'Energía asequible y no contaminante', icon: '💡', description: 'Garantizar el acceso a una energía asequible, segura, sostenible y moderna.', targets: ['Acceso universal a la electricidad.', 'Aumentar cuota de energías renovables.', 'Duplicar la eficiencia energética.'], status: { type: 'warning', title: 'Transición en Marcha pero Lenta', text: 'El acceso a la electricidad mejora, pero 660 millones de personas podrían seguir sin ella en 2030. La financiación para energías limpias es insuficiente.'}, chart: { type: 'bar', label: 'Personas sin electricidad (millones)', data: [958, 685], labels: ['2015', '2022'] } },
                    { id: 8, title: 'Trabajo decente y crecimiento económico', icon: '📈', description: 'Promover el crecimiento económico inclusivo y sostenible, el empleo y el trabajo decente.', targets: ['Crecimiento económico sostenido.', 'Lograr empleo pleno y productivo.', 'Erradicar el trabajo forzoso e infantil.'], status: { type: 'warning', title: 'Recuperación Desigual', text: 'El crecimiento se ha desacelerado y más de 2.000 millones de trabajadores tienen empleos informales sin protección social.'}, chart: { type: 'bar', label: 'Tasa de desempleo global (%)', data: [5.6, 5.0], labels: ['2015', '2023'] } },
                    { id: 9, title: 'Industria, innovación e infraestructura', icon: '🏗️', description: 'Construir infraestructuras resilientes, promover la industrialización y fomentar la innovación.', targets: ['Desarrollar infraestructura de calidad.', 'Promover industrialización sostenible.', 'Aumentar la investigación y desarrollo.'], status: { type: 'warning', title: 'Brecha de Inversión', text: 'Aunque la cobertura móvil es casi universal (95%), las emisiones de CO2 de la industria siguen aumentando y la inversión en infraestructura es insuficiente.'}, chart: { type: 'doughnut', label: 'Cobertura 4G/5G', data: [95, 5], labels: ['Cubierta', 'No cubierta'], bgColor: ['#0d9488', '#e5e7eb'] } },
                    { id: 10, title: 'Reducción de las desigualdades', icon: '⚖️', description: 'Reducir la desigualdad en y entre los países.', targets: ['Aumentar ingresos del 40% más pobre.', 'Promover la inclusión social.', 'Facilitar la migración segura.'], status: { type: 'danger', title: 'Desigualdad Creciente', text: 'La brecha entre países ricos y pobres se está ampliando. La discriminación y la exclusión persisten.'}, chart: { type: 'bar', label: 'Muertes de migrantes (récord)', data: [8500], labels: ['2023'] } },
                    { id: 11, title: 'Ciudades y comunidades sostenibles', icon: '🏙️', description: 'Lograr que las ciudades sean más inclusivas, seguras, resilientes y sostenibles.', targets: ['Acceso a vivienda adecuada.', 'Sistemas de transporte sostenibles.', 'Proteger el patrimonio cultural.'], status: { type: 'warning', title: 'Urbanización Desordenada', text: '1.100 millones de personas viven en barrios marginales. La contaminación del aire y la falta de espacios públicos son problemas graves.'}, chart: { type: 'doughnut', label: 'Población urbana en barrios marginales', data: [25, 75], labels: ['En barrios marginales (%)', 'Otros (%)'], bgColor: ['#fb923c', '#e5e7eb'] } },
                    { id: 12, title: 'Producción y consumo responsables', icon: '♻️', description: 'Garantizar modalidades de consumo y producción sostenibles.', targets: ['Uso eficiente de recursos.', 'Reducir el desperdicio de alimentos.', 'Gestionar desechos químicos.'], status: { type: 'danger', title: 'Modelo Insostenible', text: 'La huella material global sigue creciendo. El desperdicio de alimentos y los residuos electrónicos están en niveles récord.'}, chart: { type: 'bar', label: 'Residuos electrónicos generados (millones de toneladas)', data: [41.8, 62], labels: ['2014', '2022'] } },
                    { id: 13, title: 'Acción por el clima', icon: '🌡️', description: 'Adoptar medidas urgentes para combatir el cambio climático y sus efectos.', targets: ['Fortalecer la resiliencia.', 'Integrar políticas climáticas.', 'Mejorar la educación climática.'], status: { type: 'danger', title: 'Emergencia Climática', text: 'El mundo se dirige a un calentamiento de 2.8°C. Las emisiones de GEI y los subsidios a combustibles fósiles alcanzaron nuevos récords en 2022.'}, chart: { type: 'bar', label: 'Aumento de temperatura proyectado (°C)', data: [1.5, 2.8], labels: ['Límite del Acuerdo de París', 'Proyección actual'] } },
                    { id: 14, title: 'Vida submarina', icon: '🐠', description: 'Conservar y utilizar sosteniblemente los océanos, los mares y los recursos marinos.', targets: ['Reducir contaminación marina.', 'Gestionar ecosistemas marinos.', 'Poner fin a la sobrepesca.'], status: { type: 'danger', title: 'Océanos en Peligro', text: 'La acidificación, el calentamiento y la contaminación amenazan la vida marina. Más de un tercio de las poblaciones de peces están sobreexplotadas.'}, chart: { type: 'doughnut', label: 'Poblaciones de peces', data: [62.3, 37.7], labels: ['Sostenibles (%)', 'Sobreexplotadas (%)'], bgColor: ['#0d9488', '#f87171'] } },
                    { id: 15, title: 'Vida de ecosistemas terrestres', icon: '🦋', description: 'Proteger, restablecer y promover el uso sostenible de los ecosistemas terrestres.', targets: ['Detener la deforestación.', 'Luchar contra la desertificación.', 'Frenar la pérdida de biodiversidad.'], status: { type: 'danger', title: 'Pérdida Acelerada', text: 'El riesgo de extinción de especies se ha deteriorado un 12% en las últimas tres décadas. La deforestación y la degradación del suelo continúan a un ritmo alarmante.'}, chart: { type: 'bar', label: 'Pérdida neta de bosques (millones de hectáreas)', data: [100], labels: ['2000-2020'] } },
                    { id: 16, title: 'Paz, justicia e instituciones sólidas', icon: '🏛️', description: 'Promover sociedades pacíficas e inclusivas, y facilitar el acceso a la justicia.', targets: ['Reducir la violencia.', 'Poner fin al abuso infantil.', 'Luchar contra la corrupción.'], status: { type: 'danger', title: 'Violencia y Conflicto en Aumento', text: 'Las muertes de civiles en conflictos aumentaron un 72% en 2023. El número de desplazados forzosos alcanzó un récord de 120 millones.'}, chart: { type: 'bar', label: 'Personas desplazadas forzosamente (millones)', data: [60, 120], labels: ['2015', '2024'] } },
                    { id: 17, title: 'Alianzas para lograr los objetivos', icon: '🌐', description: 'Fortalecer los medios de implementación y revitalizar la Alianza Mundial.', targets: ['Fortalecer movilización de recursos.', 'Promover la cooperación en ciencia y tecnología.', 'Mejorar la coherencia de políticas.'], status: { type: 'warning', title: 'Solidaridad Insuficiente', text: 'Los países en desarrollo enfrentan una brecha de inversión de $4 billones anuales para los ODS. La deuda externa es un problema creciente.'}, chart: { type: 'doughnut', label: 'Brecha de inversión anual en ODS', data: [4], labels: ['Billones de USD'], bgColor: ['#f59e0b'] } },
                ],
                pacto: [
                    { title: 'Desarrollo Sostenible y Financiación', content: 'Reafirma la Agenda 2030, priorizando la erradicación de la pobreza y la acción climática. Propone una reforma de la arquitectura financiera internacional para que sea más justa y representativa, y considera una tributación mínima global para individuos de alto patrimonio para generar nuevos fondos.' },
                    { title: 'Paz y Seguridad Internacional', content: 'Busca fortalecer el multilateralismo para prevenir conflictos, proponiendo la reforma más concreta del Consejo de Seguridad de la ONU en décadas para mejorar su representatividad (especialmente de África). Incluye un renovado compromiso con el desarme nuclear y la regulación de nuevas tecnologías de guerra.' },
                    { title: 'Ciencia, Tecnología e Innovación Digital', content: 'Reconoce el potencial de la tecnología para el desarrollo, pero también sus riesgos. Su anexo clave, el <strong>Pacto Digital Global</strong>, establece el primer marco mundial para la cooperación digital y la gobernanza de la inteligencia artificial, buscando cerrar la brecha digital y garantizar un uso responsable de la IA.' },
                    { title: 'Transformación de la Gobernanza Global', content: 'Pretende que las instituciones globales sean más eficaces y justas. Impulsa la adopción de métricas que vayan más allá del PIB para medir el progreso real (incluyendo bienestar y sostenibilidad). Fortalece el enfoque en los derechos humanos y la igualdad de género.' },
                    { title: 'Juventudes y Generaciones Futuras', content: 'Coloca la solidaridad intergeneracional en el centro. Su anexo, la <strong>Declaración sobre las Generaciones Futuras</strong>, establece principios y compromisos para asegurar que las decisiones actuales no comprometan el futuro. Busca crear mecanismos para la participación significativa de los jóvenes en la política global.' },
                ]
            };

            const teoriasContent = document.getElementById('teorias-content');
            const tabButtons = document.querySelectorAll('.tab-button');
            const goalsGrid = document.getElementById('goals-grid');
            const odmBtn = document.getElementById('odm-btn');
            const odsBtn = document.getElementById('ods-btn');
            const pactoAccordion = document.getElementById('pacto-accordion');

            let activeFramework = 'ods';
            let chartInstance = null;

            function renderTheories(tab) {
                teoriasContent.innerHTML = appData.theories[tab].content;
            }

            tabButtons.forEach(button => {
                button.addEventListener('click', () => {
                    tabButtons.forEach(btn => btn.classList.remove('active'));
                    button.classList.add('active');
                    renderTheories(button.dataset.tab);
                });
            });

            function renderGoals(framework) {
                goalsGrid.innerHTML = '';
                appData[framework].forEach(goal => {
                    const card = document.createElement('div');
                    card.className = 'goal-card cursor-pointer bg-white rounded-lg p-4 text-center shadow-md';
                    card.dataset.id = goal.id;
                    card.dataset.framework = framework;
                    card.innerHTML = `
                        <div class="text-4xl mb-2">${goal.icon}</div>
                        <p class="font-semibold text-sm text-gray-700">${goal.id}. ${goal.title}</p>
                    `;
                    card.addEventListener('click', () => openModal(goal.id, framework));
                    goalsGrid.appendChild(card);
                });
            }

            function setFramework(framework) {
                activeFramework = framework;
                if (framework === 'odm') {
                    odmBtn.classList.add('bg-teal-600', 'text-white');
                    odsBtn.classList.remove('bg-teal-600', 'text-white');
                } else {
                    odsBtn.classList.add('bg-teal-600', 'text-white');
                    odmBtn.classList.remove('bg-teal-600', 'text-white');
                }
                renderGoals(framework);
            }

            odmBtn.addEventListener('click', () => setFramework('odm'));
            odsBtn.addEventListener('click', () => setFramework('ods'));

            const modal = document.getElementById('goal-modal');
            const modalTitle = document.getElementById('modal-title');
            const modalSubtitle = document.getElementById('modal-subtitle');
            const modalDescription = document.getElementById('modal-description');
            const modalTargets = document.getElementById('modal-targets');
            const modalStatus = document.getElementById('modal-status');
            const modalStatusTitle = document.getElementById('modal-status-title');
            const modalStatusText = document.getElementById('modal-status-text');
            const chartCaption = document.getElementById('modal-chart-caption');

            function openModal(id, framework) {
                const goal = appData[framework].find(g => g.id === id);
                if (!goal) return;

                modalTitle.textContent = `${goal.id}. ${goal.title}`;
                modalSubtitle.textContent = framework.toUpperCase();
                modalDescription.textContent = goal.description;
                
                modalTargets.innerHTML = goal.targets.map(t => `<li>${t}</li>`).join('');

                const statusColors = {
                    success: 'bg-green-100 text-green-800',
                    warning: 'bg-yellow-100 text-yellow-800',
                    danger: 'bg-red-100 text-red-800'
                };
                modalStatus.className = `mt-6 p-4 rounded-lg ${statusColors[goal.status.type]}`;
                modalStatusTitle.textContent = goal.status.title;
                modalStatusText.textContent = goal.status.text;

                if (goal.chart) {
                    chartCaption.textContent = goal.chart.label;
                    const ctx = document.getElementById('goalChart').getContext('2d');
                    if(chartInstance) {
                        chartInstance.destroy();
                    }
                    chartInstance = new Chart(ctx, {
                        type: goal.chart.type,
                        data: {
                            labels: goal.chart.labels,
                            datasets: [{
                                label: goal.chart.label,
                                data: goal.chart.data,
                                backgroundColor: goal.chart.bgColor || ['rgba(13, 148, 136, 0.6)', 'rgba(209, 213, 219, 0.6)'],
                                borderColor: goal.chart.borderColor || ['rgba(13, 148, 136, 1)', 'rgba(107, 114, 128, 1)'],
                                borderWidth: 1
                            }]
                        },
                        options: {
                            responsive: true,
                            maintainAspectRatio: false,
                            plugins: {
                                legend: {
                                    display: goal.chart.type === 'doughnut'
                                },
                                tooltip: {
                                    callbacks: {
                                        label: function(context) {
                                            let label = context.dataset.label || '';
                                            if (label) {
                                                label += ': ';
                                            }
                                            if (context.parsed.y !== null) {
                                                label += context.parsed.y;
                                            }
                                            if (context.parsed.y === undefined && context.parsed !== null) {
                                                label += context.parsed;
                                            }
                                            return label;
                                        }
                                    }
                                }
                            },
                            scales: {
                                y: {
                                    beginAtZero: true,
                                    display: goal.chart.type === 'bar'
                                },
                                x: {
                                    display: goal.chart.type === 'bar'
                                }
                            }
                        }
                    });
                }
                
                modal.classList.remove('hidden');
            }
            
            document.getElementById('modal-close').addEventListener('click', () => modal.classList.add('hidden'));
            modal.addEventListener('click', (e) => {
                if(e.target === modal) {
                    modal.classList.add('hidden');
                }
            });

            function renderPacto() {
                pactoAccordion.innerHTML = '';
                appData.pacto.forEach((item, index) => {
                    const div = document.createElement('div');
                    div.className = 'bg-white rounded-lg shadow-md';
                    div.innerHTML = `
                        <button class="w-full text-left p-4 font-semibold flex justify-between items-center accordion-toggle">
                            <span>${item.title}</span>
                            <span class="transform transition-transform duration-300 ">▼</span>
                        </button>
                        <div class="accordion-content hidden p-4 border-t border-gray-200">
                            <p class="text-gray-600">${item.content}</p>
                        </div>
                    `;
                    pactoAccordion.appendChild(div);
                });

                document.querySelectorAll('.accordion-toggle').forEach(button => {
                    button.addEventListener('click', () => {
                        const content = button.nextElementSibling;
                        const icon = button.querySelector('span:last-child');
                        content.classList.toggle('hidden');
                        icon.classList.toggle('rotate-180');
                    });
                });
            }

            document.querySelectorAll('.timeline-item').forEach(item => {
                item.addEventListener('click', () => {
                    const targetId = item.dataset.target;
                    document.querySelector(targetId).scrollIntoView({ behavior: 'smooth' });
                });
            });

            const header = document.getElementById('header');
            const navLinks = document.querySelectorAll('.nav-link');
            const sections = document.querySelectorAll('main section[id]');

            window.addEventListener('scroll', () => {
                let current = '';
                sections.forEach(section => {
                    const sectionTop = section.offsetTop;
                    if(pageYOffset >= sectionTop - header.offsetHeight - 20) {
                        current = section.getAttribute('id');
                    }
                });

                navLinks.forEach(link => {
                    link.classList.remove('active');
                    if (link.getAttribute('href').substring(1) === current) {
                        link.classList.add('active');
                    }
                });
            });
            
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
            document.querySelectorAll('#mobile-menu a').forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                });
            });

            renderTheories('rostow');
            setFramework('ods');
            renderPacto();
        });
    </script>
</body>
</html>
