# Drone


```text
simpleicons-7/D/Drone
```

```text
include('simpleicons-7/D/Drone')
```



| Illustration | Drone |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/D/Drone.png) | ![illustration for Drone](../../simpleicons-7/D/Drone.Local.png) |




## Drone

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Drone
include('simpleicons-7/D/Drone')

' renders the element
Drone('Drone', 'Drone', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Drone
include('simpleicons-7/D/Drone')

' renders the element
Drone('Drone', 'Drone', 'an optional tech label', 'an optional description')
@enduml
```

