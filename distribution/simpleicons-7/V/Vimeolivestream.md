# Vimeolivestream


```text
simpleicons-7/V/Vimeolivestream
```

```text
include('simpleicons-7/V/Vimeolivestream')
```



| Illustration | Vimeolivestream |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/V/Vimeolivestream.png) | ![illustration for Vimeolivestream](../../simpleicons-7/V/Vimeolivestream.Local.png) |




## Vimeolivestream

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Vimeolivestream
include('simpleicons-7/V/Vimeolivestream')

' renders the element
Vimeolivestream('Vimeolivestream', 'Vimeolivestream', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Vimeolivestream
include('simpleicons-7/V/Vimeolivestream')

' renders the element
Vimeolivestream('Vimeolivestream', 'Vimeolivestream', 'an optional tech label', 'an optional description')
@enduml
```

