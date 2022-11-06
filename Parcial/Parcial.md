# Parcial Practico
## Testing
* Se forma el Test para revisar la consulta por id
![Imgur](https://i.imgur.com/6pfVEYg.png)
## Implementación de Historias de Usuario
* Primero en el PacienteMapper se construye la consulta 	necesaria de acuerdo a los criterios de aceptación
![Imgur](https://i.imgur.com/7zeUm1d.png)
![Imgur](https://i.imgur.com/yxoTLIT.png)
![Imgur](https://i.imgur.com/EhtLrAL.png)
* Se construye la interfaz asignada al mapper de Consultas
![Imgur](https://i.imgur.com/iWyxLpL.png)
* Se hace la implementacion de los metodos que implementamos en el mapper, ademas de ponerle a la clase pacienteBean como heriencia de BasePageBean que es serializable, ademas de inyectar la interfaz de ServiciosPaciente y poner propiedades adicionales para el funcionamiento
![Imgur](https://i.imgur.com/07sjC7f.png)
![Imgur](https://i.imgur.com/lmXpfCI.png)
![Imgur](https://i.imgur.com/PDDkJ3B.png)
* Se hace la implementacion de la función en la clase MyBatisDAOPaciente
![Imgur](https://i.imgur.com/WviPyGp.png)
* En el web.xml se relaciona la ruta del listener que se le asignara al proyecto
![Imgur](https://i.imgur.com/lCulYp5.png)
* Se construye el .xhtml que va a ser el encargado del fronted de mostrar la interfaz para hacer la consulta correspondiente
![Imgur](https://i.imgur.com/VQVM1Lk.png)
![Imgur](https://i.imgur.com/Kv8PHJ9.png)
![Imgur](https://i.imgur.com/zIJZQfE.png)
![Imgur](https://i.imgur.com/zseFv5e.png)


