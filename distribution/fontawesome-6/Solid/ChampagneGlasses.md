# ChampagneGlasses


```text
fontawesome-6/Solid/ChampagneGlasses
```

```text
include('fontawesome-6/Solid/ChampagneGlasses')
```



| Illustration | ChampagneGlasses |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/ChampagneGlasses.png) | ![illustration for ChampagneGlasses](../../fontawesome-6/Solid/ChampagneGlasses.Local.png) |




## ChampagneGlasses

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ChampagneGlasses
include('fontawesome-6/Solid/ChampagneGlasses')

' renders the element
ChampagneGlasses('ChampagneGlasses', 'Champagne Glasses', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ChampagneGlasses
include('fontawesome-6/Solid/ChampagneGlasses')

' renders the element
ChampagneGlasses('ChampagneGlasses', 'Champagne Glasses', 'an optional tech label', 'an optional description')
@enduml
```

