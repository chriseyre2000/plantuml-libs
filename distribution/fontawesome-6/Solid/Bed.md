# Bed


```text
fontawesome-6/Solid/Bed
```

```text
include('fontawesome-6/Solid/Bed')
```



| Illustration | Bed |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Bed.png) | ![illustration for Bed](../../fontawesome-6/Solid/Bed.Local.png) |




## Bed

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Bed
include('fontawesome-6/Solid/Bed')

' renders the element
Bed('Bed', 'Bed', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bed
include('fontawesome-6/Solid/Bed')

' renders the element
Bed('Bed', 'Bed', 'an optional tech label', 'an optional description')
@enduml
```

