# Waze


```text
simpleicons-7/W/Waze
```

```text
include('simpleicons-7/W/Waze')
```



| Illustration | Waze |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/W/Waze.png) | ![illustration for Waze](../../simpleicons-7/W/Waze.Local.png) |




## Waze

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Waze
include('simpleicons-7/W/Waze')

' renders the element
Waze('Waze', 'Waze', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Waze
include('simpleicons-7/W/Waze')

' renders the element
Waze('Waze', 'Waze', 'an optional tech label', 'an optional description')
@enduml
```

