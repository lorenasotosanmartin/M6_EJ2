# Ejercicio Práctico: Almacenamiento y Análisis de PWA en la Web del Hospital
## Descripción 
En este proyecto se configuran y utilizan opciones de almacenamiento web dentro de la web del hospital convertida en PWA.

### Despliegue y Configuración del Service Worker Personalizado
Se implementa un servive worker básico, el cual permite que la aplicación funcione en modo offline, ademas, realice precaching de los archivos principales y se verifica que este se encuentra registrado y activado correctamente.
### Pruebas de Rendimiento con Lighthouse
Mediantes las herramientas de desarrollador proporcionadas por Chrome se comprueba el funcionamiento de la aplicacion en modalidad offline, y se realiza un informe mediante la aplicacion Ligthouse, respecto a la version desktop de la aplicación donde los parametros evaluados arrogan en su mayoria una puntuacion superior a 80, tal como se aprecia en la siguiente imagen, donde se aprecian los resultados del informe: 
![image](https://github.com/user-attachments/assets/33557a5a-0dde-44fa-9779-e5ee6aa8d1fd)

### Visualización del proyecto
Para visualizar este proyecto se necesita que previamente cuentes con la instalación de:
- **Git**: [sitio de descarga] (https://git-scm.com/downloads)
- **Node.js**: [sitio de descarga] (https://nodejs.org/en/download/package-manager)
- **Visual Studio Code**: [sitio de descarga] (https://code.visualstudio.com/download)
  
Una vez que ya cuentes con lo descrito anteriormente, debes clonar este repositorio en una carpeta local, mediante el siguiente comando:
```bash
git clone https://github.com/lorenasotosanmartin/M6_EJ2.git
```
cuando ya este clonado, escribir el siguiente comando en la consola: 
```bash
npm  i
```
y ejecutar el comando, para inicializar el proyecto: 
```bash
npm run dev
```
Finalmente, para visualizar el proyecto en tu navegador debes abrir la url http://localhost:5173/
