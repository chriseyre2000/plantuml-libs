# Monoprix


```text
simpleicons-7/M/Monoprix
```

```text
include('simpleicons-7/M/Monoprix')
```



| Illustration | Monoprix |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Monoprix.png) | ![illustration for Monoprix](../../simpleicons-7/M/Monoprix.Local.png) |




## Monoprix

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Monoprix
include('simpleicons-7/M/Monoprix')

' renders the element
Monoprix('Monoprix', 'Monoprix', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Monoprix
include('simpleicons-7/M/Monoprix')

' renders the element
Monoprix('Monoprix', 'Monoprix', 'an optional tech label', 'an optional description')
@enduml
```

