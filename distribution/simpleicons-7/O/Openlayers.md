# Openlayers


```text
simpleicons-7/O/Openlayers
```

```text
include('simpleicons-7/O/Openlayers')
```



| Illustration | Openlayers |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/O/Openlayers.png) | ![illustration for Openlayers](../../simpleicons-7/O/Openlayers.Local.png) |




## Openlayers

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Openlayers
include('simpleicons-7/O/Openlayers')

' renders the element
Openlayers('Openlayers', 'Openlayers', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Openlayers
include('simpleicons-7/O/Openlayers')

' renders the element
Openlayers('Openlayers', 'Openlayers', 'an optional tech label', 'an optional description')
@enduml
```

