# Trino


```text
simpleicons-7/T/Trino
```

```text
include('simpleicons-7/T/Trino')
```



| Illustration | Trino |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/T/Trino.png) | ![illustration for Trino](../../simpleicons-7/T/Trino.Local.png) |




## Trino

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Trino
include('simpleicons-7/T/Trino')

' renders the element
Trino('Trino', 'Trino', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Trino
include('simpleicons-7/T/Trino')

' renders the element
Trino('Trino', 'Trino', 'an optional tech label', 'an optional description')
@enduml
```

