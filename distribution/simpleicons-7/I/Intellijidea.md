# Intellijidea


```text
simpleicons-7/I/Intellijidea
```

```text
include('simpleicons-7/I/Intellijidea')
```



| Illustration | Intellijidea |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/I/Intellijidea.png) | ![illustration for Intellijidea](../../simpleicons-7/I/Intellijidea.Local.png) |




## Intellijidea

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Intellijidea
include('simpleicons-7/I/Intellijidea')

' renders the element
Intellijidea('Intellijidea', 'Intellijidea', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Intellijidea
include('simpleicons-7/I/Intellijidea')

' renders the element
Intellijidea('Intellijidea', 'Intellijidea', 'an optional tech label', 'an optional description')
@enduml
```

