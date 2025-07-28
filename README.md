
# Conversor de Monedas 🪙💱

Este proyecto permite convertir pesos chilenos a otras monedas extranjeras usando datos en tiempo real desde la API de [mindicador.cl](https://mindicador.cl/). Además, muestra un gráfico con el historial de los últimos 10 días del valor de la moneda seleccionada.

## 🧰 Tecnologías utilizadas

- HTML5, CSS3 (fuente moderna: Inter)
- JavaScript (ES6)
- Fetch API + manejo de errores con try/catch
- [Chart.js](https://www.chartjs.org/) para graficar los valores

## 📦 Estructura de carpetas

```
conversor_monedas/
├── index.html
├── js/
│   └── app.js
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── img/  (opcional)
└── mindicador.json (solo en caso de respaldo)
```

## 🚀 Cómo usar

1. Abre `index.html` en tu navegador.
2. Ingresa un monto en pesos chilenos.
3. Selecciona una moneda (ej: dólar, euro).
4. Haz clic en "Convertir".
5. Verás el resultado y el gráfico actualizado.

## 🧪 Modo offline

Si la API está caída, el sistema usa un archivo local `mindicador.json` como respaldo.

---

💡 Proyecto desarrollado como parte del curso de JavaScript y consumo de APIs de [Desafío Latam](https://desafiolatam.com/).
