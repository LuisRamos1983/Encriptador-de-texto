Encriptador de Texto

Descripción:

Este proyecto es un encriptador y desencriptador de texto simple y fácil de usar,
desarrollado con HTML, CSS y JavaScript. Su principal objetivo es permitir a los usuarios encriptar
y desencriptar mensajes de texto para garantizar su privacidad. Este proyecto es ideal para aquellos
que deseen aprender sobre manipulaciones de texto y la creación de interfaces web interactivas.

Características:

* Encriptación de texto: Convierte el texto introducido en un formato encriptado.
* Desencriptación de texto: Permite revertir el texto encriptado a su forma original.
* Interfaz amigable: Diseño simple y moderno que facilita su uso.
* Funcionalidad de copiar: Opción para copiar el texto encriptado/desencriptado al
* portapapeles.
* 
Tecnologías Utilizadas:

* HTML5: Estructura del sitio web.
* CSS3: Estilos y diseño responsivo del sitio.
* JavaScript: Lógica de encriptación y desencriptación.

Instalación:

No se requiere instalación previa. Solo necesitas clonar este repositorio y abrir el
archivo index.html en tu navegador.

Copiar código:
git clone https://github.com/LuisRamos1983/encriptador-de-texto.git
cd encriptador-de-texto

Uso:

1. Encriptar Texto:
> Escribe o pega el texto que deseas encriptar en el campo de entrada.
> Haz clic en el botón "Encriptar".
> El texto encriptado aparecerá en el área designada.
> 
2. Desencriptar Texto:
> Escribe o pega el texto encriptado en el campo de entrada:
> Haz clic en el botón "Desencriptar".
> El texto original aparecerá en el área designada.

3. Copiar Texto:
> Una vez encriptado o desencriptado, puedes copiar el texto haciendo clic en el botón "Copiar".

Ejemplo de Código:

HTML
<textarea class="encriptar" placeholder="Ingrese el texto aquí..."></textarea>
<button class="btn-encriptar">Encriptar</button>
<button class="btn-desencriptar">Desencriptar</button>

CSS
.btn-encriptar {
    width: 328px;
    height: 67px;
    color: #ffffff;
    background: #0a3871;
    border-radius: 24px;
    cursor: pointer;
}

JavaScript
document.querySelector('.btn-encriptar').addEventListener('click', function() {
    let texto = document.querySelector('.encriptar').value;
    let textoEncriptado = encriptarTexto(texto);
    document.querySelector('.resultado').value = textoEncriptado;
});

Personalización:

Este proyecto puede ser personalizado según tus necesidades. Puedes modificar la lógica de 
encriptación en el archivo JavaScript, cambiar los estilos en el CSS o ajustar la 
interfaz en el HTML.

Contribuciones:

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, no dudes en 
hacer un fork del repositorio y enviar un pull request con tus cambios.

Licencia:
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.

Autor
Luis Ramos- Desarrollador y creador del encriptador de texto.
