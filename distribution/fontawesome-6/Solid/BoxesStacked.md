# BoxesStacked


```text
fontawesome-6/Solid/BoxesStacked
```

```text
include('fontawesome-6/Solid/BoxesStacked')
```



| Illustration | BoxesStacked |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BoxesStacked.png) | ![illustration for BoxesStacked](../../fontawesome-6/Solid/BoxesStacked.Local.png) |




## BoxesStacked

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BoxesStacked
include('fontawesome-6/Solid/BoxesStacked')

' renders the element
BoxesStacked('BoxesStacked', 'Boxes Stacked', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BoxesStacked
include('fontawesome-6/Solid/BoxesStacked')

' renders the element
BoxesStacked('BoxesStacked', 'Boxes Stacked', 'an optional tech label', 'an optional description')
@enduml
```

