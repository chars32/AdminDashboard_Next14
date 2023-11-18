# Admin Dashboard

Notas de el proyecto del Admin Dashboard panel de el video de el canal de [Lama Dev](https://www.youtube.com/watch?v=cBg6xA5C60s&list=PL86ZeyU83RP_PLIppbtGTza0Y2J1g7fNX&index=6&t=342s)

## Inicio del proyecto

* Iniciamos el proyecto creando un fork de el [repositorio](https://github.com/safak/nextadmin/tree/starter) del proyecto.

* En mi caso el fork tendra como nombre **AdminDashboard_Next14** y esta en mi cuenta de [github](https://github.com/chars32/AdminDashboard_Next14)

* En caso de que queramos iniciar un proyecto nuevo, con la ultima version de Nextjs, en este caso la ultima version es la 14, podemos hacerlo con la siguiente sintaxis:
`npx create-next-app@latest`. Ojo `latest` nos instala la ultima version ded Nextjs

* Instalamos las librerias con el comando `npm i`

* Corremos el comando `npm run dev` y debería funcionar en el navegador en la url **localhost:300**

## Estructura inicial de carpetas

* Este proyecto se compondra de dos pantallas o paginas las cuales seran **Login** y **Dashboard**.

* Creamos la estructura inicial de carpetas para las pantallas de el proyecto.

## Navbar y Sidebar

* Debido a que los componentes **Navbar** y **Sidebar** solo serán utilizados en el componente **Dashboard**, podemos agruparlos en una carpeta aparte llamada ***ui** la cual contendra todos los compenentes especificos para un componente general. En este caso creamos dos carpetas **dashboard** y **login** las cuales contendran los componentes especificos que contendran los componentes generales con los mismos nombres.

* **Componente dashboard**

  * Creamos un componente **layout.jsx** el cual sera el layout el cual afectara a todo ese componente **dahsboard**. Esto se logra al pasarle como parametro el **children**.
  * Creamos dos componentes nuevos **products** y **users**

* **Componente ui**

  * Dentro de este componente agregamos el archivo **global.css**

* **global.css**
  
  * Declaramos los estilos globales.
