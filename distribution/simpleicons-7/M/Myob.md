# Myob


```text
simpleicons-7/M/Myob
```

```text
include('simpleicons-7/M/Myob')
```



| Illustration | Myob |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Myob.png) | ![illustration for Myob](../../simpleicons-7/M/Myob.Local.png) |




## Myob

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Myob
include('simpleicons-7/M/Myob')

' renders the element
Myob('Myob', 'Myob', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Myob
include('simpleicons-7/M/Myob')

' renders the element
Myob('Myob', 'Myob', 'an optional tech label', 'an optional description')
@enduml
```

