

**Repositorio Javascript Dos**

Temas como estructuras de datos.
> *Todo autodidacta.*

```javascript
/* console.log("Bienvenidos a estructuras de datos");
 */

//ARRAYS

let listaCompra = ["pan","leche","fruta","pescado"];
//let si creo que se va a modificar
//const se va a mantener constante

let cantidades = [3,10,5,2]

let registroEntradas = [true,true,false,false]

//OBJETOS
/* let cliente = {
    nombre: "Hipermarket",
    direccion:"LA HABAS",
    ciudad: "MarketCity",
    factura: 2300,
    facturasPendientes: true
} */

//COMBINACIONES

//ARREGLO DE OBJETOS

let arreglo = [{},{},{}]


//came1Case
const topTresJugadoresTenis =[{
    //key:value
    ranking:1,
    nombre:"Ivan",
    puntos:1160,
    pais:"Serbia"
},{
     //key:value
     ranking:2,
     nombre:"Jose",
     puntos:9999,
     pais:"España"
},{
     //key:value
     ranking:1,
     nombre:"Thiem",
     puntos:4444,
     pais:"Austria"
}]

//OBJETO CON ARREGLOS

let Djokovic = {
    ranking:1,
    edad:33,
    puntos:1223,
    pais:"Serbia",
    GrandSlams: 17,
    Activo:true,
    EstaTemporada: ["Cincinati","Rome","Dubai"],
    estaTemporada:{
        wins: ["Australian Open", "Cincinati", "Rome"],
    },
    nickName:["Nole","Djokovic"]
}

//ACCESOS EN ARRAYS

const empleados = ["Jose Perez","Pepe Jimeno", "Sasuke Uchiha", "Maria Flores"];

console.log(empleados[0]);

const empleadosGenero = [["Maria","Pepa"],["Jose","Juan"]];

console.log(empleadosGenero[1][0])

//ACCESOS EN OBJETOS

let cliente = {
    nombre: "Hipermarket",
    direccion:"LA HABAS",
    ciudad: "MarketCity",
    factura: 2300,
    facturasPendientes: true,
    transportistas: ["Jose Perez","Maria Sanchez","Juan Martinez","Papa Jimeno"],
}

console.log(cliente.transportistas[2])

```


### End
