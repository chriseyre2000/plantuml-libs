# Supermicro


```text
simpleicons-7/S/Supermicro
```

```text
include('simpleicons-7/S/Supermicro')
```



| Illustration | Supermicro |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Supermicro.png) | ![illustration for Supermicro](../../simpleicons-7/S/Supermicro.Local.png) |




## Supermicro

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Supermicro
include('simpleicons-7/S/Supermicro')

' renders the element
Supermicro('Supermicro', 'Supermicro', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Supermicro
include('simpleicons-7/S/Supermicro')

' renders the element
Supermicro('Supermicro', 'Supermicro', 'an optional tech label', 'an optional description')
@enduml
```

