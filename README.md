# Solar System Explorer

An interactive, 3D web experience that allows users to explore the planets of our solar system, their characteristics, and their primary moons. This project uses advanced CSS 3D transformations and transitions to create a cinematic navigation experience without the need for heavy JavaScript libraries.


## Features

- **Interactive 3D Navigation**: Smoothly transition between planets using CSS 3D transforms (`translateZ`, `rotateX`).
- **Detailed Planet Data**: Each planet includes its distance from the sun (in AU), a brief history, and astronomical facts.
- **Moon Visualization**: View major moons for specific planets (e.g., Deimos and Phoebos for Mars, or the Galilean moons for Jupiter) along with their orbital trajectories.
- **Responsive UI**: A sidebar menu for quick navigation and a "Read More" panel for in-depth information.
- **Pure CSS Interactions**: Planet selection and view changes are handled via radio button hacks and CSS selectors, ensuring high performance.

## Technologies Used

- **HTML5**: Semantic structure for planet data and interactive elements.
- **CSS3**: 
  - **3D Transforms & Perspectives**: To create the depth of space.
  - **Keyframe Animations**: For rotating planet textures and orbital movements.
  - **Flexbox/Absolute Positioning**: For the navigational UI.
- **Google Fonts**: Uses the "Montserrat" typeface for a modern look.
- **Font Awesome**: Used for supplementary iconography.

## File Structure

- `index.html`: The core structure containing planet descriptions and moon data.
- `style.css`: All visual styling, 3D logic, and animations.

## How to Run

1. Clone the repository to your local machine.
2. Open `index.html` in any modern web browser (Chrome, Firefox, or Safari recommended for full 3D support).

## Planets Included

The explorer covers all major planets and Pluto:
* **Mercury**: 0.39 AU
* **Venus**: 0.723 AU
* **Earth**: 1 AU
* **Mars**: 1.524 AU
* **Jupiter**: 5.203 AU
* **Saturn**: 9.539 AU
* **Uranus**: 19.18 AU
* **Neptune**: 30.06 AU
* **Pluto**: 39.5 AU

---
*Data and textures sourced from NASA and various astronomical resources mentioned in the code.*
