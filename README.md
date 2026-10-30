# Cuentas de casa

Web para llevar entre dos los ingresos, gastos, ahorro y deudas de casa. Es un solo archivo (`index.html`): no tiene servidor, cuentas de usuario ni base de datos.

## Qué hace

- **Inicio**: lo que os queda libre este mes, en qué se va el dinero (rueda de gasto) y quién debe a quién. «Más detalle» muestra la regla 50/30/20 y el año mes a mes.
- **Movimientos**: todo lo apuntado, con filtros y buscador. El botón **+** apunta un gasto, ingreso o ahorro en dos toques.
- **Objetivos**: topes de presupuesto, recibos del mes, metas de ahorro, deudas y patrimonio.
- **Ajustes**: nombres, cómo repartís los gastos, compartir con la pareja, cuentas, categorías y exportar.

## Dónde se guardan los datos

En el navegador de cada móvil. **No se suben a GitHub ni a ningún otro sitio**: el repositorio solo contiene la página vacía.

Para llevarlo entre los dos: en Ajustes › Compartir, uno pulsa «Enviar copia» y se la manda al otro, que la importa con «Combinar con lo mío». Se juntan los movimientos de los dos sin duplicar nada.

Haced una copia de vez en cuando: si se borran los datos del navegador, se pierde lo que no esté en una copia.

## Publicarla con GitHub Pages

1. Sube `index.html` a la rama `main` de un repositorio.
2. En el repositorio, ve a **Settings › Pages**, elige «Deploy from a branch», rama `main`, carpeta `/ (root)` y guarda.
3. En un par de minutos estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

En el móvil, ábrela y elige «Añadir a pantalla de inicio» para usarla como una app.
