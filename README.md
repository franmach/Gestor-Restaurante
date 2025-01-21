# Gestor de Restaurantes

El Gestor de Restaurantes es una aplicación web diseñada para la administración eficiente de una cadena de restaurantes temáticos. Este sistema permite gestionar reservas, menús, mesas y usuarios, integrando descuentos basados en condiciones climáticas y tipos de clientes.

---

## Tabla de Contenidos
1. [Descripción General](#descripción-general)
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)
3. [Características](#características)
4. [Instalación](#instalación)
5. [Uso](#uso)
6. [Capturas de Pantalla](#capturas-de-pantalla)
7. [Contribuciones](#contribuciones)
8. [Contacto](#contacto)

---

## Descripción General
Este proyecto fue desarrollado como parte de la asignatura **Programación III** y tiene como objetivo ofrecer una solución integral para la gestión de operaciones en restaurantes. Además, incluye características innovadoras como la aplicación de descuentos según el clima y el tipo de cliente, utilizando APIs externas para obtener datos en tiempo real.

---

## Tecnologías Utilizadas
- **Lenguajes:** C#, JavaScript, HTML, CSS.
- **Frameworks:** ASP.NET Core MVC.
- **Bases de Datos:** SQL Server con Entity Framework.
- **APIs:** OpenWeatherMap, CurrencyLayer.

---

## Características
- **Gestión de reservas:** Registro y administración de reservas por cliente y mesa.
- **Descuentos dinámicos:** Basados en las condiciones climáticas y el tipo de cliente (Nuevo, Frecuente, VIP).
- **Roles y usuarios:** Control de acceso basado en roles para personal administrativo y usuarios generales.
- **Integración con APIs externas:** Datos climáticos y cotizaciones monetarias en tiempo real.
- **Interfaz intuitiva:** Diseño interactivo para una experiencia de usuario fluida.

---

## Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/gestor-restaurantes.git
   ```
2. Configura la base de datos en SQL Server:
   - Crea una base de datos con el nombre `gestor_restaurantes`.
   - Actualiza el archivo `appsettings.json` con tus credenciales de base de datos.

3. Ejecuta la aplicación:
   ```bash
   dotnet run
   ```

4. Abre el navegador y accede a `http://localhost:5000`.

---

## Uso
- **Administradores:** Gestiona reservas, menús y clientes desde un panel dedicado.
- **Clientes:** Consulta el menú, realiza reservas y aprovecha los descuentos aplicados automáticamente.

---

## Capturas de Pantalla
![image](https://github.com/user-attachments/assets/c45370ac-f54a-4209-9ccd-d5b79de3975b)
![image](https://github.com/user-attachments/assets/cb627c62-955d-4cc2-a558-a078f529e4ec)
![image](https://github.com/user-attachments/assets/05c73a1e-63a6-4dcb-91e7-31b2ff485926)
![image](https://github.com/user-attachments/assets/f993e96c-eaa8-4822-a28e-9955e9861280)
![image](https://github.com/user-attachments/assets/f5e415cf-b2f6-4e7c-9671-0e213da73708)
![image](https://github.com/user-attachments/assets/a9e7504b-25bc-416c-9e15-db6a58843f4c)

---

## Contribuciones
Este proyecto fue desarrollado como parte de un curso académico y no está abierto a contribuciones externas.

---

## Contacto
Para más información, contacta a Francisco Machado en [franmach20@outlook.com](mailto:franmach20@outlook.com).
