# Set de datos en los que vamos a basar el proyecto 

Todos estos datasets van a proceder de la plataforma Physionet.

## AF Classification from a Short Single Lead ECG Recording: The PhyisioNet / Computing in Cardiology Challenge 2017

Los autores de este set de datos son Gari D. Clifford, Chengyu Liu, etc. 
- Enlace al dataset: https://physionet.org/content/challenge-2017/1.0.0/

- Motivo de la elección: La recogida de los datos de ECG solo está realizada en una derivada, es decir, en una sola dirección del cuerpo, lo que hace que los datos que obtengamos sean más fáciles de tratar y de ser utilizados en el tipo de redes neuronales con las que vamos a trabajar. Por lo menos esto es aplicable a la primera parte del trabajo, si luego vemos que podemos realizar modificaciones para aumentar la complejidad podemos hacerlo utilizando el resto de datasets que vamos a plantear a continuación, aunque luego no sabemos si las vamos a utilizar o no.



### PTB - XL a large publicly available electrocardiography dataset

Los autores de este dataset son Patrick Wagner, Nils Stradthoff, etc. 

- Enlace al dataset: https://physionet.org/content/ptb-xl/1.0.3/

- Motivo de la NO elección: En este set de datos las medidas del ECG se han realizado con la derivada número 12, lo que equivale a haber tomado estas medidas en 12 direcciones distintas del cuerpo, por lo que estos datos son de una gran complejidad para nuestro proyecto y a priori no vamos a usarlo para nuestro objetivo. Esto se debe principalmente a que no es lo mismo realizar un Data Augmentation en una sola dirección o incluso en dos, en lugar de en doce de ellas. 


 
