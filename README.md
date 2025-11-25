# pagina-de-inglesh
nivel pollito
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English Learning Platform | 20 Módulos de Aprendizaje</title>
    <link rel="stylesheet" href="style.css">
    <link href="fonts.googleapis.com" rel="stylesheet">
</head>
<body>
    <header>
        <div class="container nav-container">
            <div class="logo">EducaEnglish</div>
            <nav>
                <a href="#inicio">Inicio</a>
                <a href="#modulos">Módulos</a>
                <a href="#quiz-section">Examen</a>
            </nav>
        </div>
    </header>

    <main class="container">
        <section id="inicio" class="hero">
            <h1>Welcome! Aprende Inglés de Cero 🚀</h1>
            <p>20 Módulos estructurados desde Nivel Básico (A1) hasta Avanzado (C2).</p>
            <div class="progress-bar">
                <div class="progress-fill" id="progress-fill"></div>
                <div class="progress-text" id="progress-text">Progreso: 0%</div>
            </div>
        </section>

        <section id="modulos">
            <h2>Mapa de Aprendizaje (20 Módulos)</h2>

            <!-- NIVEL BÁSICO (01-07) -->
            <h3>Nivel Básico (A1 - A2)</h3>
            
            <!-- Módulo 01: Alfabeto y Números -->
            <button class="accordion basic" data-module="1">Módulo 01: The Alphabet, Letters & Numbers</button>
            <div class="panel">
                <h4>El Alfabeto (The Alphabet)</h4>
                <p>Aprende la pronunciación de cada letra:</p>
                <p>A (ei), B (bi), C (si), D (di), E (i), F (ef), G (yi), H (eich), I (ai), J (yei), K (kei), L (el), M (em), N (en), O (ou), P (pi), Q (kiu), R (ar), S (es), T (ti), U (iu), V (vi), W (dabal yu), X (ex), Y (guay), Z (zi).</p>
                <h4>Los Números (Numbers 1-10)</h4>
                <p>
                    1: One <button class="listen-btn" data-text="One">🔊</button>, 
                    2: Two <button class="listen-btn" data-text="Two">🔊</button>, 
                    3: Three <button class="listen-btn" data-text="Three">🔊</button>, 
                    4: Four <button class="listen-btn" data-text="Four">🔊</button>, 
                    5: Five <button class="listen-btn" data-text="Five">🔊</button>, 
                    6: Six <button class="listen-btn" data-text="Six">🔊</button>, 
                    7: Seven <button class="listen-btn" data-text="Seven">🔊</button>, 
                    8: Eight <button class="listen-btn" data-text="Eight">🔊</button>, 
                    9: Nine <button class="listen-btn" data-text="Nine">🔊</button>, 
                    10: Ten <button class="listen-btn" data-text="Ten">🔊</button>
                </p>
                 <button class="complete-btn" data-module="1">Marcar Módulo 1 como Completado</button>
            </div>

            <!-- Módulo 02: The Verb "To Be" -->
            <button class="accordion basic" data-module="2">Módulo 02: The Verb "To Be" (Presente Simple)</button>
            <div class="panel">
                <h4>Gramática: Ser o Estar</h4>
                <p>El verbo "To Be" es esencial. Significa *ser* o *estar*.</p>
                <table>
                    <tr><th>Sujeto</th><th>Verbo "To Be"</th><th>Ejemplo</th></tr>
                    <tr><td>I (Yo)</td><td>am</td><td>I am happy. <button class="listen-btn" data-text="I am happy.">🔊</button></td></tr>
                    <tr><td>You (Tú/Ustedes)</td><td>are</td><td>You are a student. <button class="listen-btn" data-text="You are a student.">🔊</button></td></tr>
                    <tr><td>He (Él)</td><td>is</td><td>He is a doctor. <button class="listen-btn" data-text="He is a doctor.">🔊</button></td></tr>
                    <tr><td>She (Ella)</td><td>is</td><td>She is tired. <button class="listen-btn" data-text="She is tired.">🔊</button></td></tr>
                    <tr><td>It (Ello)</td><td>is</td><td>It is cold. <button class="listen-btn" data-text="It is cold.">🔊</button></td></tr>
                    <tr><td>We (Nosotros)</td><td>are</td><td>We are friends. <button class="listen-btn" data-text="We are friends.">🔊</button></td></tr>
                    <tr><td>They (Ellos)</td><td>are</td><td>They are here. <button class="listen-btn" data-text="They are here.">🔊</button></td></tr>
                </table>
                 <button class="complete-btn" data-module="2">Marcar Módulo 2 como Completado</button>
            </div>

            <!-- Módulo 03: Números, Días y Meses -->
            <button class="accordion basic" data-module="3">Módulo 03: Numbers, Days & Months</button>
            <div class="panel">
                <h4>Días de la Semana (Days of the Week)</h4>
                <p>Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday.</p>
                <h4>Meses del Año (Months of the Year)</h4>
                <p>January, February, March, April, May, June, July, August, September, October, November, December.</p>
                <h4>Números 11-20</h4>
                <p>11: Eleven, 12: Twelve, 13: Thirteen, 14: Fourteen, 15: Fifteen, 16: Sixteen, 17: Seventeen, 18: Eighteen, 19: Nineteen, 20: Twenty.</p>
                 <button class="complete-btn" data-module="3">Marcar Módulo 3 como Completado</button>
            </div>

            <!-- Módulo 04: Present Simple -->
            <button class="accordion basic" data-module="4">Módulo 04: Present Simple (I do, you play)</button>
            <div class="panel">
                <h4>Gramática: Presente Simple</h4>
                <p>Se usa para rutinas diarias, hábitos y hechos generales.</p>
                <p><strong>Ejemplos:</strong></p>
                <ul>
                    <li>I <strong>work</strong> every day. (Yo trabajo todos los días)</li>
                    <li>She <strong>plays</strong> the piano. (Ella toca el piano)</li>
                    <li>They <strong>don't like</strong> milk. (A ellos no les gusta la leche)</li>
                </ul>
                 <button class="complete-btn" data-module="4">Marcar Módulo 4 como Completado</button>
            </div>

            <!-- Módulo 05: Adjetivos Posesivos -->
            <button class="accordion basic" data-module="5">Módulo 05: Possessive Adjectives & Pronouns</button>
            <div class="panel">
                <h4>Adjetivos Posesivos</h4>
                <p>Indican a quién pertenece algo.</p>
                <ul>
                    <li>My book (Mi libro)</li>
                    <li>Your car (Tu carro)</li>
                    <li>His dog (Su perro de él)</li>
                    <li>Her house (Su casa de ella)</li>
                </ul>
                 <button class="complete-btn" data-module="5">Marcar Módulo 5 como Completado</button>
            </div>

             <!-- Módulo 06: Preposiciones -->
             <button class="accordion basic" data-module="6">Módulo 06: Prepositions of Place & Time</button>
            <div class="panel">
                <h4>Preposiciones de Lugar</h4>
                <p><strong>In</strong> (dentro), <strong>On</strong> (sobre), <strong>At</strong> (en un punto específico), <strong>Under</strong> (debajo), <strong>Behind</strong> (detrás), <strong>Next to</strong> (al lado de).</p>
                <p>Ejemplo: The cat is <strong>under</strong> the table.</p>
                 <button class="complete-btn" data-module="6">Marcar Módulo 6 como Completado</button>
            </div>
             
             <!-- Módulo 07: Comida -->
             <button class="accordion basic" data-module="7">Módulo 07: Food & Daily Shopping</button>
            <div class="panel">
                <h4>Vocabulario de Comida</h4>
                <p>Apple, bread, milk, cheese, chicken, rice, water, juice.</p>
                <p><strong>Some/Any:</strong> Usamos *some* en oraciones afirmativas y *any* en negativas o preguntas.</p>
                <p>Ejemplo: I have <strong>some</strong> apples. I don't have <strong>any</strong> milk.</p>
                 <button class="complete-btn" data-module="7">Marcar Módulo 7 como Completado</button>
            </div>

            <!-- NIVEL INTERMEDIO (08-14) -->
            <h3>Nivel Intermedio (B1 - B2)</h3>
             
             <!-- Módulo 08: Past Simple -->
             <button class="accordion intermediate" data-module="8">Módulo 08: Past Simple (I did, she went)</button>
            <div class="panel">
                <h4>Gramática: Pasado Simple</h4>
                <p>Se usa para acciones completadas en el pasado. Se forman con verbos regulares (-ed) o irregulares.</p>
                <ul>
                    <li>I <strong>worked</strong> yesterday. (Regular)</li>
                    <li>She <strong>ate</strong> an apple. (Irregular - *eat* -> *ate*)</li>
                    <li>We <strong>didn't go</strong> to the party. (Negativo)</li>
                </ul>
                 <button class="complete-btn" data-module="8">Marcar Módulo 8 como Completado</button>
            </div>
            
            <!-- Módulo 09: Present Continuous -->
            <button class="accordion intermediate" data-module="9">Módulo 09: Present Continuous (I am doing)</button>
            <div class="panel">
                <h4>Gramática: Presente Continuo</h4>
                <p>Se usa para acciones que están ocurriendo *ahora* mismo.</p>
                <p>Fórmula: Sujeto + am/is/are + Verbo(-ing)</p>
                <p>Ejemplo: They <strong>are learning</strong> English right now.</p>
                 <button class="complete-btn" data-module="9">Marcar Módulo 9 como Completado</button>
            </div>
            
            <!-- Módulo 10: Futuro -->
            <button class="accordion intermediate" data-module="10">Módulo 10: Future Tenses (Will, Going To, Present Continuous)</button>
            <div class="panel">
                <h4>Expresar el Futuro</h4>
                <p><strong>Will:</strong> Decisiones espontáneas, predicciones. (It *will* rain tomorrow.)</p>
                <p><strong>Going To:</strong> Planes fijos, intenciones. (I *am going to* visit my grandma.)</p>
                 <button class="complete-btn" data-module="10">Marcar Módulo 10 como Completado</button>
            </div>
            
            <!-- Módulo 11: Modales -->
            <button class="accordion intermediate" data-module="11">Módulo 11: Modals (Can, Must, Should, May)</button>
            <div class="panel">
                <h4>Verbos Modales</h4>
                <p>Expresan habilidad, obligación, permiso o consejo.</p>
                <ul>
                    <li><strong>Can:</strong> Habilidad (I *can* swim).</li>
                    <li><strong>Must:</strong> Obligación (You *must* finish your homework).</li>
                    <li><strong>Should:</strong> Consejo (You *should* study more).</li>
                </ul>
                 <button class="complete-btn" data-module="11">Marcar Módulo 11 como Completado</button>
            </div>
            
            <!-- Módulo 12: Comparativos -->
            <button class="accordion intermediate" data-module="12">Módulo 12: Comparatives & Superlatives</button>
            <div class="panel">
                <h4>Comparar cosas</h4>
                <p>Usamos *er* + *than* o *more* + *than*.</p>
                <p>Ejemplos: This car is <strong>faster than</strong> that one. English is <strong>more interesting than</strong> math.</p>
                 <button class="complete-btn" data-module="12">Marcar Módulo 12 como Completado</button>
            </div>
            
            <!-- Módulo 13: Presente Perfecto -->
            <button class="accordion intermediate" data-module="13">Módulo 13: Present Perfect (I have seen)</button>
            <div class="panel">
                <h4>Gramática: Presente Perfecto</h4>
                <p>Habla de experiencias de vida o acciones pasadas con un resultado presente. Usa *have* o *has* + participio pasado.</p>
                <p>Ejemplo: I <strong>have traveled</strong> to Peru. (He viajado a Perú, es una experiencia de vida).</p>
                 <button class="complete-btn" data-module="13">Marcar Módulo 13 como Completado</button>
            </div>
            
            <!-- Módulo 14: Condicionales -->
            <button class="accordion intermediate" data-module="14">Módulo 14: Conditional Sentences (Type 1 & 2)</button>
            <div class="panel">
                <h4>Condicionales (If...)</h4>
                <p><strong>Type 1 (Real):</strong> If I *study*, I *will pass* the exam.</p>
                <p><strong>Type 2 (Imaginario):</strong> If I *had* a million dollars, I *would buy* a house.</p>
                 <button class="complete-btn" data-module="14">Marcar Módulo 14 como Completado</button>
            </div>

            <!-- NIVEL AVANZADO (15-20) -->
            <h3>Nivel Avanzado (C1 - C2)</h3>
            
            <!-- Módulo 15: Phrasal Verbs -->
            <button class="accordion advanced" data-module="15">Módulo 15: Phrasal Verbs (Get up, put off, take off)</button>
            <div class="panel">
                <h4>Vocabulario Avanzado: Phrasal Verbs</h4>
                <p>Verbos compuestos por un verbo y una preposición/adverbio, cuyo significado cambia.</p>
                <ul>
                    <li><strong>Get up:</strong> Levantarse</li>
                    <li><strong>Put off:</strong> Pospone (Delay)</li>
                    <li><strong>Take off:</strong> Despegar (Avión) / Quitarse (Ropa)</li>
                </ul>
                 <button class="complete-btn" data-module="15">Marcar Módulo 15 como Completado</button>
            </div>
            
            <!-- Módulo 16: Voz Pasiva -->
            <button class="accordion advanced" data-module="16">Módulo 16: The Passive Voice</button>
            <div class="panel">
                <h4>Gramática: La Voz Pasiva</h4>
                <p>Cuando el enfoque recae en el objeto que recibe la acción, no en quien la hace.</p>
                <p>Activa: John *wrote* the book. / Pasiva: The book *was written* by John.</p>
                 <button class="complete-btn" data-module="16">Marcar Módulo 16 como Completado</button>
            </div>
            
            <!-- Módulo 17: Reported Speech -->
            <button class="accordion advanced" data-module="17">Módulo 17: Reported Speech</button>
            <div class="panel">
                <h4>Gramática: Reportar lo dicho</h4>
                <p>Cambiamos el tiempo verbal hacia atrás cuando reportamos lo que alguien dijo en el pasado.</p>
                <p>Directo: She said, "I *am* tired." / Reportado: She said that she *was* tired.</p>
                 <button class="complete-btn" data-module="17">Marcar Módulo 17 como Completado</button>
            </div>
            
            <!-- Módulo 18: Modales Avanzados -->
            <button class="accordion advanced" data-module="18">Módulo 18: Advanced Modals & Perfect Modals</button>
            <div class="panel">
                <h4>Especulación Pasada</h4>
                <p>Usamos *must have*, *could have*, *might have* para especular sobre eventos pasados.</p>
                <p>Ejemplo: He <strong>must have forgotten</strong> his keys. (Seguro se olvidó sus llaves).</p>
                 <button class="complete-btn" data-module="18">Marcar Módulo 18 como Completado</button>
            </div>
            
            <!-- Módulo 19: Conectores Avanzados -->
            <button class="accordion advanced" data-module="19">Módulo 19: Advanced Linking Words & Cohesion</button>
            <div class="panel">
                <h4>Conectores para Discurso Fluido</h4>
                <p>Aprende palabras como *nevertheless* (sin embargo), *furthermore* (además), *consequently* (consecuentemente), *although* (aunque) para un discurso más complejo.</p>
                 <button class="complete-btn" data-module="19">Marcar Módulo 19 como Completado</button>
            </div>
            
            <!-- Módulo 20: Idioms -->
            <button class="accordion advanced" data-module="20">Módulo 20: Idioms, Slang & Cultural English</button>
            <div class="panel">
                <h4>Expresiones Idiomáticas</h4>
                <p>Frases cuyo significado no es literal.</p>
                <ul>
                    <li><strong>Break a leg:</strong> ¡Buena suerte!</li>
                    <li><strong>It's raining cats and dogs:</strong> Llueve a cántaros.</li>
                    <li><strong>Piece of cake:</strong> Muy fácil.</li>
                </ul>
                 <button class="complete-btn" data-module="20">Marcar Módulo 20 como Completado</button>
            </div>

        </section>
        
        <!-- SECCIÓN DEL EXAMEN INTERACTIVO -->
         <section id="quiz-section">
            <h2>Pon a prueba tu conocimiento</h2>
            <div class="quiz-container">
                <div id="quiz"></div>
                <button id="submit">Obtener Resultados</button>
                <div id="results"></div>
            </div>
        </section>

    </main>

    <footer>
        <p>&copy; 2024 EducaEnglish. Knowledge is power.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
style.css
:root {
    --primary-color: #4a90e2; /* Azul brillante */
    --secondary-color: #f5a623; /* Naranja para acentos */
    --text-color: #333;
    --bg-color: #ffffff;
    --footer-bg: #2c3e50;
    --color-basic: #4a90e2; 
    --color-intermediate: #50b34a; 
    --color-advanced: #9b59b6; 
    --accordion-bg: #eaf1f7; 
}

body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f7f9;
    color: var(--text-color);
}

.container {
    width: 90%;
    max-width: 1000px;
    margin: 0 auto;
}

header {
    background-color: var(--footer-bg);
    color: white;
    padding: 15px 0;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-family: 'Chewy', cursive; 
    font-size: 1.8rem;
    color: var(--secondary-color);
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: 500;
}

.hero {
    background-color: var(--primary-color);
    color: white;
    padding: 60px 20px;
    text-align: center;
    margin-top: 20px;
    border-radius: 8px;
}

h1 { font-size: 2.5rem; }
h2 { color: var(--footer-bg); border-bottom: 2px solid var(--primary-color); padding-bottom: 10px; margin-top: 40px; }
h3 { color: var(--primary-color); }

/* Estilos para el botón del acordeón */
button.accordion {
    background-color: var(--primary-color); 
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    text-align: left;
    border: none;
    outline: none;
    transition: 0.4s;
    font-size: 1.1rem;
    margin-bottom: 5px;
    border-radius: 5px;
}

button.accordion.basic { background-color: var(--color-basic); }
button.accordion.intermediate { background-color: var(--color-intermediate); }
button.accordion.advanced { background-color: var(--color-advanced); }

button.accordion:hover, button.accordion.active {
    filter: brightness(110%); 
}

/* Estilo para módulos completados (JavaScript añade la clase 'completed') */
button.accordion.completed {
    background-color: #28a745; /* Verde de éxito */
    text-decoration: line-through; /* Tachamos el texto */
    opacity: 0.8;
}

/* Estilos para el panel de contenido (inicialmente oculto) */
.panel {
    padding: 0 18px;
    background-color: var(--accordion-bg);
    max-height: 0; 
    overflow: hidden;
    transition: max-height 0.2s ease-out; 
    margin-bottom: 15px;
    border-radius: 0 0 5px 5px;
}

table { width: 100%; border-collapse: collapse; margin-bottom: 15px; }
th, td { border: 1px solid #ddd; padding: 8px; text-align: left; }
th { background-color: var(--primary-color); color: white; }

/* Barra de Progreso en la sección Hero */
.progress-bar {
    width: 100%;
    background-color: #e0e0e0;
    border-radius: 5px;
    margin-top: 20px;
    overflow: hidden;
}

.progress-fill {
    height: 20px;
    width: 0%;
    background-color: var(--secondary-color);
    text-align: center;
    line-height: 20px;
    color: white;
    transition: width 0.5s ease-in-out;
}

.progress-text {
    text-align: center;
    margin-top: 5px;
    font-weight: bold;
    color: var(--footer-bg);
}

/* Estilo para el botón de completar */
.complete-btn {
    background-color: #28a745;
    margin-top: 15px;
    font-size: 0.9rem;
    padding: 8px 12px;
}

/* Estilos para el Quiz */
.quiz-container {
    background-color: var(--bg-color);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
    margin-top: 20px;
}
.question { font-weight: bold; margin-bottom: 15px; color: var(--footer-bg); }
.answers label { display: block; margin-bottom: 10px; cursor: pointer; background: #f4f7f9; padding: 10px; border-radius: 5px; transition: background-color 0.3s; }
.answers label:hover { background-color: #e9ecef; }
#submit { background-color: var(--primary-color); margin-top: 20px; padding: 12px 25px; font-size: 1rem; }
#results { margin-top: 20px; padding: 15px; border-radius: 5px; font-weight: bold; display: none; }
.results-correct { background-color: #d4edda; color: #155724; }
.results-incorrect { background-color: #f8d7da; color: #721c24; }
