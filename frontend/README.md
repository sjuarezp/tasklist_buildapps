
# Guía completa:
https://github.com/sjuarezp/tasklist_buildapps.git




# 2. Frontend


## 2.1. Crear Applicación Frontend

1. Click en "Aplicación web y movil"
![SJP APP](/data/img/Frontend/1_CrearApp/1.png)

2. Completar los datos de nuestro proyecto, en este caso ponemos el nombre: "tasklist_frontend_000" reemplazar el correlativo por el asignado a usted.
![SJP APP](/data/img/Frontend/1_CrearApp/2.png)

3. Deberíamos tener la siguiente pantalla como resultado:
![SJP APP](/data/img/Frontend/1_CrearApp/4.png)



## 2.2. Habilitar Acceso al Back-end


1. Click en la pestaña "Data"
![SJP APP](/data/img/Frontend/2_HabilitarData/1.png)

2. Click en "Add Integration": 
![SJP APP](/data/img/Frontend/2_HabilitarData/2.png)


3. Vamos a habilitar las funciones visuales cloud para lo cual damos click en "CLOUD FUNCTIONS" de nuestro proyecto backend:
![SJP APP](/data/img/Frontend/2_HabilitarData/3.png)


4. Seleccionamos nuestro backend:
![SJP APP](/data/img/Frontend/2_HabilitarData/4.png)


5. Esta es la pantalla que deberíamos visualizar:
![SJP APP](/data/img/Frontend/2_HabilitarData/5.png)


6. Click en "Install Integration":
![SJP APP](/data/img/Frontend/2_HabilitarData/6.png)


7. Click en "Enable Data Entity"
![SJP APP](/data/img/Frontend/2_HabilitarData/8.png)

8. Guardamos los cambios
![SJP APP](/data/img/Frontend/2_HabilitarData/10.png)


9. Click en "Browse Data" para crear un registro de prueba:
![SJP APP](/data/img/Frontend/2_HabilitarData/12.png)


10. Creamos un registro dando click en "NEW RECORD"
![SJP APP](/data/img/Frontend/2_HabilitarData/14.png)


11. Completamos los datos del formulario según la imagen:
![SJP APP](/data/img/Frontend/2_HabilitarData/16.png)

12. Deberíamos ver el registro guardado correctamente:
![SJP APP](/data/img/Frontend/2_HabilitarData/18.png)

4. Salimos del Browser de Datos
![SJP APP](/data/img/Frontend/2_HabilitarData/19.png)







## 2.3. Pantalla de listado de tareas

1. Click en "UI CANVAS"
![SJP APP](/data/img/Frontend/3_ListarTareasUI/1.png)


2. Así debería verse nuestra pantalla para poder empezar:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/2.png)


3. Click en "Headline" para modifiucarlo:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/4.png)

4. Escribimos "Tasklist":
![SJP APP](/data/img/Frontend/3_ListarTareasUI/5.png)

5. Ponemos como subtitulo: "Seguimiento de tareas":
![SJP APP](/data/img/Frontend/3_ListarTareasUI/6.png)

6. Seleccionamos List Item:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/7.png)

7. Arrastramos y soltamos debajo del subtítulo hasta que nos quede de la siguiente manera:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/8.png)

![SJP APP](/data/img/Frontend/3_ListarTareasUI/10.png)


8. Ahora editamos las variables a usar en la app:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/11.png)

9. Vamos al tab "DATA VARIABLES" y creamos una variable de datos:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/12.png)

10. Deberíamos encontrar una variable de datos llamada "Tarea" como la entidad de nuestro backend (Si no la encontramos es que no hemos realizado algúno de los pasos anteriores o en el back-end de manera correcta) damos click para seleccionar:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/13.png)

11. Seleccionamos la variable y os adeguramos que esté seleccionado como colección de datos, ya que a través de esta variable vamos a leer datos de la entidad:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/14.png)


12. Regresamos a la vista de edición:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/15.png)

13. Seleccionamos la lista creada y damos click en "Repeat with":
![SJP APP](/data/img/Frontend/3_ListarTareasUI/16.png)

14. Seleccionamos como data de iteación "Data and Variables":
![SJP APP](/data/img/Frontend/3_ListarTareasUI/17.png)


15. Seleccionamos las variables de datos:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/18.png)

16. Seleccionamos la variable de datos "Tarea1":
![SJP APP](/data/img/Frontend/3_ListarTareasUI/19.png)

17. Click en "Save" para guardar los cambios hasta el momento:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/20.png)

18. Ahora seleccionamos el primer registro y le asignamos un campo de la entidad que deseamos mostrar:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/21.png)

19. Seleccionamos como data a asignar a los datos que se van a iterar sobre ese control:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/22.png)


20. Seleccionamos la repetición actual y luego el campo título:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/23.png)
![SJP APP](/data/img/Frontend/3_ListarTareasUI/24.png)

21. Guardamos cambios:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/25.png)

22. Cambiamos también el campo secundario para poner la fecha:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/26.png)

![SJP APP](/data/img/Frontend/3_ListarTareasUI/27.png)

![SJP APP](/data/img/Frontend/3_ListarTareasUI/28.png)

![SJP APP](/data/img/Frontend/3_ListarTareasUI/29.png)

![SJP APP](/data/img/Frontend/3_ListarTareasUI/30.png)

23. Seleccionamos como data de iteación "Data and Variables":
![SJP APP](/data/img/Frontend/3_ListarTareasUI/31.png)


24. Así debería quedar nuestra pantalla:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/32.png)


25. Seleccionamos el fondo del lienzo para configurar los datos de esta página:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/33.png)

26. Guardamos cambios:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/34.png)

27. Vamos al tab de navegación:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/35.png)


28. Configuiramos el nombre de la opción del menú de navegación:
![SJP APP](/data/img/Frontend/3_ListarTareasUI/36.png)




## 2.4. Pantalla de creación de tareas

1. Navegamos a la pestala "UI Canvas":
![SJP APP](/data/img/Frontend/4_CrearTareaUI/1.png)

2. Click al el nombre de la pantalla actual:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/2.png)


3. Click en "add New Page":
![SJP APP](/data/img/Frontend/4_CrearTareaUI/3.png)

4. Completamos el formulario":
![SJP APP](/data/img/Frontend/4_CrearTareaUI/4.png)

5. Esta es la pantalla por default que deberíamos tener:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/5.png)

6. Iniciamos cambiando de nombre los títulos:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/6.png)

7. Borramos el subtítulo:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/7.png)


8. Agregamos los campos a nuestra página tal como muestran las pantallas:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/8.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/9.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/10.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/11.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/12.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/13.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/14.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/15.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/16.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/17.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/18.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/19.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/20.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/21.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/22.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/23.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/24.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/25.png)


9. Realizamos la creación de variables:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/26.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/28.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/29.png)

10. Esta vez nos aseguramos que la variable sea de tipo "New data record":
![SJP APP](/data/img/Frontend/4_CrearTareaUI/30.png)

11. Regresamos al lienzo:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/31.png)

12. Asignamos variable a los campos:
![SJP APP](/data/img/Frontend/4_CrearTareaUI/32.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/33.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/34.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/35.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/36.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/37.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/38.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/39.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/40.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/41.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/42.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/43.png)


![SJP APP](/data/img/Frontend/4_CrearTareaUI/46.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/47.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/48.png)




13. Seleccionamos "Data Variable" y asignamos la fecha y damos click en "Guardar":
![SJP APP](/data/img/Frontend/4_CrearTareaUI/49.png)
![SJP APP](/data/img/Frontend/4_CrearTareaUI/50.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/51.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/52.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/53.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/54.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/55.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/56.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/57.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/58.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/59.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/60.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/61.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/62.png)

14. Así debería quedar nuestro formulario
![SJP APP](/data/img/Frontend/4_CrearTareaUI/63.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/64.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/65.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/66.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/67.png)



![SJP APP](/data/img/Frontend/4_CrearTareaUI/71.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/72.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/73.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/74.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/75.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/76.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/77.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/78.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/79.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/80.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/81.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/82.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/83.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/84.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/85.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/86.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/87.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/88.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/89.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/90.png)

![SJP APP](/data/img/Frontend/4_CrearTareaUI/91.png)





