# Cuenta mixta

App para iPhone (y cualquier móvil) para llevar entre dos una **cuenta mixta proporcional**: cada uno tiene su cuenta, y a la cuenta común (Openbank) va solo lo de los gastos de casa, poniendo cada uno según lo que cobra ese mes.

App: https://edriderofficial-afk.github.io/cuentas-de-casa/

## Qué hace

- **Mes**: pones los sueldos y los gastos de ese mes (luz, agua… cambian cada mes) y te dice cuánto transfiere cada uno a la cuenta común y cuánto le queda. Botón para copiar el importe y marcar la transferencia como hecha.
- **Historial**: todos los meses guardados, gráfico de gastos y lo que lleva puesto cada uno en el año.
- **Ajustes**: nombres, reparto (según sueldo o a medias), plantilla de gastos (fijos y variables), conexión entre los dos móviles y copias de seguridad.
- Modo oscuro automático, se instala en la pantalla de inicio y funciona sin conexión.

## Dónde se guardan los datos

Este repositorio es público y **solo contiene la app, nunca vuestros datos**.

Los datos se guardan en el móvil y, si lo conectáis, en un archivo `cuentas.json` dentro de un **repositorio privado aparte** (`cuentas-de-casa-datos`). Los dos móviles leen y escriben ese archivo, así que veis lo mismo y queda guardado mes a mes (con historial de cambios de GitHub).

## Puesta en marcha (una vez)

1. Crea el repositorio privado: github.com/new › nombre `cuentas-de-casa-datos` › **Private** › Create repository.
2. Crea una clave: GitHub › Settings › Developer settings › Personal access tokens › **Fine-grained tokens** › Generate new token.
   - Repository access: **Only select repositories** › `cuentas-de-casa-datos`.
   - Permissions › Repository permissions › **Contents: Read and write**.
   - Generate token y cópiala (empieza por `github_pat_`).
3. En tu iPhone, abre la app en Safari › Compartir › **Añadir a pantalla de inicio**. Ábrela desde el icono.
4. Ajustes › pega la clave › **Conectar**.
5. Para usarla también en el PC: en el iPhone, Ajustes › **Copiar código para otro dispositivo**. Abre la app en el navegador del PC, Ajustes › pega el código › **Conectar con código**.

Cuando la clave caduque, crea otra igual, pulsa «Desconectar este móvil» y vuelve a conectar (en cada dispositivo).

La versión anterior de la app («Cuentas de casa») sigue en el historial de este repositorio.
