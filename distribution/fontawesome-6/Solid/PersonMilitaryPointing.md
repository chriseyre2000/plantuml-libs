# PersonMilitaryPointing


```text
fontawesome-6/Solid/PersonMilitaryPointing
```

```text
include('fontawesome-6/Solid/PersonMilitaryPointing')
```



| Illustration | PersonMilitaryPointing |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PersonMilitaryPointing.png) | ![illustration for PersonMilitaryPointing](../../fontawesome-6/Solid/PersonMilitaryPointing.Local.png) |




## PersonMilitaryPointing

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PersonMilitaryPointing
include('fontawesome-6/Solid/PersonMilitaryPointing')

' renders the element
PersonMilitaryPointing('PersonMilitaryPointing', 'Person Military Pointing', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PersonMilitaryPointing
include('fontawesome-6/Solid/PersonMilitaryPointing')

' renders the element
PersonMilitaryPointing('PersonMilitaryPointing', 'Person Military Pointing', 'an optional tech label', 'an optional description')
@enduml
```

