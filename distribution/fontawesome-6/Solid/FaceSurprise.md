# FaceSurprise


```text
fontawesome-6/Solid/FaceSurprise
```

```text
include('fontawesome-6/Solid/FaceSurprise')
```



| Illustration | FaceSurprise |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/FaceSurprise.png) | ![illustration for FaceSurprise](../../fontawesome-6/Solid/FaceSurprise.Local.png) |




## FaceSurprise

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FaceSurprise
include('fontawesome-6/Solid/FaceSurprise')

' renders the element
FaceSurprise('FaceSurprise', 'Face Surprise', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FaceSurprise
include('fontawesome-6/Solid/FaceSurprise')

' renders the element
FaceSurprise('FaceSurprise', 'Face Surprise', 'an optional tech label', 'an optional description')
@enduml
```

