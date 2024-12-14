// Cambiar tema claro/oscuro
const toggleButton = document.getElementById('theme-toggle');
toggleButton.addEventListener('click', () => {
    document.body.classList.toggle('dark');
});

// Mostrar mensaje emergente en formulario
const form = document.getElementById('feedback-form');
form.addEventListener('submit', (e) => {
    e.preventDefault();
    alert('¡Gracias por tu mensaje!');
    const name = document.getElementById('nombre').value;
    const message = document.getElementById('mensaje').value;

    // Agregar a la lista dinámica
    const ideasList = document.getElementById('ideas-list');
    const newIdea = document.createElement('li');
    newIdea.textContent = `${name}: ${message}`;
    ideasList.appendChild(newIdea);

    // Limpiar formulario
    form.reset();
});
