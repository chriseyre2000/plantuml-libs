# Coronaengine


```text
simpleicons-7/C/Coronaengine
```

```text
include('simpleicons-7/C/Coronaengine')
```



| Illustration | Coronaengine |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Coronaengine.png) | ![illustration for Coronaengine](../../simpleicons-7/C/Coronaengine.Local.png) |




## Coronaengine

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Coronaengine
include('simpleicons-7/C/Coronaengine')

' renders the element
Coronaengine('Coronaengine', 'Coronaengine', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Coronaengine
include('simpleicons-7/C/Coronaengine')

' renders the element
Coronaengine('Coronaengine', 'Coronaengine', 'an optional tech label', 'an optional description')
@enduml
```

