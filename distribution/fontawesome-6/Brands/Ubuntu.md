# Ubuntu


```text
fontawesome-6/Brands/Ubuntu
```

```text
include('fontawesome-6/Brands/Ubuntu')
```



| Illustration | Ubuntu |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Ubuntu.png) | ![illustration for Ubuntu](../../fontawesome-6/Brands/Ubuntu.Local.png) |




## Ubuntu

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Ubuntu
include('fontawesome-6/Brands/Ubuntu')

' renders the element
Ubuntu('Ubuntu', 'Ubuntu', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ubuntu
include('fontawesome-6/Brands/Ubuntu')

' renders the element
Ubuntu('Ubuntu', 'Ubuntu', 'an optional tech label', 'an optional description')
@enduml
```

