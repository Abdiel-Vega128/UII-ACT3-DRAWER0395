#PROMPT
Este es el "Prompt de Ingeniería" definitivo. Está diseñado con un nivel de detalle técnico tan alto que cualquier IA (como GPT-4, Claude o yo mismo) generará el código exacto, con la estructura de archivos y el diseño visual que hemos perfeccionado, sin margen de error.

🇮🇹 Prompt Maestro de Alta Precisión: App Móvil "ITA Ristorante"
Rol de la IA: Actúa como un Desarrollador Senior de Flutter experto en arquitectura limpia y UI/UX de alta gama.

Objetivo: Generar un proyecto de Flutter estructurado en múltiples archivos que represente la identidad de un restaurante italiano de lujo llamado "ITA".

1. Identidad Visual y Restricciones Estéticas (UI/UX)
Paleta de Colores: * Primario: Verde Italiano (#2E7D32).

Secundario/Acento: Rojo Pomodoro (#C62828).

Fondo: Blanco Hueso (#FCFCFC).

Textos: Negro Carbono (#212121) con opacidades variables.

Tipografía: Usar una fuente tipo Serif (estilo Georgia o de sistema).

REGLA DE ORO: Prohibido el uso de fontWeight. La jerarquía debe establecerse exclusivamente mediante:

Tamaño: Títulos grandes vs. subtítulos pequeños.

Letter Spacing: Espaciado de letras amplio (entre 2.0 y 10.0) para títulos.

Case: Uso de Mayúsculas (UPPERCASE) para elementos de navegación y títulos.

2. Arquitectura de Navegación (Named Routes)
Configurar el MaterialApp en main.dart con un mapa de rutas estricto:

'/': Home/Bienvenida.

'/comida': Sección de platos.

'/bebidas': Sección de bar/coctelería.

'/favoritos': Sección de guardados.

'/amigos': Sección de fidelización/social.

3. Especificaciones del Componente: CustomDrawer
Estructura: Drawer con ancho de 300px y bordes rectos (sin redondeo lateral).

Header (UserAccountsDrawerHeader o Container personalizado):

Fondo: Verde sólido (#2E7D32).

Avatar: CircleAvatar con borde blanco, cargando una imagen de logo desde la red.

Información: Nombre "RESTAURANTE ITA", Dirección física "Calle Italiana 123", Teléfono "+54 9 11 1234-5678" y Email "contacto@ita-restaurante.com".

Cuerpo: Lista de ListTile con iconos outlined. El icono debe ser Rojo (#C62828).

Lógica: Al hacer clic, debe ejecutar Navigator.pop(context) seguido de Navigator.pushNamed(context, ruta).

4. Especificaciones del Componente: PaginaSeccion (Plantilla)
AppBar: Transparente, sin sombra. El título debe ser un RichText con el logo "ITA" (I-Verde, T-Gris, A-Rojo) con letterSpacing: 5.

Imagen Principal: * Tamaño exacto: 200x200.

Forma: Circular (BoxShape.circle).

Efecto: Sombra difusa (BoxShadow) de color negro con 0.05 de opacidad.

Fuente: Cargar desde URL de GitHub o red (Pexels/Unsplash).

Tipografía de Sección:

Título: Debajo de la imagen, en Mayúsculas, tamaño 32-34, letterSpacing: 10.

Divisor: Una línea horizontal roja de 50px de ancho y 1.5px de grosor.

Lema: Un pequeño texto inferior (ej: "SABOR TRADICIONAL") con letterSpacing: 4.

5. Estructura de Archivos Requerida
Divide el código en:

lib/main.dart: Configuración global y rutas.

lib/widgets/custom_drawer.dart: Lógica y diseño del menú lateral.

lib/pages/pagina_seccion.dart: Widget reutilizable para las 4 pantallas
