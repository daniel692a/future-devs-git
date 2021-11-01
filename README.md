# Git
Primeros pasos en *git* 

## Capítulos:
1. Introducción a Git
2. Flujo de trabajo básico
3. Repositorios remotos

| Centralizado |
| ------------ |
| Se trabaja sobre una rama central (main o master) y no se hace uso de otras ramas |

###  GitFlow
Popularizado por **Vincent Driessen**, Este flujo utiliza un diseño de ramas específicas, el cual *asigna* una *función* específica a cada una de ellas.
* `develop`: Se utilizrá el `feature flow`, no se harán commits en ella, si no que crearemos otras: 
	* `feature/funcionalidad`: Nuevas características que se integrarán a `develop`
* `hotfix/funcionalidad`: Correcciones que se integran a `main` y `develop` pero después de un release.
* `release`: Se programan entregables, no se agregan funcionalidades, se arreglan errores, una vez solucionados, se integran a `main` y `develop`

### Feature Branch
**Workflow basado en ramas**, aquí no se trabajará en `master` o `main`, solo los primeros *commits* serán en `main`, después crearemos una rama para cada funcionalidad y una vez completa, se hace *merge* a la principal, permite hacer revisiones por medio de *pull request*.

Si decimos designar un servidor central tenemos opciones como:
1. GitHub
2. GitLab
3. Bitbucket
