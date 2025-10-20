# Teclado Microtonal 53-TET

Teclado hexagonal para el sistema de temperamento igual de 53 notas por octava (53-TET / 53-EDO).

## Características

- **Disposición hexagonal** de teclas para fácil visualización de intervalos
- **Sistema 53-TET completo**: 75 teclas totales distribuidas en 3 octavas
  - Octava baja: 9 notas de octava anterior (44-52) + 22 notas (0-21)
  - Octava media: 31 notas (22-52)
  - Octava alta: 23 notas (0-22)
- **Visualización de escalas** con resaltado de notas
- **Modo de combinación de escalas** para explorar superposiciones armónicas
- **Controles de transposición** de octava (+8va, -8va, Reset)
- **Monitor de polifonía en tiempo real**: 
  - Visualización de todas las notas activas simultáneamente
  - Contador de voces activas
  - Información de frecuencia y octava por cada nota
  - Chips de colores según la octava
  - Orden cronológico de notas pulsadas
- **Información monofónica**: Muestra la última nota tocada
- **Integración con Max/MSP** mediante `window.max.outlet()`
- **Soporte parcial de teclado QWERTY** (32 teclas mapeadas + controles)

## Uso

### Online
Simplemente abre `index.html` en tu navegador web.


## Escalas incluidas

### Modos Griegos (adaptados a 53-TET)
- **Jónico (Mayor)**: Do-Re-Mi-Fa-Sol-La-Si
- **Dórico**: Do-Re-Mib-Fa-Sol-La-Sib
- **Frigio**: Do-Reb-Mib-Fa-Sol-Lab-Sib
- **Lidio**: Do-Re-Mi-Fa#-Sol-La-Si
- **Mixolidio**: Do-Re-Mi-Fa-Sol-La-Sib
- **Eólico (Menor)**: Do-Re-Mib-Fa-Sol-Lab-Sib
- **Locrio**: Do-Reb-Mib-Fa-Solb-Lab-Sib

### Escalas Especiales
- **Cromática**: Las 53 notas del sistema
- **Tonos Enteros**: 6 notas separadas por tonos enteros
- **Pentatónica Mayor**: 5 notas en modo mayor
- **Pentatónica Menor**: 5 notas en modo menor
- **Blues**: Escala blues de 6 notas
- **Armónica Menor**: Escala armónica menor de 7 notas

## Controles

### Ratón
- **Clic en tecla**: Reproducir nota
- **Mantener presionado**: Nota sostenida
- **Hover**: Vista previa del color de activación
- **Clic en chip de nota**: Detener nota específica en modo polifonía

### Teclado QWERTY - Mapeo Parcial (32 notas)

```
┌──────────────────────────────────────────────────────────────────
│ Fila 1-0:  1  2  3  4  5  6  7  8  9  0                
│           44 45 46 47 48 49 50 51 52  0         
│           (La#)(Sib)(Sib+)(Sin)(Si-)(Si)(Si+)(Si#)(Do-)(Do)
├──────────────────────────────────────────────────────────────────
│ Fila Q-]:  Q  W  E  R  T  Y  U  I  O  P  [  ]            
│            1  2  3  4  5  6  7  8  9 10 11 12           
│           (Do+)(Don)(Do#-)(Do#)(Reb)(Reb+)(Ren-)(Re-)(Re)(Re+)(Ren+)(Re#-)
├──────────────────────────────────────────────────────────────────
│ Fila A-L:  A  S  D  F  G  H  J  K  L                  
│           13 14 15 16 17 18 19 20 21           
│           (Re#)(Mib)(Mib+)(Min)(Mi-)(Mi)(Mi+)(Mi#)(Fa-)
├──────────────────────────────────────────────────────────────────
│ Fila Z-/:  Z  X  C  V  B  N  M  ,  .  /                
│           22 23 24 25 26 27 28 29 30 31        
│           (Fa)(Fa+)(Fan)(Fa#-)(Fa#)(Solb)(Solb+)(Soln-)(Sol-)(Sol)
└──────────────────────────────────────────────────────────────────
```

#### Controles de octava:
- **↑ Flecha Arriba**: +8va (subir octava)
- **↓ Flecha Abajo**: -8va (bajar octava)  
- **Barra Espaciadora**: Reset octava a 0

### Controles de interfaz
- **+8va / -8va**: Transponer octavas (también con flechas ↑↓)
- **Reset Octava**: Volver a octava base (también con Espacio)
- **Selector de escala**: Elegir escala o modo
- **Combinar escalas**: Activar modo de superposición de escalas
- **Limpiar escalas**: Resetear visualización de escalas

### Atajos útiles
- Mantén presionadas múltiples teclas para tocar acordes
- Usa las flechas mientras tocas para cambiar de octava en tiempo real
- El espacio te permite volver rápidamente a la octava central

## Disposición del teclado

- **Octava baja (b)**: valores 163-193 (31 notas: 44-52 de octava anterior + 0-21)
- **Octava media (m)**: valores 194-224 (31 notas: 22-52)
- **Octava alta (a)**: valores 225-247 (23 notas: 0-22)

**Total**: 75 teclas hexagonales (85 notas)

## Compositores y usos del 53-TET

- **Jing Fang** (siglo I a.C.) - Matemático chino que propuso por primera vez la división en 53 partes
- **Nicholas Mercator** (siglo XVII) - Redescubrió el sistema en Europa
- **R.H.M. Bosanquet** - Construyó un armonio generalizado con 53 notas (1876)
- **Adriaan Fokker** - Construyó un órgano de 31 tonos y estudió el 53-TET
- **Joel Mandelbaum** - Compositor estadounidense que utilizó extensivamente el 53-TET
- **Isaac Newton** - Propuso un sistema musical basado en 53 divisiones
- **Música experimental moderna**: Utilizado por diversos compositores para explorar armonías microtonales con precisión

