# PersonMilitaryRifle


```text
fontawesome-6/Solid/PersonMilitaryRifle
```

```text
include('fontawesome-6/Solid/PersonMilitaryRifle')
```



| Illustration | PersonMilitaryRifle |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PersonMilitaryRifle.png) | ![illustration for PersonMilitaryRifle](../../fontawesome-6/Solid/PersonMilitaryRifle.Local.png) |




## PersonMilitaryRifle

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PersonMilitaryRifle
include('fontawesome-6/Solid/PersonMilitaryRifle')

' renders the element
PersonMilitaryRifle('PersonMilitaryRifle', 'Person Military Rifle', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PersonMilitaryRifle
include('fontawesome-6/Solid/PersonMilitaryRifle')

' renders the element
PersonMilitaryRifle('PersonMilitaryRifle', 'Person Military Rifle', 'an optional tech label', 'an optional description')
@enduml
```

