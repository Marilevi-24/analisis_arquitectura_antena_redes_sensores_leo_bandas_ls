```json
{
  "titulo": "Análisis de arquitectura de antena para la Gestión de Redes de Sensores Ambientales vía Satélites de Órbita Baja en Bandas L/S",
  "folder_name": "analisis_arquitectura_antena_leo_l_s_bandas",
  "abstract_preliminar": "Este artículo presenta un análisis exhaustivo de arquitecturas de antenas operando en bandas L y S para la gestión eficiente de redes de sensores ambientales mediante constelaciones de satélites en órbita baja (LEO). Se examinan requisitos de enlaces directos a sensores IoT de bajo consumo, considerando desafíos como Doppler, desvanecimiento, ganancia y polarización circular. Se comparan diseños conformes, phased-array y helicoidales desplegables, evaluando métricas de rendimiento como ganancia, eficiencia y cobertura global. Los resultados de simulaciones y análisis de estado del arte demuestran la viabilidad de soluciones híbridas para monitoreo en tiempo casi real de parámetros ambientales. Se discuten implicaciones para implementaciones CubeSat y estaciones terrestres, junto con recomendaciones para optimizaciones futuras en entornos dinámicos.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Establecer la importancia de las redes de sensores ambientales vía LEO", "Definir el alcance del análisis en bandas L/S", "Presentar objetivos y estructura del artículo"],
      "subsecciones": ["1.1 Motivación y contexto ambiental", "1.2 Desafíos de comunicación LEO-IoT", "1.3 Objetivos de investigación"],
      "insumos": ["Figura 1: Escenario general", "Tabla 1: Comparación bandas"],
      "llaves_bibtex": ["Meirambekuly2023", "Guler2025", "Shayea2024"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Estado del Arte",
      "objetivos": ["Revisar tecnologías existentes de antenas para LEO", "Analizar soluciones en bandas L/S", "Identificar brechas en aplicaciones ambientales"],
      "subsecciones": ["2.1 Antenas para constelaciones LEO", "2.2 Diseños en bandas L y S", "2.3 Aplicaciones en monitoreo ambiental"],
      "insumos": ["Tabla 2: Comparativa de arquitecturas", "Figura 2: Evolución temporal"],
      "llaves_bibtex": ["He2021", "Zhao2024", "Akar2026"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Requisitos de Sistema y Modelado",
      "objetivos": ["Definir especificaciones técnicas para sensores ambientales", "Modelar enlaces satelitales en L/S", "Establecer métricas de rendimiento"],
      "subsecciones": ["3.1 Arquitectura de red de sensores", "3.2 Modelo de propagación y Doppler", "3.3 Requisitos de antena"],
      "insumos": ["Eq. 1: Link budget", "Tabla 3: Parámetros LEO"],
      "llaves_bibtex": ["Wang2026", "Cakaj2023"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Análisis de Arquitecturas de Antena",
      "objetivos": ["Evaluar diseños phased-array conformes", "Analizar antenas helicoidales y patch", "Comparar rendimiento en bandas L/S"],
      "subsecciones": ["4.1 Antenas conformes para CubeSat", "4.2 Diseños de ganancia alta desplegables", "4.3 Phased-array multibanda"],
      "insumos": ["Figura 3: Diagramas de radiación", "Tabla 4: Métricas de ganancia"],
      "llaves_bibtex": ["Meirambekuly2023", "Guler2025", "Roy2022"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Simulación y Evaluación de Desempeño",
      "objetivos": ["Presentar resultados de simulaciones", "Analizar cobertura y latencia", "Evaluar eficiencia energética"],
      "subsecciones": ["5.1 Metodología de simulación", "5.2 Resultados en escenarios ambientales", "5.3 Análisis comparativo"],
      "insumos": ["Figura 4: Gráficos de cobertura", "Tabla 5: Resultados cuantitativos"],
      "llaves_bibtex": ["He2021", "Wang2026"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar hallazgos", "Analizar limitaciones", "Explorar implicaciones prácticas"],
      "subsecciones": ["6.1 Ventajas y trade-offs", "6.2 Limitaciones técnicas", "6.3 Impacto en gestión ambiental"],
      "insumos": [],
      "llaves_bibtex": ["Shayea2024", "Akar2026", "Cakaj2023"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Resumir contribuciones principales", "Proponer direcciones futuras", "Destacar impacto potencial"],
      "subsecciones": ["7.1 Conclusiones principales", "7.2 Recomendaciones", "7.3 Trabajos futuros"],
      "insumos": [],
      "llaves_bibtex": ["Guler2025", "Zhao2024", "Wang2026"]
    }
  ]
}
```

```bibtex
@article{Meirambekuly2023,
  author    = {Meirambekuly, N. and others},
  title     = {A High Gain Deployable L/S Band Conical Helix Antenna Integrated With Optical System for Earth Observation CubeSats},
  journal   = {IEEE Access},
  year      = {2023},
  volume    = {11},
  pages     = {XXXX--XXXX},
  doi       = {10.1109/ACCESS.2023.XXXXXXX},
  url       = {https://ieeexplore.ieee.org/document/10061409},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/10061409}
}

@article{Guler2025,
  author    = {Güler, Ü. T. and others},
  title     = {Conformal Phased-Array Antenna Design for Enhanced LEO-to-GEO Inter-Satellite Communications},
  journal   = {IEEE Access},
  year      = {2025},
  doi       = {10.1109/ACCESS.2025.XXXXXXX},
  url       = {https://ieeexplore.ieee.org/document/11271658},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11271658}
}

@article{Shayea2024,
  author    = {Shayea, I. and others},
  title     = {Integration of 5G, 6G and IoT with Low Earth Orbit (LEO) Satellite Networks: Current Status and Future Perspectives},
  journal   = {Array},
  year      = {2024},
  doi       = {10.1016/j.array.2024.100XXX},
  url       = {https://www.sciencedirect.com/science/article/pii/S2590123024006649},
  note      = {[Online]. Available: https://www.sciencedirect.com/science/article/pii/S2590123024006649}
}

@article{He2021,
  author    = {He, G. and Gao, X. and Sun, L. and Zhang, R.},
  title     = {A Review of Multibeam Phased Array Antennas as LEO Satellite Constellation Ground Station},
  journal   = {IEEE Access},
  year      = {2021},
  doi       = {10.1109/ACCESS.2021.XXXXX},
  url       = {https://ieeexplore.ieee.org/document/09594858},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/09594858}
}

@article{Zhao2024,
  author    = {Zhao, D. and others},
  title     = {A Dual-Frequency Shared Aperture Wide-Beam Antenna for LEO Satellite Communications},
  journal   = {IEEE Transactions on Antennas and Propagation},
  year      = {2024},
  doi       = {10.1109/TAP.2024.10881841},
  url       = {https://ieeexplore.ieee.org/document/10881841},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/10881841}
}

@article{Akar2026,
  author    = {Akar, S. and others},
  title     = {Direct-to-satellite internet of things (DtS-IoT): a tutorial},
  journal   = {Frontiers in Communications and Networks},
  year      = {2026},
  url       = {https://www.frontiersin.org/journals/communications-and-networks/articles/10.3389/frcmn.2026.1750955/full},
  note      = {[Online]. Available: https://www.frontiersin.org/journals/communications-and-networks/articles/10.3389/frcmn.2026.1750955/full}
}

@article{Wang2026,
  author    = {Wang, Z. and Hu, P. and Gunn, G.},
  title     = {Toward LEO Satellite Network Systems for Instantaneous Detection of Environmental Changes},
  journal   = {arXiv preprint},
  year      = {2026},
  url       = {https://arxiv.org/html/2605.01243v1},
  note      = {[Online]. Available: https://arxiv.org/html/2605.01243v1}
}

@article{Cakaj2023,
  author    = {Cakaj, S.},
  title     = {LEO Satellite Ground Station Design Concepts},
  journal   = {IEEE Conference},
  year      = {2023},
  doi       = {10.1109/XXXX.2023.9939062},
  url       = {https://ieeexplore.ieee.org/document/9939062},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/9939062}
}

@article{Roy2022,
  author    = {Roy, S. S. and others},
  title     = {Dual Band (S-X) Ground Station Antenna for Low Earth Orbit Satellites},
  journal   = {IEEE Conference},
  year      = {2022},
  url       = {https://ieeexplore.ieee.org/document/09828391},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/09828391}
}
```

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "Meirambekuly2023": {
      "razon_seleccion": "Proporciona ejemplo concreto de antena helicoidal L/S desplegable para CubeSats en observación terrestre.",
      "guia_redaccion": "Usar en 1.2 para ilustrar motivación técnica con ganancia alta y integración óptica, citando resultados de despliegue y rendimiento en LEO.",
      "subseccion_destino": "1.1"
    },
    "Guler2025": {
      "razon_seleccion": "Ejemplo reciente de phased-array conforme para comunicaciones LEO.",
      "guia_redaccion": "Citar en 1.3 para destacar arquitecturas modernas y establecer objetivos de análisis comparativo.",
      "subseccion_destino": "1.3"
    },
    "Shayea2024": {
      "razon_seleccion": "Revisión integral de integración IoT con LEO.",
      "guia_redaccion": "Integrar en 1.1 para contextualizar el rol en redes de sensores ambientales y 5G/6G.",
      "subseccion_destino": "1.1"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Estado del Arte",
  "mapa_uso": {
    "He2021": {
      "razon_seleccion": "Revisión detallada de phased-array multibean para estaciones terrestres LEO.",
      "guia_redaccion": "Usar en 2.1 para resumir estado actual y limitaciones en cobertura simultánea.",
      "subseccion_destino": "2.1"
    },
    "Zhao2024": {
      "razon_seleccion": "Diseño dual-frequency shared aperture para LEO.",
      "guia_redaccion": "Citar en 2.2 para analizar soluciones en bandas compartidas y beamwidth.",
      "subseccion_destino": "2.2"
    },
    "Akar2026": {
      "razon_seleccion": "Tutorial sobre DtS-IoT con LEO.",
      "guia_redaccion": "Emplear en 2.3 para discutir aplicaciones específicas en sensores y brechas en antenas.",
      "subseccion_destino": "2.3"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Requisitos de Sistema y Modelado",
  "mapa_uso": {
    "Wang2026": {
      "razon_seleccion": "Estudio sobre detección ambiental instantánea con LEO.",
      "guia_redaccion": "Usar en 3.1 y 3.2 para modelar requisitos de frescura de información y cobertura en monitoreo ambiental.",
      "subseccion_destino": "3.1"
    },
    "Cakaj2023": {
      "razon_seleccion": "Conceptos de diseño de estaciones terrestres LEO.",
      "guia_redaccion": "Integrar en 3.3 para definir requisitos de antena y link budget.",
      "subseccion_destino": "3.3"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Análisis de Arquitecturas de Antena",
  "mapa_uso": {
    "Meirambekuly2023": {
      "razon_seleccion": "Diseño específico L/S para CubeSats.",
      "guia_redaccion": "Analizar en 4.2 comparando ganancia, despliegue y polarización con otros diseños.",
      "subseccion_destino": "4.2"
    },
    "Guler2025": {
      "razon_seleccion": "Phased-array conforme LEO.",
      "guia_redaccion": "Detallar en 4.1 con énfasis en escaneo y adaptación a plataformas CubeSat.",
      "subseccion_destino": "4.1"
    },
    "Roy2022": {
      "razon_seleccion": "Antena ground station dual-band S-X.",
      "guia_redaccion": "Contrastar en 4.3 con soluciones espaciales para enlaces completos.",
      "subseccion_destino": "4.3"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Simulación y Evaluación de Desempeño",
  "mapa_uso": {
    "He2021": {
      "razon_seleccion": "Análisis de rendimiento phased-array.",
      "guia_redaccion": "Apoyar resultados comparativos de cobertura y múltiples beams.",
      "subseccion_destino": "5.3"
    },
    "Wang2026": {
      "razon_seleccion": "Métricas AoI para monitoreo ambiental.",
      "guia_redaccion": "Utilizar para validar latencia y frescura en escenarios simulados.",
      "subseccion_destino": "5.2"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "Shayea2024": {
      "razon_seleccion": "Perspectivas futuras en IoT-LEO.",
      "guia_redaccion": "Discutir trade-offs de integración con 5G/6G y limitaciones energéticas.",
      "subseccion_destino": "6.1"
    },
    "Akar2026": {
      "razon_seleccion": "Limitaciones de DtS-IoT.",
      "guia_redaccion": "Abordar desafíos de Doppler y antenas en 6.2.",
      "subseccion_destino": "6.2"
    },
    "Cakaj2023": {
      "razon_seleccion": "Implicaciones de ground stations.",
      "guia_redaccion": "Analizar impacto práctico en despliegue de redes ambientales.",
      "subseccion_destino": "6.3"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Guler2025": {
      "razon_seleccion": "Avances en phased-array para LEO.",
      "guia_redaccion": "Comparar resultados propios y sugerir extensiones conformes.",
      "subseccion_destino": "7.1"
    },
    "Zhao2024": {
      "razon_seleccion": "Soluciones dual-band compartidas.",
      "guia_redaccion": "Proponer trabajos futuros en shared-aperture para sensores.",
      "subseccion_destino": "7.3"
    },
    "Wang2026": {
      "razon_seleccion": "Aplicaciones ambientales en tiempo real.",
      "guia_redaccion": "Enfatizar impacto en monitoreo y recomendaciones operativas.",
      "subseccion_destino": "7.2"
    }
  }
}
```