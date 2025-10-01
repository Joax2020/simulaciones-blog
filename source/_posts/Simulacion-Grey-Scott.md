---
title: Modelo de Gray-Scott - Patrones Emergentes en Sistemas de Reacción-Difusión
date: 2025-09-30 15:28:00
tags: [Reacción-Difusión, Sistemas Complejos, Simulación, Patrones Emergentes]
categories: Modelos
---

# Modelo de Gray-Scott: Cuando la Simplicidad Genera Complejidad

En el estudio de sistemas dinámicos, existen modelos que demuestran cómo interacciones locales simples pueden dar lugar a patrones globales sorprendentemente complejos. Uno de los más fascinantes es el **modelo de Gray-Scott**, un sistema de reacción-difusión que genera estructuras que recuerdan a patrones biológicos naturales.

## ¿Qué son los Modelos de Reacción-Difusión?

A diferencia de modelos poblacionales tradicionales como Malthus o Verhulst, los modelos de reacción-difusión incorporan el componente espacial, permitiendo explicar la formación espontánea de patrones en la naturaleza.

Imaginen un espacio donde dos sustancias químicas interactúan:
- **Sustancia A (U)**: Se introduce constantemente en el sistema
- **Sustancia B (V)**: Se elimina progresivamente y reacciona con A

La magia ocurre cuando dos moléculas de B reaccionan con una de A, convirtiéndola en más B - un proceso **autocatalítico** que genera retroalimentación positiva.

Este componente extra permite explicar la **formación espontánea de patrones** en la naturaleza, lo que convierte al modelo de Gray-Scott en un puente entre **matemáticas, biología, física y computación**.

## El Corazón Matemático del Modelo

El sistema se describe mediante dos ecuaciones diferenciales parciales:

```python
# Ecuaciones del modelo Gray-Scott
∂U/∂t = Du·∇²U - U·V² + F·(1 - U)
∂V/∂t = Dv·∇²V + U·V² - (F + k)·V

 ```

##  Fundamentos Teóricos

###  Modelos de Reacción-Difusión
Un modelo de reacción-difusión describe cómo dos (o más) sustancias:  
- reaccionan químicamente,  
- se difunden en un espacio continuo o discreto.  

El resultado de estas interacciones es la **auto-organización**: estructuras que emergen sin necesidad de un control centralizado.

###  El Modelo de Gray-Scott
Propuesto en los años 80, el modelo de Gray-Scott fue estudiado en detalle por Pearson (1993), mostrando cómo reglas sencillas podían generar una diversidad de **patrones espaciales**: manchas, rayas, ondas, espirales.  

Se centra en dos sustancias:  

- **U (alimentada constantemente)**  
- **V (reactiva y eliminada progresivamente)** 

<video width="100%" controls>
  <source src="../videos/prueba.mp4" type="video/mp4">
  Tu navegador no soporta el elemento video.
</video>

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; margin: 2rem 0; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);"> <iframe src="https://www.youtube.com/embed/6Bv6VIKstn0" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen title="Modelo Gray-Scott - Patrones Emergentes"> </iframe> </div>

https://pmneila.github.io/jsexp/grayscott/?spm=a2ty_o01.29997173.0.0.14fec921Kw28aO