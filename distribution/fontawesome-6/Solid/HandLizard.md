# HandLizard


```text
fontawesome-6/Solid/HandLizard
```

```text
include('fontawesome-6/Solid/HandLizard')
```



| Illustration | HandLizard |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/HandLizard.png) | ![illustration for HandLizard](../../fontawesome-6/Solid/HandLizard.Local.png) |




## HandLizard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element HandLizard
include('fontawesome-6/Solid/HandLizard')

' renders the element
HandLizard('HandLizard', 'Hand Lizard', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HandLizard
include('fontawesome-6/Solid/HandLizard')

' renders the element
HandLizard('HandLizard', 'Hand Lizard', 'an optional tech label', 'an optional description')
@enduml
```

