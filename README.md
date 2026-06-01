# Homo sapiens caminando — Maqueta 3D

Maqueta 3D interactiva de un *Homo sapiens* caminando, hecha para una presentación de Biología.
Muestra el **bipedalismo** (locomoción erguida sobre dos piernas) en un entorno de **sabana africana**,
el ecosistema asociado a la evolución de la marcha humana.

## Uso

Abre `index.html` en un navegador moderno (requiere conexión a internet para cargar la librería 3D).

- **Arrastrar** → rotar la cámara
- **Rueda** → acercar / alejar
- **Clic derecho** → desplazar
- Botón **▶ Caminar / ⏸ Detenerse** → alterna entre estar parado (Idle) y caminar, con transición suave
- **Velocidad de caminata** → ajusta el ritmo del paso

## Tecnología

- [Three.js](https://threejs.org/) (WebGL) para el render 3D
- Modelo y animaciones de [Mixamo](https://www.mixamo.com/)
- Animación combinada: la malla con piel (Idle) + el ciclo de caminata (Walking)

## Archivos

- `index.html` — la escena principal
- `personaje-skin.fbx` — modelo con malla y textura (animación Idle)
- `personaje-walk.fbx` — animación de caminar
- `homo-sapiens-caminando.html` — versión alternativa con figura geométrica procedimental
