# Bugsnag


```text
simpleicons-7/B/Bugsnag
```

```text
include('simpleicons-7/B/Bugsnag')
```



| Illustration | Bugsnag |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/B/Bugsnag.png) | ![illustration for Bugsnag](../../simpleicons-7/B/Bugsnag.Local.png) |




## Bugsnag

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Bugsnag
include('simpleicons-7/B/Bugsnag')

' renders the element
Bugsnag('Bugsnag', 'Bugsnag', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bugsnag
include('simpleicons-7/B/Bugsnag')

' renders the element
Bugsnag('Bugsnag', 'Bugsnag', 'an optional tech label', 'an optional description')
@enduml
```

