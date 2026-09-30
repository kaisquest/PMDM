# Plantilla: propuesta del Proyecto A

---

## 0 · Datos

| | |
|---|---|
| **Nombre de la app** | Gestion de Colecciones |
| **Autor/a** | Iván Fernánez López |
| **Fecha** | 20-09-2026 |

---

## 1 · La idea en una frase

> Qué hace tu app y para quién, en una sola frase.

> La app permite a usuarios con colecciones de videojuegos divididas en diferentes formatos y plataformas aunarlas para registrarlas y llevar un backlog.


---

## 2 · El problema

> ¿Qué problema resuelve? ¿Cómo se resuelve hoy sin tu app?

> Permite a cualquier usuario tener un control absoluto sobre qué juegos tiene, en qué formatos lo tiene y en qué plataformas lo tiene.

>A día de hoy no existe una forma de hacerlo todo en un mismo sitio: no puedes contabilizar en ningún lado si tienes 3 copias digitales de un mismo juego en diferentes stores ni de si tienes varias versiones físicas, etc.
---

## 3 · Personas usuarias

> ¿Quién la va a usar? Describe a una persona concreta: edad, soltura con la
> tecnología, cuándo y dónde abre la app, cuánto tiempo le dedica y qué pasa
> si le falla.

>  El usuario medio será un varón de unos 35 años, con mucha soltura con la tecnología que abrirá la app tras adquirir un juego en una tienda o cuando decida de vez en cuando actualizar su catálogo, dedicándole de unos minutos en situaciones cortas a algunas horas si hablamos de actualizar el backlog, y que si la app falla seguramente deje sin actualizar ese juego o decida buscarse alguna otra app.

---

## 4 · Funcionalidades

### Imprescindibles (sin esto la app no tiene sentido)

| # | Funcionalidad |
|---|---------------|
| F1 | Registrar títulos videojuegos por plataforma y formato |
| F2 | Registrar y subir fotos de los títulos |
| F3 | Crear listas y categorías: por plataforma, juegos buscados, etc. |
| F4 | Postear comentarios en los perfiles de usuarios que sigues |
| F5 | Seguir a otros usuarios |

### Opcionales (si sobra tiempo)

| # | Funcionalidad |
|---|---------------|
| O1 | Conexión con APIs de otras plataformas para sincronizar datos |
| O2 | Canal automatizado sobre noticias |


---

## 5 · Pantallas

| Pantalla | Para qué sirve | Se llega desde |
|----------|----------------|----------------|
| Inicio (Lista) | Muestra las novedades en portales de videojuegos, últimos añadidos por tus amigos y juegos en tendencia | (arranque) |
| Colección (Listas) | Muestra todos los juegos que tiene un usario agredados | Inicio, Menu, Burger |
| Añadir Ítem (Formulario) | Permite añadir un juego a la colección personal, ya sea buscando en la base de datos o añadiendo una nueva entrada a mano | Inicio, Menu, Burger, Floating Button |
| Ajustes de usuario (Ajustes) | Permite modificar los datos personales de un usuario | Inicio, Menu, Burger, IconoPerfil |
| Información de un título (Detalle) | Permite ver todos los datos en detalle de un juego que esté en una colección o en a base de datos | Colección, Inicio | 
| Información de un perfil (Detalle) | Permite datos de un perfil que sea público como sus juegos añadidos o sus capturas subidas | Búsqueda, Inicio | 

---

## 6 · Bocetos

> Dibuja las pantallas principales. A mano y fotografiado es válido.
> Pega aquí las imágenes o indica el nombre de los archivos adjuntos.

---

## 7 · Qué datos guarda la app

| Tipo de dato | Campos | Ejemplo |
|--------------|--------|---------|
| Videojuego | Título, desarrolladora, publisher, fecha de publicacón por región, plataforma, formato, OpenCritic | Ratchet & Clank, Insomniac Games, Sony Computer Entertainment, NA: 04-11-2002 / AU: 06-11-2002 / EU: 08-11-2002, PlayStation 2, físico, 88/100  |
| Desarrolladora | Nombre, año de fundación, año de cierre, localización, propietario, principales sagas y títulos | Insomniac Games, 28-02-1994, en activo, Burbank, California, US, Sony Interactive Entertainment, Spyro The Dragon / Ratchet & Clank / Resistance / Sunset Overdrive / Spiderman |
| Publisher | Nombre, año de fundación, año de cierre, localización, productos| Sony Interactive Entertainment, 16-11-1993, en activo, Tokio (Fundación) / San Mateo, California, US (Sede central), PlayStation / PlayStation VR / PlayStation Portable / PlayStation Vita|



---

## 8 · Riesgos

| Lo que me preocupa | Plan B |
|--------------------|--------|
| Que no haya ninguna foto disponile para subir al perfil  | Tener dentro del tema de la app algunos fondos de perfil predefinidos |
| No tener acceso  | |

---

## Antes de entregar

- [ ] La idea cabe en una frase.
- [ ] El público es una persona concreta, no «todo el mundo».
- [ ] Hay **3 o 4** funcionalidades imprescindibles, no diez.
- [ ] Cada funcionalidad imprescindible tiene su pantalla.
- [ ] Hay bocetos de las pantallas principales.
- [ ] **Las cuatro casillas del apartado 8 están rellenas.**
- [ ] Está identificado al menos un riesgo con su plan B.
