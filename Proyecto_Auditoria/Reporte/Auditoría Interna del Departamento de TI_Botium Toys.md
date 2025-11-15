# 📄Informe de Auditoría Interna de Seguridad del Departamento de Tecnologías de la Informática — Botium Toys


Fecha: Noviembre, 2025  
Elaborado por: Ginely De Vita  
Curso: Fundamentos de Ciberseguridad – Simulación de Auditoría Interna  
Organización: Botium Toys (Ejercicio ficticio)  

## Índice  

* [Resumen ejecutivo](Resumen-ejecutivo)  
* [1. Introducción](introduccion)  
* [2. Alcance y objetivos](alcance-y-objetivos)  
* [3. Metodología](metodologia)
* [4. Resultados y observaciones](resultados-y-observaciones)   
* [5. Análisis de riesgos](analisis-de-riesgos)    
* [6. Evaluación del cumplimiento](evaluacion-del-cumplimiento)   
* [7. Evaluación de los controles](evaluacion-de-los-controles)    
* [8. Recomendaciones](recomendaciones)    
* [9. Conclusión](conclusion)    
* [Anexo Referencias](anexo-referencias)

## Resumen Ejecutivo

Esta auditoría interna de TI evalúa la postura de ciberseguridad de Botium Toys, una pequeña empresa de juguetes con sede en EE. UU., una única oficina física y una presencia global en el comercio electrónico en rápida expansión. La auditoría se inició debido al aumento de las exigencias operativas del departamento de TI y a la creciente exposición a clientes internacionales y requisitos normativos.

La evaluación reveló varias deficiencias de alto riesgo: gestión incompleta de activos, controles insuficientes en sistemas críticos, falta de procedimientos documentados y posible incumplimiento de marcos normativos como PCI DSS, RGPD y las mejores prácticas del sector alineadas con el Marco de Ciberseguridad (CSF) del NIST. La puntuación de riesgo general actual es de 8/10, debido principalmente a la falta de controles y a la escasa visibilidad de los activos y los permisos de acceso de los usuarios.

Es necesario tomar medidas correctivas inmediatas para fortalecer las defensas del sistema, cumplir con las obligaciones de cumplimiento relacionadas con los pagos en línea y los clientes de la UE, y respaldar el crecimiento de la empresa. Los hallazgos justifican la solicitud del gerente de TI de ampliar el equipo de ciberseguridad para satisfacer las necesidades operativas y de cumplimiento.

## 1. Introducción  

Este informe documenta los resultados de una auditoría interna simulada de seguridad informática realizada a Botium Toys como parte de un programa de capacitación en ciberseguridad. El ejercicio se basa íntegramente en documentación de auditoría ficticia, pero realista, que incluye:

* Instrucciones del escenario  
* Alcance y objetivos definidos por la dirección de TI  
* Una evaluación formal de riesgos  
* Una evaluación de la aplicabilidad de los controles  
* Una lista de verificación de los requisitos de cumplimiento  
* Un memorándum para las partes interesadas  
* Una referencia de las categorías de control  

Botium Toys mantiene infraestructura local para sus operaciones comerciales y, al mismo tiempo, gestiona un mercado global en línea. Estas condiciones aumentan la exposición de la organización a amenazas de seguridad y obligaciones regulatorias, lo que exige una revisión integral de su postura de seguridad.

## 2. Alcance y Objetivos

### 2.1 Alcance  
El alcance, definido por el responsable de TI, abarca todo el programa de seguridad informática, incluyendo:
* Permisos de usuario en:  
    * Sistemas de contabilidad  
    * Detección de endpoints
    * Firewalls
    * Sistema de detección de intrusiones (IDS)
    * Gestión de información y eventos de seguridad (SIEM)
    * Controles actuales implementados en los sistemas mencionados
    * Procedimientos y protocolos de TI relacionados con el uso del sistema
    * Cumplimiento con las normativas estadounidenses e internacionales aplicables
    * Inventario de hardware, sistemas y accesos
    * Activos heredados y obsoletos que requieren monitorización  

### 2.2 Objetivos

El gerente de TI estableció los siguientes objetivos:  
* Alinear el programa con el Marco de Ciberseguridad (CSF) del NIST
* Fortalecer los controles y procesos del sistema
* Aplicar el principio de mínimo privilegio
* Mejorar la preparación para el cumplimiento de las normativas estadounidenses y europeas
* Desarrollar políticas, procedimientos y manuales de procedimientos fundamentales
* Proporcionar evidencia que justifique la ampliación del equipo de seguridad informática

 ## 3. Metodología

Esta auditoría empleó el siguiente enfoque:  

### 3.1 Revisión de documentos

Se analizaron los documentos proporcionados por el escenario:  
* Evaluación de riesgos
* Lista de verificación de aplicabilidad de controles
* Lista de verificación de cumplimiento
* Instrucciones del escenario 
* Categorías de control
* Memorándum para las partes interesadas

### 3.2 Evaluación de riesgos

* Se evaluaron el impacto y la probabilidad con base en la puntuación de riesgo proporcionada.
* Las deficiencias se asignaron a las categorías del Marco de Factores de Conformidad (CSF) del NIST.
  
### 3.3 Revisión de controles

* Los controles se marcaron como “Aplicables” o “No aplicables” utilizando la lista de verificación de evaluación.
* Los controles faltantes se asignaron a las necesidades de remediación inmediatas o futuras.  

### 3.4 Mapeo de cumplimiento

* Se revisó la exposición a PCI DSS y al RGPD de la UE con base en:
    * Procesamiento de pagos en línea
    * Base de clientes internacionales
  
### 3.5 Síntesis para el informe

* Los hallazgos se clasificaron como Inmediatos (alto riesgo) o Futuros (riesgo medio/bajo).
* Las recomendaciones se alinearon con los estándares de la industria y las limitaciones organizacionales.

## 4. Hallazgos y Observaciones

### 4.1 Hallazgos Inmediatos (de Alto Riesgo)

#### 1. Gestión de Activos Inadecuada
* No existe un inventario completo de hardware, software ni accesos.
* Impacto desconocido en caso de fallo o vulneración de los activos.  

#### 2. Falta de Controles Críticos

* Los sistemas clave carecen de configuraciones necesarias, tales como:
    * Reglas de firewall adecuadas
    * Ajuste del IDS
    * Políticas de protección de endpoints
    * Reglas de correlación del SIEM  

#### 3. Permisos de Usuario Inconsistentes

* Varios usuarios poseen privilegios elevados sin justificación.
* No existe un proceso estandarizado de aprovisionamiento/desaprovisionamiento.
* No se aplica el principio de mínimo privilegio.

#### 4. Posible Incumplimiento

* Riesgo de RGPD debido a clientes de la UE y falta de gobernanza de la privacidad.
* Riesgo de PCI DSS debido al procesamiento de pagos en línea sin controles documentados.
* Falta documentación para:
    * Retención de datos
    * Control de acceso
    * Respuesta a incidentes

### 4.2 Hallazgos de riesgo medio/bajo  

#### 1. Falta de políticas y procedimientos formales
* Falta un protocolo de respuesta ante incidentes
* La gestión de cambios no está documentada
* No existe un programa de concientización sobre seguridad  

#### 2. Deficiencias tecnológicas  
* Algunos sistemas están obsoletos y requieren supervisión humana
* Los sistemas heredados aumentan el riesgo operativo

#### 3. Supervisión del acceso de proveedores
* No se supervisa el acceso de terceros
* No se revisan los requisitos de cumplimiento de los proveedores

## 5. Análisis de Riesgos

Basado en la evaluación de riesgos proporcionada en el curso:

| Categoría                      | Descripción                                                       |
|                                                                                                    |
| Puntuación de Riesgo General   |  8/10 (Alto)                                                      |
| Impacto                        |  Medio (debido al impacto desconocido en los activos)             |
| Probabilidad                   |  Alta (falta de controles + riesgo de incumplimiento)             |
| Factores Clave                 |  Falta de controles, inventario incompleto, ausencia de políticas |
                                                                                                  

El mayor riesgo se debe a:
* Falta de visibilidad de los activos
* Alta probabilidad de exposición de datos
* Alta probabilidad de sanciones regulatorias

## 6. Evaluación de Cumplimiento
Botium Toys debe cumplir con:  

### 1. PCI DSS

Dado que la empresa ***acepta pagos en línea.***
El incumplimiento de los controles PCI puede resultar en:
* Multas
* Auditorías obligatorias
* Aumento de las comisiones de los procesadores de pago

### 2. RGPD

Botium Toys vende a clientes en la **Unión Europea**, lo que implica la aplicación del RGPD.
Deficiencias actuales:  

* Ausencia de un Delegado de Protección de Datos
* Ausencia de una política de privacidad alineada con el RGPD
* Ausencia de procesos documentados de retención de datos o consentimiento  

### 3. Expectativas de Privacidad y Manejo de Datos en EE. UU.

Si bien no son específicas del sector:
* Se requieren controles de seguridad razonables
* Se aplican las leyes de notificación de violaciones de datos  

### 4. Alineación con el Marco de Seguridad de NIST

El gerente espera una alineación completa con:
* Identificar
* Proteger
* Detectar
* Responder
* Recuperar

El nivel de madurez actual es bajo.  


  


  
