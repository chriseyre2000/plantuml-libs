# Share


```text
fontawesome-6/Solid/Share
```

```text
include('fontawesome-6/Solid/Share')
```



| Illustration | Share |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Share.png) | ![illustration for Share](../../fontawesome-6/Solid/Share.Local.png) |




## Share

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Share
include('fontawesome-6/Solid/Share')

' renders the element
Share('Share', 'Share', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Share
include('fontawesome-6/Solid/Share')

' renders the element
Share('Share', 'Share', 'an optional tech label', 'an optional description')
@enduml
```

