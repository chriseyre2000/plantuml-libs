# CloudMoonRain


```text
fontawesome-6/Solid/CloudMoonRain
```

```text
include('fontawesome-6/Solid/CloudMoonRain')
```



| Illustration | CloudMoonRain |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/CloudMoonRain.png) | ![illustration for CloudMoonRain](../../fontawesome-6/Solid/CloudMoonRain.Local.png) |




## CloudMoonRain

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CloudMoonRain
include('fontawesome-6/Solid/CloudMoonRain')

' renders the element
CloudMoonRain('CloudMoonRain', 'Cloud Moon Rain', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CloudMoonRain
include('fontawesome-6/Solid/CloudMoonRain')

' renders the element
CloudMoonRain('CloudMoonRain', 'Cloud Moon Rain', 'an optional tech label', 'an optional description')
@enduml
```

