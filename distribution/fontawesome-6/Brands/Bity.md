# Bity


```text
fontawesome-6/Brands/Bity
```

```text
include('fontawesome-6/Brands/Bity')
```



| Illustration | Bity |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Bity.png) | ![illustration for Bity](../../fontawesome-6/Brands/Bity.Local.png) |




## Bity

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Bity
include('fontawesome-6/Brands/Bity')

' renders the element
Bity('Bity', 'Bity', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bity
include('fontawesome-6/Brands/Bity')

' renders the element
Bity('Bity', 'Bity', 'an optional tech label', 'an optional description')
@enduml
```

