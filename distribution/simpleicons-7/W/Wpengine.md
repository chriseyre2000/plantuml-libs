# Wpengine


```text
simpleicons-7/W/Wpengine
```

```text
include('simpleicons-7/W/Wpengine')
```



| Illustration | Wpengine |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/W/Wpengine.png) | ![illustration for Wpengine](../../simpleicons-7/W/Wpengine.Local.png) |




## Wpengine

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Wpengine
include('simpleicons-7/W/Wpengine')

' renders the element
Wpengine('Wpengine', 'Wpengine', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wpengine
include('simpleicons-7/W/Wpengine')

' renders the element
Wpengine('Wpengine', 'Wpengine', 'an optional tech label', 'an optional description')
@enduml
```

