# Multímetro Digital con Arduino

## Descripción del Proyecto
Este proyecto implementa un multímetro digital utilizando Arduino, capaz de medir voltaje, corriente, resistencia y continuidad. Es una solución de código abierto para realizar mediciones eléctricas básicas con un dispositivo personalizado.

## Características
- Medición de voltaje DC y AC
- Medición de corriente
- Medición de resistencia
- Prueba de continuidad
- Pantalla LCD para visualización de resultados
- Interfaz de usuario simple
- Calibración precisa

## Componentes Necesarios
- Arduino Uno o Arduino Mega
- Pantalla LCD 16x2
- Módulo de referencia de voltaje
- Resistencias de precisión
- Cables de prueba
- Protoboard
- Componentes electrónicos varios

## Instalación
1. Clonar el repositorio
```bash
https://github.com/yiixaj/Multimetro-arduino.git
```

2. Abrir el proyecto con Arduino IDE
3. Instalar las bibliotecas necesarias:
   - LiquidCrystal
   - Wire
   - SPI

## Uso
1. Conectar los cables de prueba
2. Seleccionar modo de medición
3. Realizar la medición
4. Leer el resultado en la pantalla LCD

## Calibración
El proyecto incluye rutinas de calibración para garantizar mediciones precisas. Consultar la sección de calibración en el código fuente.

## Limitaciones
- Rango de medición limitado
- Precisión dependiente de la calidad de los componentes
- No apto para mediciones profesionales de alta precisión

## Agradecimientos
- Comunidad Arduino
- Proyectos de código abierto
