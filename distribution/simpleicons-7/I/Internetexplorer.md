# Internetexplorer


```text
simpleicons-7/I/Internetexplorer
```

```text
include('simpleicons-7/I/Internetexplorer')
```



| Illustration | Internetexplorer |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/I/Internetexplorer.png) | ![illustration for Internetexplorer](../../simpleicons-7/I/Internetexplorer.Local.png) |




## Internetexplorer

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Internetexplorer
include('simpleicons-7/I/Internetexplorer')

' renders the element
Internetexplorer('Internetexplorer', 'Internetexplorer', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Internetexplorer
include('simpleicons-7/I/Internetexplorer')

' renders the element
Internetexplorer('Internetexplorer', 'Internetexplorer', 'an optional tech label', 'an optional description')
@enduml
```

