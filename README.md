---

## Universidad de Costa Rica
### Escuela de Ingeniería Eléctrica
#### IE0405 - Modelos Probabilísticos de Señales y Sistemas

Segundo semestre del 2020

---

* Estudiante: **Heiner Mauricio Obando Vega**
* Carné: **B55130**
* Grupo: **1**

---
# `P4` - *Modulación digital IQ*

---
## 4. - Asignaciones del proyecto

### 4.1. - Modulación QPSK

* (50%) Realice una simulación del sistema de comunicaciones como en la sección 3.2., pero utilizando una modulación QPSK en lugar de una modulación BPSK. Deben mostrarse las imágenes enviadas y recuperadas y las formas de onda.

En este punto se trabajó con diferentes funciones que permitieron la simulación de la transmisión de imagenenes, utilizando una modulación QPSK, en base al código brindado por el profesor se modificaron algunas funciones para lograr realizar esta funcion. La primera función en ser cambiada fue la función de modulador, esta función permitió que se crearan dos señales portadoras que transmitieran una imagen al sumarse en una sola señal modulada, luego de esto se modificó la función demodulación para que recibiera la señal modulada sometida a un ruido, así como las portadoras, para que de esta manera esta señal "recibida" reacomodora los bits en una sola señal de nuevo en el orden que fueron tomados en la etapa de modulación, y así, estos bits se convirtieran de nuevo en pixeles, y se simulara imagen la imagen recibida por el receptor.

Se puede observar el comportamiento de las señales dadas en la siguiente imagen, siendo la primera, la señal modulada, la segunda representa la señal modulada cuando fue sometida a ruido y la tercera representa la señal demodulada.

![Imgur](https://i.imgur.com/XapifxV.png)
