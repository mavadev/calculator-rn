#  Calculadora Moderna 🔢

Este proyecto es una calculadora moderna desarrollada en React Native, inspirada en la interfaz de la calculadora de iOS. En esta nueva versión, se han añadido mejoras para permitir realizar operaciones más elaboradas directamente en pantalla, mostrando el resultado en tiempo real mientras se introduce la fórmula. Además, se han realizado cambios de estilo con una paleta de colores más moderna, y ahora los íconos son de Material Community Icons provistos por `react-native-vector-icons`.

## :pushpin: Características principales
- **Interfaz iOS Moderna:** La interfaz de usuario está inspirada en el diseño de la calculadora de iOS, brindando una experiencia estética y funcional similar.
- **Operaciones Elaboradas:** A diferencia de versiones anteriores, ahora los usuarios pueden escribir operaciones largas y complejas, permitiendo que la calculadora evalúe fórmulas completas con la prioridad de operadores correcta.
- **Resultado en Tiempo Real:** Mientras los usuarios escriben la fórmula, el resultado se actualiza dinámicamente en un subtexto para mostrar el valor de la operación en curso.
- **Hook Personalizado:** Toda la lógica de cálculo sigue centralizada en el hook personalizado  `useCalculator`, pero ahora maneja operaciones más largas y complejas con manejo adecuado de la precedencia de operadores.
- **Iconos de Vector Icons:** Se reemplazaron los íconos anteriores ( Iconify ), proporcionados por la librería `react-native-vector-icons`, para un diseño visual más coherente y moderno.
- **Estilo Moderno:** Se actualizó el esquema de colores a uno más moderno y diferente al original, alineado con el diseño de aplicaciones contemporáneas.

## :dart: Instalación y Ejecución
Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/mavadev/RN_Calculadora.git

2. Navega al directorio del proyecto:
   ```bash
   cd RN_Calculadora

3. Instala las dependencias:
   ```bash
   npm install

4. Ejecuta la aplicación:
   ```bash
    npm run android # para Android
    npm run ios # para iOS

## :iphone: Interfaz de Usuario
La interfaz ahora permite a los usuarios escribir operaciones largas y ver el resultado actualizado en tiempo real. El diseño utiliza una paleta de colores modernos y un nuevo set de íconos provistos por Material Community Icons.

| Calculadora | Operación |
|:---------:|:------------:|
| <img src="https://github.com/user-attachments/assets/7c4ae08d-ed2e-47de-839d-cc2930094a42" alt="captura1" width="320"/> |<img src="https://github.com/user-attachments/assets/2ec2f0a3-c505-412f-883f-6d43800f02cb" alt="captura2" width="320"/> |
