# Procedimiento-Total-Cuentas

Dando respuesta al punto "Escribe un procedimiento almacenado para su proyecto integrador que sea útil."

Crearemos un procedimiento llamado TotalCuentas para el cual usaremos la información de las tablas cuentas y presupuesto.

![image](https://github.com/user-attachments/assets/f1e5f120-c8b1-4ee4-81ec-dac354407865)

![image](https://github.com/user-attachments/assets/664b3603-4c3d-468c-8215-e48d13fb76c1)

Para el procedimiento tendremos como parámetro de entrada la cedula de un usuario y con ella y ayuda de un JOIN conseguiremos datos como: idPresupuesto, y con estos ya podemos saber cuanto dinero tiene el usuario en cada cuenta y con la función “sum” sabremos el total del usuario.

![image](https://github.com/user-attachments/assets/24d1acbf-6b04-40eb-8bab-9d00a67eb853)

Como podemos ver en el ejemplo el usuario con cedula “1010101” tiene en total en todas sus cuentas $1.055.000 pesos.

![image](https://github.com/user-attachments/assets/defd0a34-74f9-4193-974f-5f3b887032c7)

Este es un procedimiento muy útil y utilizado en la vida real para poder unificar todo el dinero que un usuario pueda tener en diferentes cuentas, bancos y demás.




