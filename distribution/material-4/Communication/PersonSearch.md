# PersonSearch


```text
material-4/Communication/PersonSearch
```

```text
include('material-4/Communication/PersonSearch')
```



| Illustration | PersonSearch |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/PersonSearch.png) | ![illustration for PersonSearch](../../material-4/Communication/PersonSearch.Local.png) |




## PersonSearch

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PersonSearch
include('material-4/Communication/PersonSearch')

' renders the element
PersonSearch('PersonSearch', 'Person Search', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PersonSearch
include('material-4/Communication/PersonSearch')

' renders the element
PersonSearch('PersonSearch', 'Person Search', 'an optional tech label', 'an optional description')
@enduml
```

