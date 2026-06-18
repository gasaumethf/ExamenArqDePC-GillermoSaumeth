# ExamenArqDePC-GillermoSaumeth

## Objetivo
Desplegar y eliminar una instancia EC2 en AWS usando CloudFormation y GitHub Actions.

## Tecnologías utilizadas
- AWS CloudFormation
- AWS EC2
- GitHub Actions
- Git Flow

## Funcionalidad de Deploy
El workflow `deploy.yml` se ejecuta manualmente desde GitHub Actions. Valida el template y despliega el stack con la EC2 y Security Group.

## Funcionalidad de Destroy
El workflow `destroy.yml` elimina completamente el stack de CloudFormation y todos sus recursos.

## Objetivo del template EC2
Lanzar una instancia Amazon Linux con Apache instalado via UserData, sirviendo una página web con los datos del estudiante.