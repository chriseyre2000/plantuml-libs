# PersonBreastfeeding


```text
fontawesome-6/Solid/PersonBreastfeeding
```

```text
include('fontawesome-6/Solid/PersonBreastfeeding')
```



| Illustration | PersonBreastfeeding |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PersonBreastfeeding.png) | ![illustration for PersonBreastfeeding](../../fontawesome-6/Solid/PersonBreastfeeding.Local.png) |




## PersonBreastfeeding

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PersonBreastfeeding
include('fontawesome-6/Solid/PersonBreastfeeding')

' renders the element
PersonBreastfeeding('PersonBreastfeeding', 'Person Breastfeeding', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PersonBreastfeeding
include('fontawesome-6/Solid/PersonBreastfeeding')

' renders the element
PersonBreastfeeding('PersonBreastfeeding', 'Person Breastfeeding', 'an optional tech label', 'an optional description')
@enduml
```

