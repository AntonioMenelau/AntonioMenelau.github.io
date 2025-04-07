<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio - Antonio Menelau | Full Stack Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Fontes do Google -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Ícones -->
    <script src="https://unpkg.com/@heroicons/v2.0.18/24/outline/index.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #2563eb);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .skill-card:hover {
            transform: translateY(-5px);
        }
        .project-card:hover img {
            transform: scale(1.05);
        }
        .project-card img {
            transition: transform 0.5s ease;
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
    <!-- Barra de Navegação -->
    <nav class="bg-white shadow-lg fixed w-full z-50 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <div class="flex items-center">
                    <span class="text-2xl font-bold text-blue-600">{"/Dev"}</span>
                    <span class="ml-2 text-xl font-semibold">Antonio Menelau</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-600 hover:text-blue-600 transition">Home</a>
                    <a href="#sobre" class="text-gray-600 hover:text-blue-600 transition">Sobre</a>
                    <a href="#projetos" class="text-gray-600 hover:text-blue-600 transition">Projetos</a>
                    <a href="#skills" class="text-gray-600 hover:text-blue-600 transition">Skills</a>
                    <a href="#contato" class="text-gray-600 hover:text-blue-600 transition">Contato</a>
                </div>
                <div class="md:hidden">
                    <button id="menu-button" class="text-gray-600 focus:outline-none">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Menu Mobile -->
        <div id="mobile-menu" class="hidden md:hidden bg-white pb-4 px-4">
            <a href="#home" class="block py-2 text-gray-600 hover:text-blue-600">Home</a>
            <a href="#sobre" class="block py-2 text-gray-600 hover:text-blue-600">Sobre</a>
            <a href="#projetos" class="block py-2 text-gray-600 hover:text-blue-600">Projetos</a>
            <a href="#skills" class="block py-2 text-gray-600 hover:text-blue-600">Skills</a>
            <a href="#contato" class="block py-2 text-gray-600 hover:text-blue-600">Contato</a>
        </div>
    </nav>

    <!-- Seção Hero -->
    <section id="home" class="pt-32 pb-20 px-4 bg-gradient-to-b from-white to-blue-50">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between">
            <div class="md:w-1/2 text-center md:text-left mb-10 md:mb-0">
                <p class="text-blue-600 font-semibold mb-2">Olá, eu sou</p>
                <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-4">
                    Antonio Menelau
                </h1>
                <h2 class="text-3xl md:text-4xl font-bold gradient-text mb-6">
                    Desenvolvedor Full Stack
                </h2>
                <p class="text-xl text-gray-600 mb-8 max-w-xl">
                    Transformando ideias em soluções digitais robustas e escaláveis com foco em performance e experiência do usuário.
                </p>
                <div class="flex flex-wrap gap-4 justify-center md:justify-start">
                    <a href="#contato" class="bg-blue-600 text-white px-8 py-3 rounded-lg hover:bg-blue-700 transition shadow-md">
                        Vamos conversar!
                    </a>
                    <a href="#projetos" class="border-2 border-blue-600 text-blue-600 px-8 py-3 rounded-lg hover:bg-blue-50 transition">
                        Ver projetos
                    </a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative">
                    <div class="w-64 h-64 md:w-80 md:h-80 rounded-full bg-blue-100 overflow-hidden flex items-center justify-center border-4 border-white shadow-xl">
                        <!-- Substitua por sua foto ou mantenha como está -->
                        <img src="Antonio-Menelau.png" alt="Antonio Menelau" class="w-full h-full object-cover">
                    </div>
                    <div class="absolute -bottom-4 -right-4 bg-white p-3 rounded-full shadow-lg">
                        <i class="fab fa-python text-3xl text-blue-600"></i>
                    </div>
                </div>
            </div>
        </div>
        <!-- Tecnologias/Linguagens em destaque -->
        <div class="max-w-7xl mx-auto mt-16">
            <div class="p-6 bg-white rounded-xl shadow-md">
                <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12">
                    <div class="text-center">
                        <i class="fab fa-python text-4xl text-gray-700 mb-2"></i>
                        <p class="text-sm font-medium">Python</p>
                    </div>
                    <div class="text-center">
                        <i class="fab fa-js text-4xl text-gray-700 mb-2"></i>
                        <p class="text-sm font-medium">JavaScript</p>
                    </div>
                    <div class="text-center">
                        <i class="fab fa-react text-4xl text-gray-700 mb-2"></i>
                        <p class="text-sm font-medium">React</p>
                    </div>
                    <div class="text-center">
                        <i class="fab fa-node-js text-4xl text-gray-700 mb-2"></i>
                        <p class="text-sm font-medium">Node.js</p>
                    </div>
                    <div class="text-center">
                        <i class="fab fa-html5 text-4xl text-gray-700 mb-2"></i>
                        <p class="text-sm font-medium">HTML5/CSS3</p>
                    </div>
                    <div class="text-center">
                        <i class="fas fa-database text-4xl text-gray-700 mb-2"></i>
                        <p class="text-sm font-medium">SQL/NoSQL</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Sobre Mim -->
    <section id="sobre" class="py-20 px-4">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 relative">
                Sobre <span class="gradient-text">Mim</span>
                <div class="absolute w-20 h-1 bg-blue-600 bottom-0 left-1/2 transform -translate-x-1/2 mt-2"></div>
            </h2>
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2">
                    <div class="bg-white p-6 shadow-lg rounded-xl border-l-4 border-blue-600">
                        <h3 class="text-2xl font-semibold mb-4">Minha Jornada</h3>
                        <p class="text-gray-600 mb-4">
                            Desenvolvedor Full Stack apaixonado por criar soluções tecnológicas que resolvem problemas reais. Com 3 anos de experiência no desenvolvimento de aplicações web, tenho focado principalmente em Python e ecossistema JavaScript.
                        </p>
                        <p class="text-gray-600 mb-4">
                            Tenho experiência no desenvolvimento de aplicações escaláveis, automatização de processos e implementação de interfaces intuitivas e responsivas.
                        </p>
                        <p class="text-gray-600">
                            Minha abordagem combina pensamento analítico com práticas de desenvolvimento modernas para criar software robusto, testável e de alta qualidade.
                        </p>
                    </div>
                    <div class="flex flex-wrap gap-4 mt-6">
                        <div class="flex items-center bg-blue-50 p-3 rounded-lg">
                            <i class="fas fa-code text-blue-600 mr-2"></i>
                            <span class="font-medium">15+ Projetos</span>
                        </div>
                        <div class="flex items-center bg-blue-50 p-3 rounded-lg">
                            <i class="fas fa-briefcase text-blue-600 mr-2"></i>
                            <span class="font-medium">4+ Anos de Experiência</span>
                        </div>
                        <div class="flex items-center bg-blue-50 p-3 rounded-lg">
                            <i class="fas fa-user-graduate text-blue-600 mr-2"></i>
                            <span class="font-medium">Graduação em Analise e Desenvolvimento de Sistema</span>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2 space-y-4">
                    <div class="bg-white p-5 rounded-xl shadow hover:shadow-md transition">
                        <h4 class="text-xl font-semibold mb-2 flex items-center">
                            <i class="fas fa-laptop-code text-blue-600 mr-2"></i>
                            Desenvolvimento Web
                        </h4>
                        <p class="text-gray-600">
                            Criação de aplicações web completas, desde o back-end até interfaces responsivas e acessíveis.
                        </p>
                    </div>
                    <div class="bg-white p-5 rounded-xl shadow hover:shadow-md transition">
                        <h4 class="text-xl font-semibold mb-2 flex items-center">
                            <i class="fas fa-robot text-blue-600 mr-2"></i>
                            Automação
                        </h4>
                        <p class="text-gray-600">
                            Desenvolvimento de scripts e ferramentas para automação de processos e tarefas repetitivas.
                        </p>
                    </div>
                    <div class="bg-white p-5 rounded-xl shadow hover:shadow-md transition">
                        <h4 class="text-xl font-semibold mb-2 flex items-center">
                            <i class="fas fa-database text-blue-600 mr-2"></i>
                            Banco de Dados
                        </h4>
                        <p class="text-gray-600">
                            Modelagem, otimização e administração de bancos de dados SQL e NoSQL.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Skills -->
    <section id="skills" class="py-20 bg-white px-4">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 relative">
                Minhas <span class="gradient-text">Habilidades</span>
                <div class="absolute w-20 h-1 bg-blue-600 bottom-0 left-1/2 transform -translate-x-1/2 mt-2"></div>
            </h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Front-end -->
                <div class="p-6 border rounded-xl hover:shadow-lg transition skill-card bg-white">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 p-3 rounded-lg">
                            <i class="fas fa-code text-blue-600 text-xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold ml-3">Front-end</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>JavaScript/TypeScript</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>HTML5, CSS3</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Tailwind CSS, Bootstrap</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Responsive Design</span>
                        </li>
                    </ul>
                </div>

                <!-- Back-end -->
                <div class="p-6 border rounded-xl hover:shadow-lg transition skill-card bg-white">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 p-3 rounded-lg">
                            <i class="fas fa-server text-blue-600 text-xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold ml-3">Back-end</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Django, Flask</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>FastAPI</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>REST APIs</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>SQL (PostgreSQL, MySQL, SQLite)</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Docker, Git</span>
                        </li>
                    </ul>
                </div>

                <!-- Python -->
                <div class="p-6 border rounded-xl hover:shadow-lg transition skill-card bg-white">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 p-3 rounded-lg">
                            <i class="fab fa-python text-blue-600 text-xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold ml-3">Python</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Automação</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Pandas, NumPy</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Análise de Dados</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Pytest</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>API Integration</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <!-- Barra de progresso de habilidades adicionais -->
            <div class="mt-16 bg-white p-8 rounded-xl shadow">
                <h3 class="text-2xl font-semibold mb-6">Outras Habilidades</h3>
                <div class="space-y-6">
                    <div>
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Metodologias Ágeis</span>
                            <span>90%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 90%"></div>
                        </div>
                    </div>
                    <div>
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">UI/UX Design</span>
                            <span>85%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 85%"></div>
                        </div>
                    </div>
                    <div>
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">DevOps</span>
                            <span>80%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 80%"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Projetos -->
    <section id="projetos" class="py-20 px-4 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 relative">
                Projetos <span class="gradient-text">Destacados</span>
                <div class="absolute w-20 h-1 bg-blue-600 bottom-0 left-1/2 transform -translate-x-1/2 mt-2"></div>
            </h2>
            
            <!-- Filtro de Projetos -->
            <div class="flex flex-wrap justify-center gap-4 mb-12">
                <button class="px-4 py-2 bg-blue-600 text-white rounded-full shadow-md hover:bg-blue-700 transition">Todos</button>
                <button class="px-4 py-2 bg-white text-gray-700 rounded-full shadow-md hover:bg-gray-100 transition">Web</button>
                <button class="px-4 py-2 bg-white text-gray-700 rounded-full shadow-md hover:bg-gray-100 transition">Automação</button>
                <button class="px-4 py-2 bg-white text-gray-700 rounded-full shadow-md hover:bg-gray-100 transition">API</button>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card Projeto 1 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition project-card">
                    <div class="overflow-hidden h-48">
                        <img src="/api/placeholder/600/400" alt="Sistema de Automação" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Sistema de Automação</h3>
                        <p class="text-gray-600 mb-4">Sistema completo de automação de processos empresariais usando Python e Selenium com dashboard em React.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">Python</span>
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">Selenium</span>
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">React</span>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:underline flex items-center">
                                <i class="fab fa-github mr-1"></i> Código
                            </a>
                            <a href="#" class="text-blue-600 hover:underline flex items-center">
                                <i class="fas fa-external-link-alt mr-1"></i> Demo
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Card Projeto 2 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition project-card">
                    <div class="overflow-hidden h-48">
                        <img src="/api/placeholder/600/400" alt="E-commerce Dashboard" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">E-commerce Dashboard</h3>
                        <p class="text-gray-600 mb-4">Dashboard administrativo para plataforma de e-commerce com análise de vendas e gerenciamento de produtos.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">Next.js</span>
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">Django</span>
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">PostgreSQL</span>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:underline flex items-center">
                                <i class="fab fa-github mr-1"></i> Código
                            </a>
                            <a href="#" class="text-blue-600 hover:underline flex items-center">
                                <i class="fas fa-external-link-alt mr-1"></i> Demo
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Card Projeto 3 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition project-card">
                    <div class="overflow-hidden h-48">
                        <img src="/api/placeholder/600/400" alt="API RESTful" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">API RESTful</h3>
                        <p class="text-gray-600 mb-4">API completa para sistema de gerenciamento de tarefas com autenticação JWT e documentação automática.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">FastAPI</span>
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">Pydantic</span>
                            <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded text-sm font-medium">SQLAlchemy</span>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:underline flex items-center">
                                <i class="fab fa-github mr-1"></i> Código
                            </a>
                            <a href="#" class="text-blue-600 hover:underline flex items-center">
                                <i class="fas fa-external-link-alt mr-1"></i> Docs
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Ver Mais Projetos -->
            <div class="text-center mt-12">
                <a href="https://github.com/AntonioMenelau" target="_blank" class="inline-flex items-center px-6 py-3 bg-white border border-blue-600 text-blue-600 rounded-lg hover:bg-blue-50 transition shadow-sm">
                    <i class="fab fa-github mr-2"></i>
                    Ver mais projetos no GitHub
                </a>
            </div>
        </div>
    </section>

    <!-- Seção Estatísticas -->
    <section class="py-16 bg-blue-600 text-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-2 md:grid-cols-3 gap-8 text-center">
                <div>
                    <div class="text-4xl font-bold mb-2">15+</div>
                    <p class="text-blue-100">Projetos Completos</p>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">4+</div>
                    <p class="text-blue-100">Anos de Experiência</p>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">17+</div>
                    <p class="text-blue-100">Contribuições Open Source</p>
                </div>
            </div>
        </div>
    </section>

<!-- Seção Testemunhos -->
    <section class="py-20 px-4 bg-white">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 relative">
                O que <span class="gradient-text">Dizem</span>
                <div class="absolute w-20 h-1 bg-blue-600 bottom-0 left-1/2 transform -translate-x-1/2 mt-2"></div>
            </h2>
        
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-6 rounded-xl shadow-md hover:shadow-lg transition">
                    <div class="flex items-center mb-4">
                        <img src="/api/placeholder/50/50" alt="Cliente" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-semibold">Ana Silva</h4>
                            <p class="text-gray-600 text-sm">CEO, Empresa ABC</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        "Trabalhar com este desenvolvedor foi uma experiência extraordinária. A capacidade técnica aliada à comunicação clara e entrega no prazo fizeram toda a diferença em nosso projeto."
                    </p>
                    <div class="flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testemunho 2 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md hover:shadow-lg transition">
                    <div class="flex items-center mb-4">
                        <img src="/api/placeholder/50/50" alt="Cliente" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-semibold">Carlos Mendes</h4>
                            <p class="text-gray-600 text-sm">CTO, Startup XYZ</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        "A qualidade do código e a atenção aos detalhes impressionam. Conseguiu resolver problemas complexos com soluções elegantes que superaram nossas expectativas."
                    </p>
                    <div class="flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testemunho 3 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md hover:shadow-lg transition">
                    <div class="flex items-center mb-4">
                        <img src="/api/placeholder/50/50" alt="Cliente" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-semibold">Mariana Costa</h4>
                            <p class="text-gray-600 text-sm">Gestora de Projetos</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        "Além de entregar um produto de altíssima qualidade, sua capacidade de entender as necessidades do negócio e propor melhorias fez toda a diferença em nosso projeto."
                    </p>
                    <div class="flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Contato -->
    <section id="contato" class="py-20 px-4 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 relative">
                Entre em <span class="gradient-text">Contato</span>
                <div class="absolute w-20 h-1 bg-blue-600 bottom-0 left-1/2 transform -translate-x-1/2 mt-2"></div>
            </h2>
            
            <div class="flex flex-col md:flex-row gap-10">
                <!-- Formulário de Contato -->
                <div class="md:w-2/3 bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-2xl font-semibold mb-6">Envie uma mensagem</h3>
                    <form>
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                            <div>
                                <label for="name" class="block text-gray-700 mb-2">Nome</label>
                                <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" placeholder="Seu nome">
                            </div>
                            <div>
                                <label for="email" class="block text-gray-700 mb-2">Email</label>
                                <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" placeholder="seu.email@exemplo.com">
                            </div>
                        </div>
                        <div class="mb-6">
                            <label for="subject" class="block text-gray-700 mb-2">Assunto</label>
                            <input type="text" id="subject" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" placeholder="Assunto da mensagem">
                        </div>
                        <div class="mb-6">
                            <label for="message" class="block text-gray-700 mb-2">Mensagem</label>
                            <textarea id="message" rows="5" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" placeholder="Sua mensagem..."></textarea>
                        </div>
                        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition shadow-md">
                            Enviar Mensagem
                        </button>
                    </form>
                </div>
                
                <!-- Informações de Contato -->
                <div class="md:w-1/3 space-y-6">
                    <div class="bg-white p-6 rounded-xl shadow-md">
                        <h3 class="text-xl font-semibold mb-4">Informações de Contato</h3>
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <div class="bg-blue-100 p-3 rounded-full mr-4">
                                    <i class="fas fa-map-marker-alt text-blue-600"></i>
                                </div>
                                <div>
                                    <h4 class="font-medium">Localização</h4>
                                    <p class="text-gray-600">Mococa, SP - Brasil</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="bg-blue-100 p-3 rounded-full mr-4">
                                    <i class="fas fa-envelope text-blue-600"></i>
                                </div>
                                <div>
                                    <h4 class="font-medium">Email</h4>
                                    <p class="text-gray-600">tonimenelau@gmail.com</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="bg-blue-100 p-3 rounded-full mr-4">
                                    <i class="fas fa-phone text-blue-600"></i>
                                </div>
                                <div>
                                    <h4 class="font-medium">Telefone</h4>
                                    <p class="text-gray-600">+55 (19) 99419-7105</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Redes Sociais -->
                    <div class="bg-white p-6 rounded-xl shadow-md">
                        <h3 class="text-xl font-semibold mb-4">Redes Sociais</h3>
                        <div class="flex flex-wrap gap-3">
                            <a href="#" class="bg-blue-600 text-white p-3 rounded-full hover:bg-blue-700 transition">
                                <i class="fab fa-linkedin-in"></i>
                            </a>
                            <a href="#" class="bg-gray-800 text-white p-3 rounded-full hover:bg-black transition">
                                <i class="fab fa-github"></i>
                            </a>
                            <a href="#" class="bg-blue-400 text-white p-3 rounded-full hover:bg-blue-500 transition">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="bg-red-600 text-white p-3 rounded-full hover:bg-red-700 transition">
                                <i class="fab fa-youtube"></i>
                            </a>
                            <a href="#" class="bg-pink-600 text-white p-3 rounded-full hover:bg-pink-700 transition">
                                <i class="fab fa-instagram"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <div class="flex items-center">
                        <span class="text-2xl font-bold text-blue-400">{"/Dev"}</span>
                        <span class="ml-2 text-xl font-semibold">Antonio Menelau</span>
                    </div>
                    <p class="mt-2 text-gray-400">
                        Desenvolvedor Full Stack apaixonado por criar<br>
                        soluções web de alta qualidade.
                    </p>
                </div>
                
                <div class="flex flex-wrap gap-8">
                    <div>
                        <h4 class="text-lg font-semibold mb-3">Links Rápidos</h4>
                        <ul class="space-y-2">
                            <li><a href="#home" class="text-gray-400 hover:text-white transition">Home</a></li>
                            <li><a href="#sobre" class="text-gray-400 hover:text-white transition">Sobre</a></li>
                            <li><a href="#projetos" class="text-gray-400 hover:text-white transition">Projetos</a></li>
                            <li><a href="#skills" class="text-gray-400 hover:text-white transition">Skills</a></li>
                        </ul>
                    </div>
                    
                    <div>
                        <h4 class="text-lg font-semibold mb-3">Recursos</h4>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-gray-400 hover:text-white transition">Blog</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white transition">GitHub</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white transition">LinkedIn</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white transition">Currículo</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <hr class="my-8 border-gray-700">
            
            <div class="flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">
                    &copy; 2025 Antonio Menelau. Todos os direitos reservados.
                </p>
                <p class="text-gray-400">
                    Desenvolvido com <i class="fas fa-heart text-red-500"></i> e muito <i class="fas fa-coffee text-yellow-800"></i>
                </p>
            </div>
        </div>
    </footer>

    <!-- Botão Voltar ao Topo -->
    <button id="back-to-top" class="fixed bottom-8 right-8 bg-blue-600 text-white p-3 rounded-full shadow-lg hidden">
        <i class="fas fa-arrow-up"></i>
    </button>

    <!-- Scripts -->
    <script>
        // Menu Mobile Toggle
        const menuButton = document.getElementById('menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        
        menuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Navbar Scroll Effect
        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('py-2');
                navbar.classList.remove('py-4');
            } else {
                navbar.classList.add('py-4');
                navbar.classList.remove('py-2');
            }
        });
        
        // Smooth Scroll para Links de Navegação
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Fechar menu mobile se estiver aberto
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });
        
        // Botão Voltar ao Topo
        const backToTopBtn = document.getElementById('back-to-top');
        
        window.addEventListener('scroll', () => {
            if (window.scrollY > 300) {
                backToTopBtn.classList.remove('hidden');
            } else {
                backToTopBtn.classList.add('hidden');
            }
        });
        
        backToTopBtn.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
    </script>
</body>
</html>