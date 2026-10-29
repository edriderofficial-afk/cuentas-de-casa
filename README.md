# Cuentas de casa

Web para llevar entre dos los ingresos, gastos, ahorro y deudas de casa. Es un solo archivo (`index.html`): no tiene servidor, cuentas de usuario ni base de datos.

## Qué hace

- **Resumen**: lo que os queda libre, la tasa de ahorro, la rueda de gasto por grupo con el presupuesto de cada uno, la regla 50/30/20, quién debe a quién en los gastos comunes y la evolución del año.
- **Movimientos**: apuntar ingresos, gastos, ahorro y traspasos entre cuentas, con buscador y filtros.
- **Plan**: presupuesto mensual por grupo, recibos fijos (se marcan solos), deudas con estrategia avalancha e intereses ahorrados, y metas de ahorro.
- **Cuentas**: saldo de cada cuenta y patrimonio neto.
- **Ajustes**: nombres, forma de repartir (a medias, porcentaje fijo o según ingresos), categorías y copias de seguridad.

## Dónde se guardan los datos

En el navegador de cada móvil. **No se suben a GitHub ni a ningún otro sitio**: el repositorio solo contiene la página vacía.

Para llevarlo entre los dos: en Ajustes, uno pulsa «Descargar copia» y se la manda al otro, que la importa con «Combinar con lo mío». Se juntan los movimientos de los dos sin duplicar nada.

Haced una copia de vez en cuando: si se borran los datos del navegador, se pierde lo que no esté en una copia.

## Publicarla con GitHub Pages

1. Sube `index.html` a la rama `main` de un repositorio.
2. En el repositorio, ve a **Settings › Pages**, elige «Deploy from a branch», rama `main`, carpeta `/ (root)` y guarda.
3. En un par de minutos estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

En el móvil, ábrela y elige «Añadir a pantalla de inicio» para usarla como una app.
