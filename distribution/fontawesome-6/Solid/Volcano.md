# Volcano


```text
fontawesome-6/Solid/Volcano
```

```text
include('fontawesome-6/Solid/Volcano')
```



| Illustration | Volcano |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Volcano.png) | ![illustration for Volcano](../../fontawesome-6/Solid/Volcano.Local.png) |




## Volcano

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Volcano
include('fontawesome-6/Solid/Volcano')

' renders the element
Volcano('Volcano', 'Volcano', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Volcano
include('fontawesome-6/Solid/Volcano')

' renders the element
Volcano('Volcano', 'Volcano', 'an optional tech label', 'an optional description')
@enduml
```

