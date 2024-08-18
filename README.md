# CVDS Laboratorio 01

## **Integrantes**

- Sergio Andrés Bejarano Rodríguez
- Laura Daniela Rodríguez Sánchez

## **Link repositorios git**

- https://github.com/LauraRo166/CVDS_lab01.git
- https://github.com/SergioBejarano/Laboratory-01-CVDS.git

## **Respuestas Parte I**

### **git add**

El comando git add se utiliza para agregar cambios en los archivos del directorio de trabajo al área de preparación de Git. Es decir que se preparan los archivos que se han modificado, creado o eliminado para el próximo commit. Se usa escribiendo tanto el nombre del archivo que se desea agregar después del comando tanto como '.' para agregar todos los archivos modificados.

### **git commit -m "mensaje"**

El comando git commit -m "mensaje" guarda los cambios registrado en el área de preparación en el repositorio con un mensaje que describe los cambios realizados. Este mensaje sirve como un historial de commits.

_Laura Rodríguez_

## **Parte II**

Se invitó al colaborador a formar parte del repositorio (CVDS_lab01)

![alt text](image.png)

Al realizar cambios e intentar realizar push al mismo tiempo no se permitió el mismo para uno de los desarrolladores.

![alt text](<Screenshot 2024-08-17 120913.png>)

Por lo que se realizó pull y se resolvieron manualmente los conflictos.

![alt text](image-1.png)

Se creó un nuevo conflicto para resolver en IntelliJ:

![img_1.png](img_1.png)

![img_2.png](img_2.png)

![img_3.png](img_3.png)

![img_4.png](img_4.png)

## **Respuestas Parte III**

**1.** _¿Hay una mejor forma de trabajar con git para no tener conflictos?_

Implementar prácticas como frecuentes pulls, pequeños commits y usar Git Flow ayuda a minimizar conflictos y a mejorar la forma de trabajar en Git.
Git Flow organiza el desarrollo en ramas específicas, lo que facilita la resolución de conflictos al mantener cambios aislados y organizados.

**2.** _¿Qué es y como funciona el Pull Request?_

Es una funcionalidad de github (en gitlab llamada merge request y en bitbucket push request), en la que un colaborador pide que revisen sus cambios antes de hacer merge a una rama, normalmente master. Al hacer pull request se genera una conversación que pueden seguir los demás usuarios del repositorio, así como autorizar y rechazar los cambios.

### Nuevas ramas

La rama correspondiente a Laura Rodríguez es feature/laura.

Y la rama correspondiente a Sergio Bejarano es feature/sergio.

![img.png](img.png)

### Pull Request

Se realizaron dos pull request.

![img_5.png](img_5.png)

## **Referencias**


- *https://itdo.com/blog/guia-de-git-para-principiantes/*
- *https://www.atlassian.com/es/git/glossary#commands*