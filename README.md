<p align="center"><img src="banner.png" alt="5 historias basadas en datos" width="100%"></p>

# Historias que los datos cuentan

Cinco historias **basadas en datos reales y verificados**, cada una construida sobre un **arquetipo narrativo distinto** del compendio de la asignatura, y un **reporte crítico** por historia que explica por qué se eligió ese arquetipo y si los datos lo sostienen.

Proyecto de la asignatura **Comunicación en Ciencia de Datos** · autora: **Brianet**

---

## Las 5 historias

| # | Historia | Arquetipo | El dato gancho | Léela |
|---|----------|-----------|----------------|-------|
| 1 | **Más dinero, menos gente**: el misterio de las salas de cine | Confusión aclarada | La taquilla de 2019 fue un 23 % mayor que la de 2002, pero se vendieron un 22 % menos de entradas | [Historia](historia-01-confusion-aclarada.pdf) · [Reporte crítico](critica-01-confusion-aclarada.pdf) |
| 2 | **El disco que no quiso morir** | Caída y recuperación | De 0,9 millones de vinilos vendidos en EE. UU. (2006) a 46,8 millones (2025) | [Historia](historia-02-caida-y-recuperacion.pdf) · [Reporte crítico](critica-02-caida-y-recuperacion.pdf) |
| 3 | **Night City: el juego que se arrepintió** | Renacimiento | Cyberpunk 2077: de un lanzamiento con reembolsos a más de 35 millones de copias | [Historia](historia-03-renacimiento.pdf) · [Reporte crítico](critica-03-renacimiento.pdf) |
| 4 | **Palworld: 2,1 millones de jugadores en una semana… y el después** | Ascenso y caída | El pico diario cayó ≈95 % en dos meses; en 2026, la versión 1.0 recuperó el 41 % del pico | [Historia](historia-04-ascenso-y-caida.pdf) · [Reporte crítico](critica-04-ascenso-y-caida.pdf) |
| 5 | **Lo dicen todos, lo hacemos todos** | Ironía | El 48 % de los adolescentes dice que las redes dañan a otros; el 14 %, que les dañan a ellos; el 46 % está casi constantemente en internet | [Historia](historia-05-ironia.pdf) · [Reporte crítico](critica-05-ironia.pdf) |

## Cómo está hecho

- **Datos verificados.** Cada cifra tiene fuente y está en [`datos-y-fuentes.md`](datos-y-fuentes.md). Lo calculado por mí se marca como *cálculo propio*; lo inferido, como *inferido*.
- **El arquetipo se somete a prueba.** Cada reporte aplica la matriz de verificación del compendio (§4.5.1: señal a favor y señal en contra) y declara dónde el patrón **no** se sostiene del todo. Cuando los datos no dan para el patrón, se dice.
- **Sin villanos ni causas inventadas.** Los datos dicen *cuándo* y *cuánto*, no siempre *por qué*; las historias lo respetan.
- **Regla de cierre.** Si al quitar el arquetipo el mensaje sigue siendo verdad, el arquetipo sirvió a los datos y no al revés.

## Qué contiene cada reporte crítico

1. Qué cuenta la historia.
2. Por qué este arquetipo y no otro (con tabla pieza del patrón → historia, y patrones descartados).
3. Matriz de verificación (§4.5.1).
4. Las cinco preguntas de elección (§4.5.2).
5. Pruebas de tensión sin invención (§3.3: Knaflic, Lo Duca, reverso y costo).
6. Límites (§4.5.3) y regla de cierre.
7. Decisiones de diseño, qué quedó fuera y cómo se verificó.

## Archivos

```
README.md                      ← esta página
banner.png
datos-y-fuentes.md             ← cifras y fuentes de cada historia
historia-0X-<arquetipo>.pdf    ← las 5 historias
critica-0X-<arquetipo>.pdf     ← los 5 reportes críticos
```

*Las gráficas están dentro de los PDF (hechas con Python y matplotlib).*
