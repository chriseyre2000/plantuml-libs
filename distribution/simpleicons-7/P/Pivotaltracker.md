# Pivotaltracker


```text
simpleicons-7/P/Pivotaltracker
```

```text
include('simpleicons-7/P/Pivotaltracker')
```



| Illustration | Pivotaltracker |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Pivotaltracker.png) | ![illustration for Pivotaltracker](../../simpleicons-7/P/Pivotaltracker.Local.png) |




## Pivotaltracker

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Pivotaltracker
include('simpleicons-7/P/Pivotaltracker')

' renders the element
Pivotaltracker('Pivotaltracker', 'Pivotaltracker', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pivotaltracker
include('simpleicons-7/P/Pivotaltracker')

' renders the element
Pivotaltracker('Pivotaltracker', 'Pivotaltracker', 'an optional tech label', 'an optional description')
@enduml
```

