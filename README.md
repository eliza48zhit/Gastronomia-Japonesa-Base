🇯🇵 Gastronomía Japonesa - Smart Contract (Base Mainnet)
Este contrato inteligente rinde homenaje a la milenaria y estética cultura culinaria de Japón, desplegado en la red Base. Utiliza una arquitectura de almacenamiento persistente que permite registrar cada especialidad japonesa de forma individual, creando un museo digital donde la tradición se encuentra con la inmutabilidad de la blockchain.

🔗 Verificación en Basescan

El contrato ha sido verificado satisfactoriamente, permitiendo que cualquier entusiasta de la cultura japonesa pueda explorar el menú, proponer nuevas delicias y participar en la votación de los platos más icónicos.

Contract Address: 0xbea6510cb6f3c4f50bdb6ff8e74f37d48dc104ab

Explorer Link: [Ver en Basescan
](https://basescan.org/address/0xbea6510cb6f3c4f50bdb6ff8e74f37d48dc104ab#code)
🛠️ Detalles Técnicos

Este contrato implementa una gestión de datos de alto nivel:

Estructuras Dinámicas (struct): Cada plato es un objeto que contiene su nombre, descripcion y un contador de likes en tiempo real.

Historial Acumulativo (mapping): Los platos se almacenan de forma permanente. Cada entrada genera un nuevo ID único (1, 2, 3...), preservando el archivo histórico.

Capa de Interacción Social: Incluye una función de votación para que la comunidad destaque platos como el Sushi, el Ramen o el Takoyaki.

Optimización de Gas: Límite estricto de 200 caracteres por registro para asegurar la eficiencia en la red.

📖 Instrucciones de Interacción

Consultar Menú: En la pestaña Read Contract, usa consultarPlato con un número de ID (ej. 1 para Sushi Nigiri) para obtener los detalles.

Registrar Plato: En la pestaña Write Contract, usa registrarPlato para añadir nuevas especialidades (ej. "Sopa de Miso", "Caldo a base de soja con tofu, algas y cebollino").

Votar: Usa darLikeAlPlato con el ID correspondiente para sumar tu apoyo a una receta.

🐈 Nota de Autoría
"Este contrato fue desarrollado bajo la silenciosa compañía de mi gato y la inspiración de mis lecturas. En Japón, el Maneki-neko atrae la fortuna; este contrato busca atraer y preservar el conocimiento culinario en la blockchain."
