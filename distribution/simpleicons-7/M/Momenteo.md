# Momenteo


```text
simpleicons-7/M/Momenteo
```

```text
include('simpleicons-7/M/Momenteo')
```



| Illustration | Momenteo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Momenteo.png) | ![illustration for Momenteo](../../simpleicons-7/M/Momenteo.Local.png) |




## Momenteo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Momenteo
include('simpleicons-7/M/Momenteo')

' renders the element
Momenteo('Momenteo', 'Momenteo', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Momenteo
include('simpleicons-7/M/Momenteo')

' renders the element
Momenteo('Momenteo', 'Momenteo', 'an optional tech label', 'an optional description')
@enduml
```

