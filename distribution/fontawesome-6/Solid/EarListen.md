# EarListen


```text
fontawesome-6/Solid/EarListen
```

```text
include('fontawesome-6/Solid/EarListen')
```



| Illustration | EarListen |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/EarListen.png) | ![illustration for EarListen](../../fontawesome-6/Solid/EarListen.Local.png) |




## EarListen

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element EarListen
include('fontawesome-6/Solid/EarListen')

' renders the element
EarListen('EarListen', 'Ear Listen', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element EarListen
include('fontawesome-6/Solid/EarListen')

' renders the element
EarListen('EarListen', 'Ear Listen', 'an optional tech label', 'an optional description')
@enduml
```

