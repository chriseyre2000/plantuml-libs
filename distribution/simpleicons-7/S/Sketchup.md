# Sketchup


```text
simpleicons-7/S/Sketchup
```

```text
include('simpleicons-7/S/Sketchup')
```



| Illustration | Sketchup |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Sketchup.png) | ![illustration for Sketchup](../../simpleicons-7/S/Sketchup.Local.png) |




## Sketchup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Sketchup
include('simpleicons-7/S/Sketchup')

' renders the element
Sketchup('Sketchup', 'Sketchup', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sketchup
include('simpleicons-7/S/Sketchup')

' renders the element
Sketchup('Sketchup', 'Sketchup', 'an optional tech label', 'an optional description')
@enduml
```

