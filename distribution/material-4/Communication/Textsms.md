# Textsms


```text
material-4/Communication/Textsms
```

```text
include('material-4/Communication/Textsms')
```



| Illustration | Textsms |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/Textsms.png) | ![illustration for Textsms](../../material-4/Communication/Textsms.Local.png) |




## Textsms

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Textsms
include('material-4/Communication/Textsms')

' renders the element
Textsms('Textsms', 'Textsms', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element Textsms
include('material-4/Communication/Textsms')

' renders the element
Textsms('Textsms', 'Textsms', 'an optional tech label', 'an optional description')
@enduml
```

