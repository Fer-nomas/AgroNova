# 🌱 **Sitio Web Publicitario - AgroNova**  

*Proyecto académico desarrollado para la materia "Paradigmas de la Programación"*  

---

## 📌 **Descripción**  
Página web publicitaria para **AgroNova** (empresa ficticia de soluciones agronómicas digitales), diseñada para:  
- Promover servicios y productos agrícolas.  
- Generar confianza profesional mediante testimonios y descripciones detalladas.  
- Facilitar el contacto con clientes potenciales.  

**Público objetivo**: Productores agrícolas, cooperativas, empresas agroindustriales y estudiantes de agronomía.  

---

## 🛠 **Tecnologías Utilizadas**  
| Área          | Herramientas                                                                 |  
|---------------|-----------------------------------------------------------------------------|  
| **Frontend**  | Astro.js, Tailwind CSS, React (Context API)                                 |  
| **Diseño**    | Figma (wireframes, paleta de colores)                                       |  
| **Control**   | GitHub (gestión de versiones)                                               |  
| **Hosting**   | GitHub Pages o Netlify (para despliegue)                                    |  

---

## 🌟 **Funcionalidades**  
1. **Páginas clave**:  
   - 🏠 Inicio con hero section y CTA.  
   - 📚 Sección "Sobre Nosotros" + beneficios.  
   - 🚜 Catálogo de productos interactivos (`CardProduct.astro`).  
   - 👨‍🌾 Testimonios en carrusel.  
   - 📞 Formulario de contacto + mapa embebido.  

2. **Elementos dinámicos**:  
   - Animaciones con Tailwind (`animate-fade`).  
   - Carrusel de testimonios (JavaScript inline).  
   - Diseño responsive (móvil y desktop).  

---

## 🚀 **Instalación y Ejecución**   
   Instalar dependencias:
   npm install  

   Ejecutar en desarrollo:
   npm run dev  

   Desplegar:

Configurar astro.config.mjs para el build.

Usar GitHub Pages o Netlify para hosting.

Estructura del Proyecto

/src  
├── assets/           # Imágenes (logo, productos, hero)  
├── components/       # Componentes Astro/React (ej: CardProduct.astro)  
└── pages/            # Páginas principales (maquetadas en el archivo único)  

👥 Contribuidores
    Rol	                             Responsabilidades
Fernando Ávila	      Estructura de la web con Astro + Tailwind.
Federico Díaz	      Diseño UI/UX (Figma), paleta de colores.
Yucileine Mercado	  Redacción de contenidos y documentación.
Mónica Fox	          Selección y edición de recursos visuales.
Iván Díaz	          Control de versiones (GitHub) y componentes.

📄 Licencia

Este proyecto es una simulación académica. AgroNova es una empresa ficticia creada con fines educativos.
© 2024 - Paradigmas de la Programación.
