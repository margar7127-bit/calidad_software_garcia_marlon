# Calidad de Software

Repositorio de la materia de Calidad de Software.

## Objetivo

Este repositorio tiene como finalidad documentar y practicar los conceptos básicos de calidad de software, con especial atención a las pruebas automatizadas y su importancia para garantizar la confiabilidad de una aplicación.

## ¿Qué es la calidad de software?

La calidad de software se refiere a qué tan bien cumple un sistema con los requisitos, expectativas y estándares de funcionamiento, mantenibilidad y seguridad. Algunos aspectos clave son:

- Correctitud
- Confiabilidad
- Mantenibilidad
- Escalabilidad
- Seguridad
- Usabilidad

## Pruebas unitarias 

Las pruebas unitarias consisten en validar una parte muy pequeña del sistema, normalmente una función o un método, de forma aislada.

### Objetivo

- Comprobar que cada unidad realiza lo que se espera.
- Detectar errores temprano.
- Facilitar el mantenimiento y la refactorización.

### Características

- Se ejecutan de forma rápida.
- Son altamente automatizadas.
- Generalmente usan entradas y salidas simples.
- Deben ser aisladas y no depender de otros módulos.

### Ejemplo

Una función que suma dos números puede probarse con varios casos:

- 2 + 3 = 5
- 0 + 0 = 0
- 5 + (-2) = 3

## Pruebas E2E (End-to-End)

Las pruebas E2E verifican el comportamiento real del sistema completo, desde la interfaz o punto de entrada hasta la respuesta final, simulando el flujo que realiza un usuario.

### Objetivo

- Validar que el sistema funciona como un todo.
- Probar flujos reales de negocio.
- Detectar errores de integración entre componentes.

### Características

- Son más lentas que las pruebas unitarias.
- Cubren escenarios más completos.
- Ayudan a validar la experiencia del usuario.
- Suelen ejecutarse en entornos más cercanos a producción.

### Ejemplo

Una prueba E2E puede validar que un usuario:

1. Inicia sesión.
2. Navega a la pantalla de productos.
3. Agrega un artículo al carrito.
4. Finaliza la compra.
5. Observa el mensaje de confirmación.

## Relación entre pruebas unitarias y E2E

Ambas son importantes y se complementan:

- Las pruebas unitarias detectan errores a nivel de lógica y sirven como primera línea de defensa.
- Las pruebas E2E validan que el sistema funciona en conjunto y que el flujo del usuario es correcto.

Una estrategia recomendada es combinar ambas: muchas pruebas unitarias y algunas pruebas E2E clave.

## Buenas prácticas

- Escribir pruebas claras y descriptivas.
- Mantenerlas pequeñas y enfocadas.
- Probar casos positivos y negativos.
- Evitar dependencias innecesarias.
- Ejecutar pruebas con frecuencia.
- Priorizar escenarios críticos.

## Conclusión

La calidad de software se fortalece cuando se incorporan pruebas automatizadas desde el inicio del desarrollo. Las pruebas unitarias permiten validar comportamientos específicos, mientras que las pruebas E2E aseguran que el sistema completo cumple con los requisitos del usuario.

## Referencias rápidas

- Unit tests: validan lógica aislada.
- E2E tests: validan flujos completos del sistema.
- Calidad de software: garantiza confiabilidad, mantenibilidad y valor para el usuario.
