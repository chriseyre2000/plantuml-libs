# Saopaulometro


```text
simpleicons-7/S/Saopaulometro
```

```text
include('simpleicons-7/S/Saopaulometro')
```



| Illustration | Saopaulometro |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Saopaulometro.png) | ![illustration for Saopaulometro](../../simpleicons-7/S/Saopaulometro.Local.png) |




## Saopaulometro

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Saopaulometro
include('simpleicons-7/S/Saopaulometro')

' renders the element
Saopaulometro('Saopaulometro', 'Saopaulometro', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Saopaulometro
include('simpleicons-7/S/Saopaulometro')

' renders the element
Saopaulometro('Saopaulometro', 'Saopaulometro', 'an optional tech label', 'an optional description')
@enduml
```

