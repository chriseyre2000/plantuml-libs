# Scrimba


```text
simpleicons-7/S/Scrimba
```

```text
include('simpleicons-7/S/Scrimba')
```



| Illustration | Scrimba |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Scrimba.png) | ![illustration for Scrimba](../../simpleicons-7/S/Scrimba.Local.png) |




## Scrimba

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Scrimba
include('simpleicons-7/S/Scrimba')

' renders the element
Scrimba('Scrimba', 'Scrimba', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Scrimba
include('simpleicons-7/S/Scrimba')

' renders the element
Scrimba('Scrimba', 'Scrimba', 'an optional tech label', 'an optional description')
@enduml
```

