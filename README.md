# pagina-de-inglesh
nivel pollito
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
