# Version del Curso
Version Actual: v1.2.2

# Cabeceras
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera 5
###### CabeceraH6

# Underlines
Underline1
----------

Underline2
==========

# Formatos de enfasis
- formato *Italica* de la primera forma.
- formato _Italica_ de la Segunda forma.
-formato **bold o strong**  de la primera forma.
-formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~ de la unica forma.
- aqui podemos usar formato *italico*, pero tambien **bold** y ~~tachdo~~



# listas
## lista ordenada
1. esto es un item
1. esto es un item
1. esto es un item
1. esto es un item
1. esto es un item
1. esto es un item

# listas des ordenadas
 - lista Desordenada
 - lista Desordenada
 - lista Desordenada
 - lista Desordenada
 - lista Desordenada
 - lista Desordenada

 # links
 
 - <a href="http://google.com">Google Pages Html</a>
 - [Google Pages MarkDwon](http://www.google.com)
 - [Google Pages MarkDwon al index](index.html)
 # 



# Imagenes
![Logo GitHub](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ6YbjP5vT1VgTVr0p2ChwgAtmXZiiF0JuWCKDnEYgcNDqndVkF)

#

# Code Snipperts
#### Codigo en JSON
```JSON
// Storing data:
myObj = {name: "John", age: 31, city: "New York"};
myJSON = JSON.stringify(myObj);
localStorage.setItem("testJSON", myJSON);

// Retrieving data:
text = localStorage.getItem("testJSON");
obj = JSON.parse(text);
document.getElementById("demo").innerHTML = obj.name;
```


#### Codigo en JavaScript
```javascript
class Car {
  constructor(brand) {
    this.carname = brand;
  }
  present() {
    return "I have a " + this.carname;
  }
}

mycar = new Car("Ford");
document.getElementById("demo").innerHTML = mycar.present();
```


# Tablas
| Nombre    | Apellido    | Documento |
|--------   |---------    | --------- |
| Maxi      | Burgos      | 01023252  |
| kinberling | Millers    | Sdd252563 |

# 

# Citas
### Esto es un texto referente a una cita que pondremos debajo.
> esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.

> esto es otra cita.

# 


# Lineas Divisoras..
Esto es un texto que sera dividido por una linea Divisora por guiones medios, 

---
esto es otro texto dividido. por guiones medios,

Esto es un texto que sera dividido por una linea Divisora por asteriscos

***
esto es otro texto dividido. under Lines

___




# Saltos de Lineas

Esto es nuestro Primer Parrafo.

Esto es nuestro Segundo Parrafo.

Esto es nuestro Segundo Parrafo.

- Lista