
   # 🍊 TinyMind, web para gestion de planfificacion de clase, manejo de listas profesores, de listas de estudiantes y juegos de matematicas interactivos inclusivos.   


## 🥏 Tecnologias usadas 
  1. PHP (8.1) 
  2. MySQL database  
  3. Bootstrap 5
  4. JQuery, JavaScript
  5. HTML, CSS

## 💡 Funciones 
  1. manejo de listas de estudiantes
  2. manejo de listas de maestros
  3. administracion de inasistencias (maestros y estudiantes)
  4. subir resultados de examenes 
  5. soporte para subir notas
  6. incluye modulo de juegos interactivos de matematica inclusivos  
  7.permite cambio de contraseña olvidada
  8. menu principal 
  9. modulo de inicio de sesion
  10. soporte para temas oscuro
  11. uso de API a nivel estetico para mostrar el clima.
   

## 🦤 SCREENSHOTS

### Pre-View
<div style="display: flex;flex-direction: column; grid-gap: 10px;">
     <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/1.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/2.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
</div>
<br>

### Admin View
<div style="display: flex;flex-direction: column; grid-gap: 10px;">
   <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/3.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/4.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
     <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/5.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/6.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
     <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/7.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/8.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
     <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/9.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/10.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
</div>
<br>

### Teacher View
<div style="display: flex;flex-direction: column; grid-gap: 10px;">
    <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/11.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/12.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
</div>
<br>

### Student View
<div style="display: flex;flex-direction: column; grid-gap: 10px;">
   <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/13.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/14.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
    <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/15.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/16.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
    <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/20.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
    
</div>
<br>


### Owner View
<div style="display: flex;flex-direction: column; grid-gap: 10px;">
    <div style="display: flex; grid-gap: 10px;">
        <img src="screenshots/17.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
        <img src="screenshots/19.png" alt="screenshots" width="49%" style="border: 2px solid lightgreen"/>
    </div>
    
</div>
<br>

## ✅ como usar?

  <b>Pre-requirement</b> : Make sure you have both php and MySQL installed on your PC. You can also use XAMPP which provide BOTH (php + MySQL).<br><br>

 <b>Step-1 :</b> Start XAMPP <br>
   Open XAMPP Control panel and start the Apache And MySQL Server  <br>

 <b>Step-2 :</b> Create Database <br>
   <b>The schema file of the database setup is available at database/_sms.sql </b>
   <br><br>
   From you xampp open phpmyadmin by clicking on admin button in front of MySQL -> create a database with the name '_sms' -> import the  database/_sms.sql file to complete the database setup.<br>

<b>Step-3 :</b> Placement <br>
   <b> If you have xampp installed on your PC you need to place the downloaded folder on 'htdocs directory' </b>
   <br><br>
   Copy the downloaded folder and place it into htdocs folder. Located at <i>C:\xampp\htdocs/app</i>
   <br><br>
   make sure your directory setup is like : <i>C:\xampp\htdocs\app\ </i> : and index.php file is available on the that location

<b>Step-4 :</b> Run the application <br>
   <b> visit on the url : <i>http://localhost/app</i> </b>
   <br> Visit to the given URL to see the running website

## 🔐 correos y contraseñas

The project comes with default user on each panel you can remove and update them also.<br>
The **Credentials** for default logins are

| Panel   |  Email             | Password |
| ----:   |  :---------------- | :------: |
| Admin   | javier@gmail.com   | 123      |


- Note : **Password for New Teachers and Students:**  
   The default password for newly created teacher and student accounts is set to their **date of birth**.  
   - Example: If the date of birth is **12 July 2000**, the password would be **12072000**.








