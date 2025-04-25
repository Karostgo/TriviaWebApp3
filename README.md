// Dentro del <script>, reemplaza el arreglo `preguntas` con este contenido
const preguntas = [
  {
    pregunta: "¿Cuál es el planeta más cercano al Sol?",
    opciones: ["Venus", "Tierra", "Mercurio", "Marte"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Mercury_in_true_color.jpg/320px-Mercury_in_true_color.jpg"
  },
  {
    pregunta: "¿Cuál es el río más largo del mundo?",
    opciones: ["Amazonas", "Nilo", "Yangtsé", "Misisipi"],
    respuesta: 1,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d6/Nile_River_and_delta_from_orbit.jpg/640px-Nile_River_and_delta_from_orbit.jpg"
  },
  {
    pregunta: "¿Quién escribió 'Don Quijote de la Mancha'?",
    opciones: ["Miguel de Cervantes", "Pablo Neruda", "Gabriel García Márquez", "Lope de Vega"],
    respuesta: 0,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Cervantes_Jauregui.jpg/330px-Cervantes_Jauregui.jpg"
  },
  {
    pregunta: "¿Cuál es el elemento químico con símbolo 'O'?",
    opciones: ["Osmio", "Oro", "Oxígeno", "Ozono"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Oxygen_discharge_tube.jpg/320px-Oxygen_discharge_tube.jpg"
  },
  {
    pregunta: "¿Qué país tiene forma de bota?",
    opciones: ["España", "Grecia", "Italia", "México"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Italy_satellite_planetobserver.jpg/480px-Italy_satellite_planetobserver.jpg"
  },
  {
    pregunta: "¿Cuál es la capital de Japón?",
    opciones: ["Osaka", "Kioto", "Tokio", "Hiroshima"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/f/f2/Tokyo_Tower_and_surrounding_area.jpg/640px-Tokyo_Tower_and_surrounding_area.jpg"
  },
  {
    pregunta: "¿Cuál es el océano más grande del mundo?",
    opciones: ["Atlántico", "Índico", "Ártico", "Pacífico"],
    respuesta: 3,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Pacific_Ocean_map.png/640px-Pacific_Ocean_map.png"
  },
  {
    pregunta: "¿Qué instrumento mide la temperatura?",
    opciones: ["Barómetro", "Termómetro", "Altímetro", "Anemómetro"],
    respuesta: 1,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/6/64/Medical_thermometer_3.jpg/320px-Medical_thermometer_3.jpg"
  },
  {
    pregunta: "¿Qué animal es conocido como el rey de la selva?",
    opciones: ["Elefante", "León", "Tigre", "Gorila"],
    respuesta: 1,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Lion_waiting_in_Namibia.jpg/480px-Lion_waiting_in_Namibia.jpg"
  },
  {
    pregunta: "¿Cuál es el idioma más hablado del mundo?",
    opciones: ["Inglés", "Hindi", "Mandarín", "Español"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Languages_of_the_world_by_number_of_native_speakers.png/640px-Languages_of_the_world_by_number_of_native_speakers.png"
  },
  {
    pregunta: "¿Qué gas respiramos que es esencial para vivir?",
    opciones: ["Hidrógeno", "Dióxido de carbono", "Oxígeno", "Nitrógeno"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/Breathing_oxygen.jpg/320px-Breathing_oxygen.jpg"
  },
  {
    pregunta: "¿Quién pintó la Mona Lisa?",
    opciones: ["Vincent van Gogh", "Pablo Picasso", "Leonardo da Vinci", "Claude Monet"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Mona_Lisa%2C_by_Leonardo_da_Vinci%2C_from_C2RMF_retouched.jpg/480px-Mona_Lisa%2C_by_Leonardo_da_Vinci%2C_from_C2RMF_retouched.jpg"
  },
  {
    pregunta: "¿Cuál es el resultado de 8 × 7?",
    opciones: ["54", "56", "64", "49"],
    respuesta: 1,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/Matem%C3%A1ticas_-_multiplicaci%C3%B3n.jpg/640px-Matem%C3%A1ticas_-_multiplicaci%C3%B3n.jpg"
  },
  {
    pregunta: "¿Qué continente tiene más países?",
    opciones: ["Europa", "Asia", "África", "América"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/Political_Africa.svg/640px-Political_Africa.svg.png"
  },
  {
    pregunta: "¿Qué tipo de animal es una ballena?",
    opciones: ["Pez", "Reptil", "Mamífero", "Anfibio"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Blue_Whale_with_open_mouth.jpg/640px-Blue_Whale_with_open_mouth.jpg"
  },
  {
    pregunta: "¿En qué país se encuentra la Torre Eiffel?",
    opciones: ["Italia", "España", "Francia", "Alemania"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Tour_Eiffel_Wikimedia_Commons.jpg/640px-Tour_Eiffel_Wikimedia_Commons.jpg"
  },
  {
    pregunta: "¿Cuál es el órgano principal del sistema circulatorio?",
    opciones: ["Cerebro", "Pulmones", "Hígado", "Corazón"],
    respuesta: 3,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/Diagram_of_the_human_heart_%28cropped%29.svg/512px-Diagram_of_the_human_heart_%28cropped%29.svg.png"
  },
  {
    pregunta: "¿Cuál es la fórmula química del agua?",
    opciones: ["CO2", "O2", "H2O", "NaCl"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/Water_molecule_3D.svg/512px-Water_molecule_3D.svg.png"
  },
  {
    pregunta: "¿Quién fue el primer hombre en pisar la Luna?",
    opciones: ["Yuri Gagarin", "Neil Armstrong", "Buzz Aldrin", "Michael Collins"],
    respuesta: 1,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Aldrin_Apollo_11.jpg/480px-Aldrin_Apollo_11.jpg"
  },
  {
    pregunta: "¿Qué país tiene la mayor población del mundo?",
    opciones: ["Estados Unidos", "India", "China", "Indonesia"],
    respuesta: 2,
    imagen: "https://upload.wikimedia.org/wikipedia/commons/thumb/3/3b/Map_of_the_People%27s_Republic_of_China_%28en%29.png/640px-Map_of_the_People%27s_Republic_of_China_%28en%29.png"
  }
];
