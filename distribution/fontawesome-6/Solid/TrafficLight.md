# TrafficLight


```text
fontawesome-6/Solid/TrafficLight
```

```text
include('fontawesome-6/Solid/TrafficLight')
```



| Illustration | TrafficLight |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/TrafficLight.png) | ![illustration for TrafficLight](../../fontawesome-6/Solid/TrafficLight.Local.png) |




## TrafficLight

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element TrafficLight
include('fontawesome-6/Solid/TrafficLight')

' renders the element
TrafficLight('TrafficLight', 'Traffic Light', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element TrafficLight
include('fontawesome-6/Solid/TrafficLight')

' renders the element
TrafficLight('TrafficLight', 'Traffic Light', 'an optional tech label', 'an optional description')
@enduml
```

