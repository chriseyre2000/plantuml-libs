# Tryitonline


```text
simpleicons-7/T/Tryitonline
```

```text
include('simpleicons-7/T/Tryitonline')
```



| Illustration | Tryitonline |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/T/Tryitonline.png) | ![illustration for Tryitonline](../../simpleicons-7/T/Tryitonline.Local.png) |




## Tryitonline

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Tryitonline
include('simpleicons-7/T/Tryitonline')

' renders the element
Tryitonline('Tryitonline', 'Tryitonline', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Tryitonline
include('simpleicons-7/T/Tryitonline')

' renders the element
Tryitonline('Tryitonline', 'Tryitonline', 'an optional tech label', 'an optional description')
@enduml
```

