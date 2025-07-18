# Digital Ars - Billetera Virtual

Digital Ars es una billetera virtual desarrollada como proyecto grupal final para el curso de aceleracion de la rama .NET/React, realizado por [CITIA](https://www.citialapampa.ar/) con colaboracion de [Alkemy](https://www.alkemy.org/).  

Las tecnologias que usa son:
* Backend
  * DotNet 7
  * Entity Framework
* Frontend:
  * React.js
  * Vite  
* Documentacion API:
  * Swagger
* Seguridad:
  * JWT
  
Cosas que puede realizar:  
- [x] Iniciar Sesion
- [x] Registrar Usuario
- [x] Transferir Dinero Entre Usuarios
- [x] Ver Historial de Transferencias
- [x] Menu de Administrador
- [x] Modificar Usuarios/Cuentas como Administrador
- [ ] Depositar y Retirar Dinero
>[!NOTE]
>El programa no permite transferencias con dinero real, ya que fue echo como practica y para la entrega final, y no se espera darle uso para un banco real

---

# Como Usar el Programa
1. Baja los archivos del repositorio, y guardalos todos en una misma carpeta
2. Abre la carpeta con Visual Studio Code
3. Abre 2 pestañas de la terminal, una ubicada en .\React_DigitalArs\ReactDigitalArs y la otra en API_DigitalArs\ApiDigitalArs>  
![Terminales](https://i.imgur.com/3KF1wdZ.png)
4. En la terminal ubicada en ApiDigitalArs, ejecute el comando < dotnet run dev > (mantenga esta terminal abierta)
    - Si quieres revisar que funciona bien, abra el localhost indicado por la terminal, y agregue /swagger a la url (ejemplo: https://localhost:5201/swagger)
   ![Swagger](https://i.imgur.com/8DthiVf.png)
5. En la terminal ubicada en ReactDigitalArs, ejecute el comando < npm run dev > (asegurse de haber realizado el paso 4 antes)
6. Abra el localhost indicado por la terminal, y deberia aparecerle la pagina inicial del programa
![PaginaInicio](https://i.imgur.com/gYIVqog.png)
7. Desde aca podes iniciar sesion o registrar un usuario
  - Ejemplos Inicios de Sesion:
    - Administrador:
      - Correo: fausto@gmail.com
      - Contraseña: perez
    - Usuario:
      - Correo: hebe@gmail.com
      - Contraseña: gomez
>[!IMPORTANT]
>Estos correos solo existen dentro del programa para el inicio de sesion y no son correos reales

---

# Creditos
* [Fausto Leonel Perez Russo](https://www.linkedin.com/in/fausto-leonel-perez-russo-771b64280/) -- Desarrollo Backend y Frontend, Diseño del DER
* [Hebe Gómez](https://www.linkedin.com/in/hebe-gomez/) -- Desarrollo Backend y Frontend, diseño del logo
* [Ignacio Casteran](https://www.linkedin.com/in/ignacio-casteran/) -- Estructura Inicial del Frontend, Diseño del DER, Informe SQL
* Nicolas Herrera -- Colaboracion en la presentacion del proyecto
