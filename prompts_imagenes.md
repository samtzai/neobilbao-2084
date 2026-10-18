# NEOBILBAO 2084 // GUÍA DE PROMPTS PARA GOOGLE FLOW
### Dossier de Generación de Arte Visual para «La Lotería Azul»

Este archivo contiene los prompts técnicos optimizados para generar mediante **Google Flow** (o Imagen 3 / Midjourney) las 13 ilustraciones integradas en el libro y la portada de *NeoBilbao 2084: La Lotería Azul*.

---

## 🎨 Parámetros Generales de Estilo Visual

Para mantener la coherencia estética en todas las generaciones, se recomienda aplicar las siguientes directrices estilísticas:
* **Género y Tono:** Ciberpunk Noir de principios de los años 90 (*Ghost in the Shell 1995*, *Blade Runner*, *Akira*, *The City of Lost Children*). No es ciberpunk limpio ni inalámbrico; es denso, húmedo, industrial, sucio y claustrofóbico.
* **Paleta Cromática:** Negros asfalto profundo (`#1A1F26`), azul eléctrico/cian de la Lotería (`#0A84FF`), verde fósforo CRT (`#10B981`), óxido ferroso (`#B84A1E`) y destellos ámbar sobre charcos reflectantes.
* **Elementos Recurrentes:** Lluvia ácida persistente (*sirimiri*), paraguas de plástico de polímero transparente, gabardinas mojadas, monitores de tubo de rayos catódicos (CRT) parpadeantes, disquetes, cables coaxiales gruesos colgados entre fachadas y arquitectura brutalista modular de hormigón.
* **Cámara y Lente:** Cinematografía de 35mm, grano analógico sutil, lentes anamórficas Panavision, profundidad de campo cinematográfica, iluminación volumétrica de neón difusa por la niebla tóxica.

---

## 📋 Catálogo Completo de Ilustraciones y Nombres de Fichero

| # | Nombre exacto de fichero a guardar en `images/` | Capítulo / Ubicación en el libro |
|---|---|---|
| **00** | `00_portada_neobilbao_2084.jpg` | Portada institucional del manual |
| **01** | `01_distrito7_la_margen.jpg` | Capítulo 1: Introducción para los jugadores |
| **02** | `02_ane_garate_reaparicion.jpg` | Capítulo 1: El reencuentro en la tasca |
| **03** | `03_proyecto_izar_laboratorio.jpg` | Capítulo 2: El Secreto del Director |
| **04** | `04_los_secretas_auditores.jpg` | Capítulo 4: Facciones (Los Auditores) |
| **05** | `05_limpieza_sanitaria_furgoneta.jpg` | Capítulo 4: Facciones (Limpieza Sanitaria) |
| **06** | `06_descartados_antigua_ria.jpg` | Capítulo 4 / Fase 2: Los Descartados |
| **07** | `07_tecnologia_crt_terminales.jpg` | Capítulo 5: Tecnología y Wetware 2084 |
| **08** | `08_arquetipos_la_margen.jpg` | Capítulo 7: Arquetipos de la Cuadrilla |
| **09** | `09_descenso_subsuelo_alcantarillas.jpg` | Capítulo 9: Campaña Fase 2 (El Descenso) |
| **10** | `10_infiltracion_cupula_blanca.jpg` | Capítulo 9: Campaña Fase 3 (La Infiltración) |
| **11** | `11_evento_resonancia_azul.jpg` | Capítulo 9: Campaña Fase 4 (El Clímax) |
| **12** | `12_epilogo_semilla_2102.jpg` | Capítulo 10: Epílogo (La semilla de 2102) |

---

## 🖼️ Prompts Detallados por Ilustración

---

### 00. Portada Oficial
* **Nombre de fichero:** `00_portada_neobilbao_2084.jpg`
* **Ubicación:** `chapters/00_portada.tex` (cubierta completa)
* **Descripción de la escena:** Vista panorámica vertical de «La Margen» (Distrito 7) de NeoBilbao en 2084. Rascacielos modulares colmena de hormigón desgastado con cables colgantes y tuberías exteriores. Un tren magnético elevado (mag-lev) cruza entre los edificios. Lluvia ácida cayendo y reflejando luces de neón en el asfalto. Una colosal pantalla publicitaria CRT muestra el rostro de una familia feliz bajo el lema corporativo «Orekak-Corp: El Talento Tiene su Recompensa». En la lejanía superior, a través de la polución y la niebla, brilla la inalcanzable Cúpula Dorada de titanio. En primer plano, siluetas de espaldas de obreros con paraguas de polímero transparente.
* **Prompt para Google Flow / Generador:**
```text
Cinematic wide establishing shot of Neo-Bilbao cyberpunk city in 1990s retrofuturistic aesthetic. District 7, wet asphalt street bathed in toxic acid drizzle and neon reflections. Modular brutalist concrete skyscraper blocks tangled with thick hanging coaxial cables. An overhead mag-lev train glides silently on elevated tracks between smoggy towers. A gigantic flickering cathode-ray tube (CRT) billboard glows in electric blue and amber, displaying corporate propaganda text and a smiling family. In the far upper background, piercing the dense chemical smog, the majestic curved titanium architecture of the Golden Dome glows. Silhouetted pedestrians in long wet raincoats holding transparent polymer umbrellas. Moody dark ambient lighting, 35mm film grain, Panavision anamorphic lens flare, Blade Runner and Ghost in the Shell 1995 style --ar 16:9 --v 6.0
```

---

### 01. Distrito 7: La Margen
* **Nombre de fichero:** `01_distrito7_la_margen.jpg`
* **Ubicación:** `chapters/01_introduccion.tex` (sección 1)
* **Descripción de la escena:** Una calle estrecha y bulliciosa del Distrito 7 bajo el sirimiri ácido. Tascas populares con letreros de neón parpadeantes («Zulo», «Txatar»), humo saliendo de rejillas de ventilación a ras de suelo. Ciudadanos de clase trabajadora caminando con respiradores baratos de cartucho y abrigos de vinilo. Charcos con tornasol de aceite y óxido.
* **Prompt para Google Flow / Generador:**
```text
Street level eye-level view of a cramped urban alley in cyberpunk District 7. Continuous toxic acid sirimiri rain falling. Workers wearing cheap vinyl raincoats and industrial mouth respirators walking past dark taverns with glowing cyan and amber neon signs. Steam and ozone gas rising from street sewer grates. Puddles of oily iridescent water on wet cracked asphalt. Tangled overhead electrical cables, industrial retro-cyberpunk atmosphere, 1990s anime realism, highly detailed, moody atmospheric lighting --ar 16:9 --v 6.0
```

---

### 02. El Regreso de Ane Garate
* **Nombre de fichero:** `02_ane_garate_reaparicion.jpg`
* **Ubicación:** `chapters/01_introduccion.tex` (sección 2)
* **Descripción de la escena:** Primer plano medio en la penumbra de una tasca clandestina. Ane Garate, una mujer joven de unos 28 años, pálida y empapada, con mirada ausente y vacía en estado de shock. Tiene la nuca rapada donde se aprecia un tosco puerto cibernético hexagonal de titanio atornillado con cuatro pernos quirúrgicos. De las conexiones supuran gotas de suero y asoman filamentos de fibra óptica que emiten una débil pulsación azul. Sostiene con dedos temblorosos un vaso de plástico con kalimotxo.
* **Prompt para Google Flow / Generador:**
```text
Cinematic medium close-up of a traumatized young female telecom engineer sitting in the dimly lit backroom of a gritty dive bar. She is pale, soaking wet with rain, staring blankly with hollow haunted eyes. Her head is partially shaved at the back of the neck, revealing a crude, brutalist titanium hexagonal neural port socket bolted directly into her occipital skull with surgical screws. The implant has visible copper pins and emits a faint pulsating eerie electric blue light from quartz fiber conduits. Her hands tremble holding a cheap plastic cup. Shallow depth of field, dramatic chiaroscuro noir lighting, 35mm film texture, emotional cyberpunk tragedy --ar 16:9 --v 6.0
```

---

### 03. El Búnker del Proyecto IZAR
* **Nombre de fichero:** `03_proyecto_izar_laboratorio.jpg`
* **Ubicación:** `chapters/02_secreto_director.tex`
* **Descripción de la escena:** El laboratorio secreto subterráneo de Orekak-Corp. Una fila de grandes cilindros de cristal reforzado llenos de líquido amniótico azul eléctrico viscoso. En su interior flotan cuerpos humanos adultos en suspensión, con cables umbilicales gruesos conectados a sus cabezas. Terminales CRT de fósforo verde muestran trazados electroencefalográficos con picos erráticos de convulsión. Científicos con batas blindadas y mascarillas monitoreando el mainframe.
* **Prompt para Google Flow / Generador:**
```text
Industrial underground secret laboratory búnker. A row of massive vertical cylindrical glass stasis tanks filled with glowing bioluminescent electric blue amniotic fluid. Inside the tanks, human adult subjects float suspended, unconscious, with thick umbilical optic cables plugged into the base of their shaved skulls. Massive server racks with blinking green phosphor CRT terminal displays showing erratic brainwave spikes. Scientists in protective hazmat lab coats and heavy respirators monitoring data consoles. Cold sterile dystopian sci-fi aesthetic, oppressive claustrophobic atmosphere, cinematic composition --ar 16:9 --v 6.0
```

---

### 04. Los Auditores («Los Secretas»)
* **Nombre de fichero:** `04_los_secretas_auditores.jpg`
* **Ubicación:** `chapters/04_facciones_amenazas.tex`
* **Descripción de la escena:** Dos agentes encubiertos de la policía política corporativa (Los Auditores) esperando en el andén de hormigón de la estación del mag-lev. Visten gabardinas oscuras mojadas por la lluvia, sombreros discretos y gafas de sol de montura gruesa estilo 90s con filtros polarizados. Uno de ellos disimula en la manga un inyector neumático de metal con aguja hipodérmica presurizada. Mirada fría y amenazante. Al fondo, la multitud borrosa de obreros.
* **Prompt para Google Flow / Generador:**
```text
Two sinister plainclothes corporate undercover agents (The Auditors) standing on a crowded concrete mag-lev train station platform in the rain. They wear heavy dark wet trench coats and thick-rimmed 1990s dark sunglasses. One agent subtly conceals a cold chrome pneumatic needle injector in his sleeve. Stoic, predatory expressions. Atmospheric haze, harsh fluorescent platform lighting, motion blur of passing commuter crowd, retro-cyberpunk espionage noir, cinematic lighting, photorealistic --ar 16:9 --v 6.0
```

---

### 05. Furgoneta de Limpieza Sanitaria
* **Nombre de fichero:** `05_limpieza_sanitaria_furgoneta.jpg`
* **Ubicación:** `chapters/04_facciones_amenazas.tex`
* **Descripción de la escena:** Un callejón estrecho y oscuro de La Margen cortado por una furgoneta blanca blindada sin distintivos ni matrícula. Las puertas traseras están abiertas, proyectando una luz halógena blanca y vapor criogénico sobre el asfalto mojado. Dos paramédicos con trajes herméticos de presión positiva y visores opacos cargan una camilla con una bolsa de contención biológica.
* **Prompt para Google Flow / Generador:**
```text
An ominous unmarked white corporate ambulance van parked in a dark rainy cyberpunk alleyway at midnight. Back doors swung open, spilling harsh cold white halogen light and wisps of cryogenic vapor onto the glistening wet pavement. Two operatives in sterile white biohazard hazmat suits with mirrored opaque helmet visors loading a heavy black rubber body bag onto a stretcher. Rain pouring down, deep shadows, gritty noir thriller composition, cinematic --ar 16:9 --v 6.0
```

---

### 06. Los Descartados de la Vieja Ría
* **Nombre de fichero:** `06_descartados_antigua_ria.jpg`
* **Ubicación:** `chapters/04_facciones_amenazas.tex`
* **Descripción de la escena:** Los cimientos subterráneos bajo los viejos muelles industriales de la Ría de Bilbao. Techos abovedados de ladrillo y vigas de hierro carcomidas por el óxido. Una comunidad de Descartados (antiguos sujetos de prueba) apiñados alrededor de un bidón oxidado que arde con fuego anaranjado. Tienen cicatrices quirúrgicas en la cabeza, cables colgantes y vendas sucias. Miradas perdidas y gestos catatónicos. Reflejos de fuego en aguas estancadas.
* **Prompt para Google Flow / Generador:**
```text
Underground ruins beneath ancient industrial river docks. Soaring brick vaulted ceilings and corroded rusted iron beams dripping with condensation. A tragic commune of cybernetic outcasts (The Discarded) huddled around an oil drum burning with warm orange flames. The people have visible crude metal implants, dangling ribbon cables from their temples, and ragged clothes. Ghostly, melancholic expressions. Reflections of firelight on stagnant dark water pools. Evocative, painterly cinematic lighting, post-industrial dystopian underground --ar 16:9 --v 6.0
```

---

### 07. Tecnología y Wetware 2084
* **Nombre de fichero:** `07_tecnologia_crt_terminales.jpg`
* **Ubicación:** `chapters/05_tecnologia_wetware.tex`
* **Descripción de la escena:** Plano detalle de una mesa de trabajo en el taller clandestino de la Biohacker. Monitores CRT voluminosos con pantallas curvas que emiten un resplandor de fósforo verde y código ASCII hexadecimal. Montones de disquetes magnéticos de 3.5 pulgadas con etiquetas escritas a mano, cables coaxiales pelados con pinzas de cocodrilo, un soldador eléctrico echando una pequeña columna de humo, una taza de café sintético frío y herramientas quirúrgicas oxidadas.
* **Prompt para Google Flow / Generador:**
```text
Detailed close-up still life of a clandestine retro-cyberpunk hacker workbench. Bulky curved-glass CRT monitors glowing with bright green and amber phosphor terminal text and hexadecimal data. Stacks of 3.5-inch floppy diskettes with handwritten masking tape labels. Stripped coaxial cables with copper wire exposed and alligator clips. A smoking hot soldering iron on an iron stand, wire cutters, screwdrivers, and an open hardware chassis. Atmospheric dust motes in neon light, tactile 1990s analog tech aesthetic, hyper-detailed --ar 16:9 --v 6.0
```

---

### 08. Cuadrilla de La Margen (Arquetipos)
* **Nombre de fichero:** `08_arquetipos_la_margen.jpg`
* **Ubicación:** `chapters/07_arquetipos.tex`
* **Descripción de la escena:** El grupo de los cinco protagonistas de espaldas y perfil en un callejón iluminado por un letrero de neón azul. El Sabueso con gabardina larga y cigarrillo en la comisura; la Biohacker con cazadora de cuero customizada, terminal portátil a la espalda y gafas de soldador; el Celador con bata médica bajo el impermeable y maletín de urgencias; el Burócrata con corbata torcida y paraguas; y el Familiar con mirada desafiante y una llave inglesa en la mano.
* **Prompt para Google Flow / Generador:**
```text
Ensemble group shot of five diverse working-class protagonists standing together in a rain-soaked cyberpunk alley under a glowing blue neon sign. A gritty private detective in a worn trenchcoat smoking a cigarette; a rebellious female punk hacker with welding goggles on her forehead and a bulky portable CRT unit slung over her back; an exhausted hospital orderly in a damp medical coat carrying an emergency trauma kit; a stressed bureaucrat with an unbuttoned collar holding an umbrella; and an angry family member clutching an iron pipe wrench. Dynamic team composition, dramatic rim lighting, 1990s anime live-action adaptation style --ar 16:9 --v 6.0
```

---

### 09. Descenso al Subsuelo
* **Nombre de fichero:** `09_descenso_subsuelo_alcantarillas.jpg`
* **Ubicación:** `chapters/09_campana_4_fases.tex` (Fase 2)
* **Descripción de la escena:** Los personajes descendiendo por una escalera de gato metálica resbaladiza hacia un inmenso túnel colector pluvial circular de hormigón. Agua residual ácida fluyendo por la base del canal. Iluminan las tinieblas con linternas de petaca de luz amarilla que cortan la niebla sulfurosa. Tuberías industriales y compuertas hidráulicas oxidadas.
* **Prompt para Google Flow / Generador:**
```text
Explorers descending an iron rung ladder into a cavernous, circular concrete stormwater sewer tunnel deep beneath the industrial city. Thick chemical runoff water rushing along the bottom. Yellow beams from hand-held battery lanterns cutting through sulfurous green-tinted steam and fog. Huge rusted pipes and heavy pressure valves lining the curved walls. Claustrophobic, gritty, atmospheric dark subterranean exploration, cinematic perspective --ar 16:9 --v 6.0
```

---

### 10. Infiltración en la Cúpula Superior
* **Nombre de fichero:** `10_infiltracion_cupula_blanca.jpg`
* **Ubicación:** `chapters/09_campana_4_fases.tex` (Fase 3)
* **Descripción de la escena:** Pasillo monumental e inmaculado en el interior de la Torre Orekak en la Cúpula Dorada. Suelos de mármol sintético blanco pulido como espejos, paneles de luz difusa en el techo, plantas ornamentales transgénicas en jardineras geométricas. Dos personajes disfrazados de personal de mantenimiento caminan con la cabeza gacha pasando frente a un arco de escáner biométrico láser con luz roja de seguridad.
* **Prompt para Google Flow / Generador:**
```text
Stark contrasting scene: an immaculate, sterile, ultra-modern luxury corporate hallway inside the Golden Dome. Polished mirror-like white synthetic marble floors, seamless illuminated ceiling light panels, minimalist geometric interior design. Two disguised workers in utilitarian maintenance overalls walking tensely with heads down past a sleek biometric laser security checkpoint arch glowing with thin red scanlines. Dystopian corporate architectural elegance, high contrast, clean vs dirty aesthetic --ar 16:9 --v 6.0
```

---

### 11. El Evento de Resonancia Azul (Clímax)
* **Nombre de fichero:** `11_evento_resonancia_azul.jpg`
* **Ubicación:** `chapters/09_campana_4_fases.tex` (Fase 4)
* **Descripción de la escena:** El clímax caótico en la sala del mainframe. La cúpula de tanques amnióticos colapsando. Un vórtice de arcos voltaicos y rayos de energía azul eléctrico estallan desde el cilindro del procesador central. Monitores CRT explotando en chispas y humo negro. Los personajes cubriéndose en una pasarela de rejilla metálica mientras los tanques se quiebran y el líquido derramado inunda el suelo. Una tormenta psíquica visualizada como distorsiones ópticas en el aire.
* **Prompt para Google Flow / Generador:**
```text
Climactic catastrophic failure inside a colossal high-tech mainframe server chamber. Arcs of intense blinding electric blue lightning and psychic energy tendrils bursting violently from a massive central biological supercomputer core. Exploding glass stasis tanks spilling glowing amniotic fluid across metal grated catwalks. Sparks flying from overloaded CRT terminals, red emergency strobe lights spinning through clouds of electrical smoke. Characters taking cover amidst the chaos, hair and coats whipping in the shockwave. Epic cinematic climax, dynamic high-energy lighting, stunning visual effects --ar 16:9 --v 6.0
```

---

### 12. Epílogo: La Semilla de 2102
* **Nombre de fichero:** `12_epilogo_semilla_2102.jpg`
* **Ubicación:** `chapters/10_epilogo_legado_2102.tex`
* **Descripción de la escena:** Sala de reuniones en penumbra en la cúspide de la Torre Orekak. Tres altos ejecutivos de traje impecable vistos desde atrás, recortados contra un gran ventanal que muestra el amanecer brumoso sobre la colonia. Sobre la mesa de conferencias de vidrio negro se proyecta un holograma volumétrico azul translúcido que muestra el cerebro de un niño recién nacido y diagramas de neuroplasticidad infantil, anunciando la transición hacia el proyecto Velo de 2102.
* **Prompt para Google Flow / Generador:**
```text
Chilling dystopian epilogue scene. A high-altitude executive corporate boardroom shrouded in dim ambient dawn light. Three ruthless corporate directors in tailored suits seen from behind, silhouetted against a panoramic glass window overlooking the sprawling industrial city at sunrise. On the dark obsidian conference table between them, a translucent blue volumetric 3D hologram displays the scan of a newborn infant brain and neuroplasticity charts. Quiet, menacing corporate planning, cold color grading, cinematic storytelling --ar 16:9 --v 6.0
```

---

## 💡 Instrucciones para incorporar las imágenes generadas

1. Genera cada imagen en **Google Flow** utilizando los prompts correspondientes.
2. Descarga la imagen y renómbrala con el **nombre exacto de fichero** indicado en la tabla (ej. `01_distrito7_la_margen.jpg`).
3. Guarda los archivos JPG en la carpeta:
   `/home/samtzai/projects/rol_playing_games/neobilbao-2084/images/`
4. Ejecuta en el directorio del proyecto:
   ```bash
   make
   ```
5. El documento `main.pdf` actualizará automáticamente todas las figuras con tus ilustraciones finales.
