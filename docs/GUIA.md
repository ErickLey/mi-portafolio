# Guia del Laboratorio 03: Trabajo Colaborativo

Documentacion detallada sobre como trabajar en equipo utilizando ramas, Pull Requests y resolucion de conflictos en GitHub.

## Configuracion e instalacion

Para trabajar de forma colaborativa sin afectar la rama principal, es indispensable contar con el entorno adecuado configurado en tu equipo.

- Tener instalado **Git** en el sistema local
- Contar con una cuenta activa en **GitHub**
- Editor de codigo recomendado: *Visual Studio Code*

## Pasos para colaborar en un proyecto

1. Clonar el repositorio remoto en la computadora local
2. Crear una nueva rama (*branch*) para trabajar de forma aislada
3. Confirmar los cambios localmente y subirlos a GitHub
4. Abrir un **Pull Request** para revisar los cambios e integrarlos a `main`

## Comandos indispensables de Git

| Comando | Descripcion | Uso habitual |
| --- | --- | --- |
| `git checkout -b` | Crea y cambia a una nueva rama | Iniciar una tarea |
| `git pull` | Descarga e integra cambios remotos | Sincronizar trabajo |
| `git merge` | Fusiona una rama con la actual | Unir funcionalidades |
| `git status` | Muestra el estado del entorno de trabajo | Verificar cambios |

## Codigo de ejemplo para ramas

```bash
git checkout -b feature/colaboracion
git add .
git commit -m "Agrega cambios en la rama de trabajo"
git push origin feature/colaboracion
```
## Recursos utiles

- [Guia oficial de trabajo en equipo en GitHub](https://docs.github.com/es/pull-requests)

![Trabajo en equipo con github](../img/gitHub.png)