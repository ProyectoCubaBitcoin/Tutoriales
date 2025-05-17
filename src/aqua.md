# Tutorial: Cómo usar la billetera AQUA

AQUA es una billetera para Bitcoin y Liquid desarrollada por Jan3. Permite recibir y enviar BTC en la cadena principal, L-BTC y L-USDT, ambos tokens de la red Liquid. Además, también permite la recepción y envío de otros tokens de la red Liquid y USDT en al menos 4 cadenas más.

---

## Índice

1. [Crear o restaurar una billetera](#crear-o-restaurar-una-billetera)
2. [Interfaz principal y activos disponibles](#interfaz-principal-y-activos-disponibles)
3. [Acceder a los ajustes de configuración](#acceder-a-los-ajustes-de-configuración)
4. [Respaldo de la billetera (semilla)](#respaldo-de-la-billetera-semilla)
5. [Recomendaciones sobre el respaldo](#recomendaciones-sobre-el-respaldo)
6. [Intercambiar entre activos](#intercambiar-entre-activos)
7. [Recibir fondos](#recibir-fondos)
8. [Enviar fondos](#enviar-fondos)
9. [Mercado](#mercado)

---

## Crear o restaurar una billetera

Al abrir la app AQUA por primera vez, verás dos opciones: **Crear billetera nueva** o **Restaurar billetera**. Si estás comenzando desde cero, selecciona "Crear billetera nueva".

![Pantalla inicial de AQUA](./assets/images/aqua/inicio.jpg)

---

## Interfaz principal y activos disponibles

Una vez creada la billetera, la interfaz principal mostrará tus activos disponibles y su valor aproximado.

![Interfaz con activos](./assets/images/aqua/iniciada.jpg)

---

## Acceder a los ajustes de configuración

Pulsa el ícono de engranaje en la parte inferior derecha para acceder a los ajustes. Aquí puedes configurar la moneda de referencia, habilitar funciones avanzadas, etc.

![Ajustes de configuración](./assets/images/aqua/ajustes.jpg)

---

## Respaldo de la billetera (semilla)

Es muy importante hacer un respaldo de tu billetera. AQUA te mostrará una advertencia para que respaldes la frase semilla (de 12 palabras).

![Respaldo de semilla](./assets/images/aqua/backup_frase.jpg)

---

## Recomendaciones sobre el respaldo

Antes de mostrarte la semilla, AQUA te brinda recomendaciones sobre cómo protegerla. Tómate este momento en serio.

![Consejos para respaldar](./assets/images/aqua/backup_frase2.jpg)

---

## Intercambiar entre activos

AQUA permite intercambiar entre activos de la red Liquid, como L-BTC y L-USDT, directamente desde la app. Es una función útil si necesitas convertir tus fondos sin salir de la billetera. Actualmente, AQUA **no permite intercambiar BTC (on-chain)**, solo activos dentro de Liquid.

![Intercambio entre activos](./assets/images/aqua/intercambiables.jpg)

---

## Recibir fondos

Al seleccionar **RECIBIR**, podrás escoger entre varias opciones de activos:

- **Bitcoin on-chain** (BTC)
- **Tokens de la red Liquid** como L-BTC, L-USDT y otros
- **Bitcoin Lightning**
- **USDT en las cadenas Ethereum, Tron, BSC y Polygon**

En los casos de Lightning y USDT en estas cadenas, AQUA realiza un **swap automático**:

- Los fondos recibidos por Lightning se convierten en **L-BTC**.
- Los USDT recibidos en Ethereum, Tron, BSC o Polygon se convierten en **L-USDT**.


![Recibir fondos](./assets/images/aqua/recibir1.jpg)


---

## Enviar fondos

Al presionar **ENVIAR**, puedes seleccionar el activo y la red de destino:

- **BTC on-chain**
- **Tokens de la red Liquid** como L-BTC, L-USDT y otros
- **Bitcoin Lightning**
- **USDT en las cadenas Ethereum, Tron, BSC y Polygon**

Cuando envías por Lightning o en las cadenas mencionadas, AQUA realiza un **swap desde tu saldo en Liquid**:

- El envío por Lightning se hace a partir de **L-BTC**.
- El envío de USDT en Ethereum, Tron, BSC o Polygon se hace a partir de tu saldo en **L-USDT**.

![Enviar fondos](./assets/images/aqua/enviar1.jpg)

---

## Mercado

En la barra inferior central encontrarás el botón **Mercado**, que te da acceso a tres funciones:

- **Comprar BTC** directamente desde la app.
- **Intercambio P2P** de activos con otros usuarios.
- **BTC Map**, donde puedes localizar negocios que aceptan Bitcoin en tu zona.

![Mercado](./assets/images/aqua/mercado.jpg)

---

