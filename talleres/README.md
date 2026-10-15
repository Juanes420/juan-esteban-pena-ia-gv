# Talleres — Inteligencia Artificial (SI3003, EAFIT)

Entrega de los talleres de las semanas 4 a 8. Todos los notebooks están ejecutados (con sus salidas) y con las respuestas escritas.

| Semana | Carpeta | Contenido |
|---|---|---|
| 4 | `semana_04_mdp/` | MDP del almacén: Value Iteration, Policy Iteration y experimentos |
| 5 | `semana_05_q_learning/` | Q-Learning en FrozenLake y en Taxi |
| 6 | `semana_06_ml_wine/` | Pipeline de ML con el dataset de vinos (3 retos encadenados: 01 → 02 → 03) |
| 7 | `semana_07_redes_neuronales/` | Redes neuronales en Keras 3: CIFAR-10 en grises y Olivetti Faces |
| 8 | `semana_08_transfer_learning/` | Transfer learning con EfficientNetB0 (bicicleta / motocicleta / bus) |

## Notas
- **Semana 6:** los tres notebooks se ejecutan en orden desde su carpeta; cada uno usa los archivos que genera el anterior (`data/processed/`, `artifacts/`, `reports/`).
- **Semana 7 (Olivetti):** se estandarizan las entradas con la media y desviación de entrenamiento; con eso el modelo aprende (test 87.5 %, validación 91.7 %). Sin ese paso, en una ejecución anterior se quedó en el azar (2.5 %).
- **Semana 8:** el dataset se descarga al ejecutar el notebook (no se incluyen las imágenes; están en `.gitignore`).
