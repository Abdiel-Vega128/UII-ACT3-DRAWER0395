#PROMPT
Rol de la IA: Actúa como desarrollador Senior de Flutter.
Objetivo: Generar un único archivo main.dart completamente funcional para el restaurante "ITA".

1. Configuración Global y Estilo:

Tema: Crear un MaterialApp con useMaterial3: true.

Colores: Verde (#2E7D32), Blanco (#FCFCFC) y Rojo (#C62828).

Tipografía: Usar fuente tipo Serif (estilo Georgia).

REGLA CRÍTICA: No usar fontWeight en ningún widget de texto. La jerarquía se debe crear mediante fontSize, letterSpacing elevado (de 2 a 10) y el uso de mayúsculas (.toUpperCase()).

2. Navegación por Rutas Nombradas:

Implementar el mapa de routes en MaterialApp para:

'/': Inicio (Home).

'/comida': Sección de platos.

'/bebidas': Sección de bar.

'/favoritos': Sección de destacados.

'/amigos': Sección social.

3. Diseño del Drawer (Menú Lateral):

Encabezado: Un fondo verde sólido (#2E7D32) con un CircleAvatar blanco, el nombre "RESTAURANTE ITA" en mayúsculas, dirección física, teléfono y correo electrónico: "contacto@ita-restaurante.com".

Opciones: 4 elementos ListTile con iconos rojos (#C62828) en estilo outlined. Al tocar, deben usar Navigator.pushReplacementNamed.

4. Estructura de las Páginas:

AppBar: Logo centralizado usando RichText: "I" (verde), "T" (gris), "A" (rojo) con espaciado de letras de 5.

Contenido (Body):

Una imagen circular de 200x200 píxeles centrada (usar Image.network desde GitHub o Pexels).

La imagen debe tener un borde fino y una sombra suave.

Debajo de la imagen: Título de la sección en mayúsculas, tamaño 32, color verde y letterSpacing: 10.

Un divisor rojo de 50px de ancho debajo del título.

Un subtítulo inferior con lema en gris y letterSpacing: 4.

5. Requisito de Código: Todo el código (clases de páginas, widget del drawer y lógica de rutas) debe estar contenido en el mismo bloque de código para ser copiado directamente en main.dart.

<img width="1216" height="707" alt="image" src="https://github.com/user-attachments/assets/b96f14ab-d70a-43c4-a3d9-45a8778210ba" />
<img width="1225" height="718" alt="image" src="https://github.com/user-attachments/assets/209cef24-9e79-40c3-850c-dbd08f5191ca" />
<img width="1218" height="710" alt="image" src="https://github.com/user-attachments/assets/36516648-0cfd-48db-84fa-94bb5a17124d" />
<img width="1209" height="699" alt="image" src="https://github.com/user-attachments/assets/a1909dab-e16d-40fb-83b1-5b129320f249" />
<img width="1211" height="718" alt="image" src="https://github.com/user-attachments/assets/3f0b88d9-9efe-4f8a-ab3b-dfde58b65484" />
#Android
<img width="417" height="691" alt="image" src="https://github.com/user-attachments/assets/95a69bc1-ba0a-4432-9082-fbcb1075aba4" />
<img width="428" height="715" alt="image" src="https://github.com/user-attachments/assets/a0e4ce11-cf37-4a61-8d1c-48c15c6623a0" />
<img width="475" height="734" alt="image" src="https://github.com/user-attachments/assets/ecbad749-7526-4663-a4fc-61ea7db46439" />
<img width="452" height="739" alt="image" src="https://github.com/user-attachments/assets/fcd6484e-fafe-4318-a4e1-682093a5fa31" />
<img width="448" height="716" alt="image" src="https://github.com/user-attachments/assets/9b55447d-0f57-42da-8dd4-7c14548c6ee0" />


