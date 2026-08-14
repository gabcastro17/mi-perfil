## Mi perfil
Página web personal construida con Laravel y PHP, donde presento mi información personal, mis habilidades, mis intereses y mis metas.
## Descripcion
Este proyecto es un sitio web de perfil personal dividido en distintas secciones, cada una manejada con vistas Blade independientes:
-Perfil — información personal y datos de contacto.<br>
-Habilidades — competencias técnicas y personales.<br>
-Intereses — repostería, astronomía, animales, libros y música.<br>
-Metas — objetivos personales y profesionales a futuro.<br>
## Estructura
mi-perfil/ <br>
├── public/<br>
├── resources/<br>
│   ├── css/<br>
│   ├── js/<br>
│   └── views/<br>
│       ├── perfil.blade.php<br>
│       ├── habilidades.blade.php<br>
│       ├── intereses.blade.php<br>
│       └── metas.blade.php<br>
├── routes/v
│   └── web.php<br>
└── README.md<br>
## Tecnologias usadas
Laravel, PHP, Blade, HTML5, CSS3, Composer.
## Instalación
1.Clona el repositorio:
   git clone https://github.com/gabcastro17/mi-perfil.git
   cd mi-perfil
   
2.Instala las dependencias con Composer:
   composer install
   
3.Copia el archivo de entorno y genera la clave de la aplicación:
   cp .env.example .env
   php artisan key:generate
   
4.Levanta el servidor de desarrollo:
   php artisan serve
   
5.Abre tu navegador en http://localhost:8000
## Autor
**Gabriela Alejandra Castro Suarez**<br>
#13-Agosto-2026
