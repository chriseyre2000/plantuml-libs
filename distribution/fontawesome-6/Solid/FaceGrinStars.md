# FaceGrinStars


```text
fontawesome-6/Solid/FaceGrinStars
```

```text
include('fontawesome-6/Solid/FaceGrinStars')
```



| Illustration | FaceGrinStars |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/FaceGrinStars.png) | ![illustration for FaceGrinStars](../../fontawesome-6/Solid/FaceGrinStars.Local.png) |




## FaceGrinStars

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FaceGrinStars
include('fontawesome-6/Solid/FaceGrinStars')

' renders the element
FaceGrinStars('FaceGrinStars', 'Face Grin Stars', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FaceGrinStars
include('fontawesome-6/Solid/FaceGrinStars')

' renders the element
FaceGrinStars('FaceGrinStars', 'Face Grin Stars', 'an optional tech label', 'an optional description')
@enduml
```

