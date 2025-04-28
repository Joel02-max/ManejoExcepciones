# Manejo de Excepciones - C# Windows Forms

Este proyecto es una aplicación de Windows Forms en C# que maneja excepciones durante una operación de división entre dos números. La aplicación captura y maneja diferentes tipos de excepciones, como errores de formato y divisiones por cero, proporcionando mensajes de error adecuados al usuario.

## Funcionalidades

- Permite al usuario ingresar dos números en dos campos de texto.
- Realiza una operación de división entre los dos números.
- Muestra el resultado de la operación en un `Label`.
- Maneja diferentes excepciones:
  - `FormatException`: Si los valores ingresados no son números válidos.
  - `DivideByZeroException`: Si el usuario intenta dividir por cero.
  - `Exception`: Para manejar cualquier otro error inesperado.
- Los campos de entrada se limpian automáticamente después de cada operación, y el foco se coloca en el primer campo de texto.

## Requisitos

- **.NET Framework 4.7.2 o superior**
- **Visual Studio** o cualquier otro IDE compatible con C# y Windows Forms.

## Instalación

1. Clona el repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu_usuario/manejo-excepciones.git
    ```

2. Abre el proyecto en Visual Studio o tu IDE preferido.

3. Ejecuta el proyecto.

## Instrucciones de Uso

1. Ingresa un número en el primer campo de texto.
2. Ingresa otro número en el segundo campo de texto.
3. Haz clic en el botón **"Dividir"** para realizar la operación.
4. El resultado de la división se mostrará en el `Label`.
5. Si ingresas valores no válidos o intentas dividir por cero, aparecerá un mensaje de error adecuado.


## Contribuciones

Si deseas contribuir a este proyecto, puedes seguir estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b nueva-rama`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Sube tus cambios (`git push origin nueva-rama`).
5. Abre un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

