# Intercom


```text
fontawesome-6/Brands/Intercom
```

```text
include('fontawesome-6/Brands/Intercom')
```



| Illustration | Intercom |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Intercom.png) | ![illustration for Intercom](../../fontawesome-6/Brands/Intercom.Local.png) |




## Intercom

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Intercom
include('fontawesome-6/Brands/Intercom')

' renders the element
Intercom('Intercom', 'Intercom', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Intercom
include('fontawesome-6/Brands/Intercom')

' renders the element
Intercom('Intercom', 'Intercom', 'an optional tech label', 'an optional description')
@enduml
```

