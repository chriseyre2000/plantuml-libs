# Fluentbit


```text
simpleicons-7/F/Fluentbit
```

```text
include('simpleicons-7/F/Fluentbit')
```



| Illustration | Fluentbit |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/F/Fluentbit.png) | ![illustration for Fluentbit](../../simpleicons-7/F/Fluentbit.Local.png) |




## Fluentbit

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Fluentbit
include('simpleicons-7/F/Fluentbit')

' renders the element
Fluentbit('Fluentbit', 'Fluentbit', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fluentbit
include('simpleicons-7/F/Fluentbit')

' renders the element
Fluentbit('Fluentbit', 'Fluentbit', 'an optional tech label', 'an optional description')
@enduml
```

