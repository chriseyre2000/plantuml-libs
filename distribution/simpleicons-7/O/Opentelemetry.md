# Opentelemetry


```text
simpleicons-7/O/Opentelemetry
```

```text
include('simpleicons-7/O/Opentelemetry')
```



| Illustration | Opentelemetry |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/O/Opentelemetry.png) | ![illustration for Opentelemetry](../../simpleicons-7/O/Opentelemetry.Local.png) |




## Opentelemetry

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Opentelemetry
include('simpleicons-7/O/Opentelemetry')

' renders the element
Opentelemetry('Opentelemetry', 'Opentelemetry', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Opentelemetry
include('simpleicons-7/O/Opentelemetry')

' renders the element
Opentelemetry('Opentelemetry', 'Opentelemetry', 'an optional tech label', 'an optional description')
@enduml
```

