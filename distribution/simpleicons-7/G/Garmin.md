# Garmin


```text
simpleicons-7/G/Garmin
```

```text
include('simpleicons-7/G/Garmin')
```



| Illustration | Garmin |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/G/Garmin.png) | ![illustration for Garmin](../../simpleicons-7/G/Garmin.Local.png) |




## Garmin

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Garmin
include('simpleicons-7/G/Garmin')

' renders the element
Garmin('Garmin', 'Garmin', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Garmin
include('simpleicons-7/G/Garmin')

' renders the element
Garmin('Garmin', 'Garmin', 'an optional tech label', 'an optional description')
@enduml
```

