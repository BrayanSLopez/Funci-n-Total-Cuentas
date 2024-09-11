# Funcion-Total-Cuentas

Se crea una función llamada "TotalCuentas", el cual contara como parametro de entrada el numero de cedula de un usuario ya registrado
![image](https://github.com/user-attachments/assets/e1803542-76ab-4bd5-a017-81300da2e55a)
Se declararan dos variables las cuales seran "NumCe" donde guardaremos el numero de cedula ingresado como parametro y la segunda variable sera "NumId" en la cual guardaremos el numero IdPresupuesto correspondiente a esa cedula.
Este IdPresupuesto lo traeremos de la tabla presupuesto usando un Select JOIN donde usaremos como llave foranea presupuesto.cedula con Numce.
![image](https://github.com/user-attachments/assets/e6360813-c4be-4ab4-a1f0-bb52cbf1e40f)
Seguidamente comop desarrollo de la funcion usaremos la sentencia "sum" para para sumar el total del contendio de las cuentas correspondiente a un IdPresupuesto el cual anteriormente le asignamos a la valiable NumId con el numero de cedula, la llave foranea que se utilizara sera cuentas.IdPresupuesto con NumId.
Las tablas utilizadas fueron: 
- Cuentas
![image](https://github.com/user-attachments/assets/60b264d3-cc61-4dfa-8940-41a8bc64c5ea)
- Presupuesto
![image](https://github.com/user-attachments/assets/5598f876-b9e1-4f14-af66-f5ff08c0af12)
Como apreciamos el resultado corresponde a la suma del contenido de las cuentas del idPresupuesto que corresponde al numero de cedula asociado.
![image](https://github.com/user-attachments/assets/02240425-b167-4e06-91da-1c315d0a44ca)

La operatividad de esta función es que el usuario podra vizualizar el total de dinero que tiene en las diferentes cuentas unicamente con su numero de cedula, algo muy utilizado en la vida real.

![image](https://github.com/user-attachments/assets/07d26457-c3f7-40d3-9bd8-3f699943def6)
