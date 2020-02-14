% PlayZone
% Alejandro Cruz Vidal
% Curso 2019/20

# Descripción general del proyecto

El obejtivo de PlayZone será reunir a personas que tengan en común un mismo juego, brindándoles un lugar donde poder conocer a otras personas que jueguen al mismo juego. Dando la opción a los usuarios de que añadan los videojuegos a los que juegan desde una lista. La idea es que los jugadores se dividan por zonas geográficas para asegurar de que podréis jugar al mismo juego de forma totalmente óptima. También se podrán encontrar noticias sobre lanzamientos recientes de juegos.

## Funcionalidad principal de la aplicación

Permitir a los usuarios encontrar a otros usuarios de su entorno con los que puedan entablar una conversación a través de un muro, conocer sus ID de los juegos para poder añadirlos como amigos en estos y jugar juntos.
Los jugadores también podrán revisar las estadísticas de sus juegos.
Los administradores podrán postear noticias y controlar todos los mensajes de los posibles muros que haya.

## Objetivos generales

* Objetivo: "Visualizar las estadísticas de los videojuegos que juegan e interactuar con otros usuarios."

* Casos de uso:
    . Invitados: "Registrarse", "Ver noticias, "Buscar perfiles de usuarios".
    
    . Usuarios: "Iniciar sesión", "Cerrar sesión", "Eliminar usuario", "Añadir un juego", "Escribir en el muro", "Buscar otros usuarios", "Comentar una noticia", "Borrar comentario de una noticia", "Valorar una noticia", "Ver usuarios de un juego".

    . Administradores: "Iniciar sesión", "Cerrar sesión", "Eliminar usuario", "Crear noticias", "Modificar noticias", "Borrar noticias", "Borrar comentarios", "Borrar mensajes", "Ver usuarios registrados", "Eliminar usuarios", "Añadir juegos", "Eliminar juegos".

# Elemento de innovación

Integración de una API externa de un juego en la que se reciba información para procesarla dentro de la aplicación para mostar a los usuarios sus estadísticas sobre este. La principal idea es usar la API de desarrollo de Riot Games.
