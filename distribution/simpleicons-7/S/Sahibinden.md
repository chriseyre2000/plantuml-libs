# Sahibinden


```text
simpleicons-7/S/Sahibinden
```

```text
include('simpleicons-7/S/Sahibinden')
```



| Illustration | Sahibinden |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Sahibinden.png) | ![illustration for Sahibinden](../../simpleicons-7/S/Sahibinden.Local.png) |




## Sahibinden

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Sahibinden
include('simpleicons-7/S/Sahibinden')

' renders the element
Sahibinden('Sahibinden', 'Sahibinden', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sahibinden
include('simpleicons-7/S/Sahibinden')

' renders the element
Sahibinden('Sahibinden', 'Sahibinden', 'an optional tech label', 'an optional description')
@enduml
```

