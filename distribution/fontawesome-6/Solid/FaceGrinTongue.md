# FaceGrinTongue


```text
fontawesome-6/Solid/FaceGrinTongue
```

```text
include('fontawesome-6/Solid/FaceGrinTongue')
```



| Illustration | FaceGrinTongue |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/FaceGrinTongue.png) | ![illustration for FaceGrinTongue](../../fontawesome-6/Solid/FaceGrinTongue.Local.png) |




## FaceGrinTongue

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FaceGrinTongue
include('fontawesome-6/Solid/FaceGrinTongue')

' renders the element
FaceGrinTongue('FaceGrinTongue', 'Face Grin Tongue', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FaceGrinTongue
include('fontawesome-6/Solid/FaceGrinTongue')

' renders the element
FaceGrinTongue('FaceGrinTongue', 'Face Grin Tongue', 'an optional tech label', 'an optional description')
@enduml
```

