# Iniciativa THN-COE Q3 - (2022)
.Net Core 6, Angular, Sql Server

## 01. Creación y configuración del proyecto con arquitectura en capas.

```
01. Open Visual Studio 2022
02. Create a new project
03. Blank Solution (Next → Name: CompanyServer)
04. Click derecho en la solución y añadir (Add)  "Nueva Carpeta de Solución → New Solution Folder" (Name: src)

    Click derecho en la carpeta src y ñadimos las capas:

05. Add > New Project > ASP.NET Core Web Api (C#) → (Company.API)
06. Add > New Project > Class Library (C#) → (Company.BL)
07. Add > New Project > Class Library (C#) → (Company.DAL)

    Install dependencies (Click derecho en cada capa > Mange NuGet Packages... > Browse):

08. (Company.API):
    Microsoft.EntityFrameworkCore.Design

09. (Company.DAL):
    Microsoft.EntityFrameworkCore
    Microsoft.EntityFrameworkCore.SqlServer
    Microsoft.EntityFrameworkCore.Tools

    Agregar Referencias (Click derecho en cada capa > Add > Project Reference):

10. (Company.API):
    - Company.BL
    - Company.DAL

11. (Company.BL):
    - Company.DAL
  

Hasta este punto el proyecto se encuentra configurado y se puede ejecutar, en el caso que Visual Studio solicite seleccionar el projecto de arranque realizamos los siguiente:

Click derecho en la capa: (Company.API) > Set as Startup Project

```



## 05.

![image](https://user-images.githubusercontent.com/23192401/181151719-c600f5ce-3e7e-4a60-9140-dd50f071c9c1.png)

## 06.

![image](https://user-images.githubusercontent.com/23192401/181152381-8c136387-835c-4ba7-8d9b-14155acdf1ad.png)


```

```

##

```

```
##

```

```
##

```

```
##

```

```
