Construye una lista que contenga tramos horarios, en intervalos de 30 min. 
Que empiece a las 8 am y termine a las 8pm. O sea un cuadro con un bloque 
que empiece a las 8, luego 8.30, 9, 9 30.. así hasta las 8pm. La empresa 
tiene disponibilidad de 8 motociclistas cada 30 min. Cuando alguien haga 
click sobre una de estas cajitas debería tomar un recurso de motociclista. 
O sea un contador que empiece en 8 y luego baje a 7, a demás de marcar la 
caja en verde. Si el mismo usuario da click en la misma caja, debe liberar 
el recurso, si se encontraba en verde, debe liberar el recurso, o sea el 
contador nuevamente pasa de 7 a 8. Si otros usuarios han tomado a todos 
los motociclistas, la caja debe aparecer en color rojo y no me debe dejar 
tomar ese horario.
 


-detalle: agregar un link al login si el email ya es usado, cambiar pequeños texto, flecha para ir para atras ✅
-sistema de confirmacion de registro ✅
-error de email confirmated y confirmar contraseña en sing up ✅
-feekback de vista registro✅
-redireccion programatica, bloquear urls✅
-recuperar constraseña✅
-crear base de datos inicial y mostrar el valor de cada motociclista en cada caja✅
-mostrar info del usuario junto a botton de eliminar cuenta✅
-caja roja cuando no haya motociclistas disponibles✅
-aumentar y disminuir la cantidad de motociclistas de la base de datos✅
-pantalla de carga de milisegundos para evitar que se vea la redireccion y la carga de la cantidad de motociclistas
-firebase functions: eliminar un usuario luego de 30 dias - eliminar delivery dryver taking
-si hay una cuenta con sesion iniciada y accedo con un link de verificacion la app se queda iniciado con la cuenta anterior
-accessibility
-restablecer contraseña is not working
-styling feedback, texto celeste
-puedo entrar a registration con el link?



//push(): añade un alemento al final del arreglo
//unshift(): añade un elemento al inicio del arreglo
//pop(): eliminar el ultimo elemento
//shift(): elimina el primer elemento
//slice(): hace una copia exacta del arreglo sin modificar el original [] === copia[] //returns false
//const ensaladaCloned = [...ensalada]; tambien crea una copi exacta operador spread
//Array.isArray([]) //returns true
//let [tomate, hongo, zanahoria] = ['?', '?', '?'];
//fruits[4][2]; // returns '?':arreglo anidados
//let [,,,,[,,zanahoria]] = ['?', '?', '?', '?', ['?', '?', '?']]; lo mismo que lo pasado
//const emotionalVeggies = [...emotion, ...veggies]; combinar arreglos
//array.concat(arr1, arr2,..,..,..,arrN); cmbinar varios arreglos
//join(,): une los elementos de un arreglo, regresa una cadena 
//fill(): cambia lo elementos que yo selecciono
//includes(): false o true , si encuentra una coincidencia en le arreglo
//indexOf(): indice de un elemento
//reverse()
//sort(): convierte los elementos a cadenad e texto y luego los ordena segun UTF-16
//filter(): crea un nuevo arreglo , con los que cumplan la condicion indicada
//map()