# ImportExport


```text
material-4/Communication/ImportExport
```

```text
include('material-4/Communication/ImportExport')
```



| Illustration | ImportExport |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/ImportExport.png) | ![illustration for ImportExport](../../material-4/Communication/ImportExport.Local.png) |




## ImportExport

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ImportExport
include('material-4/Communication/ImportExport')

' renders the element
ImportExport('ImportExport', 'Import Export', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ImportExport
include('material-4/Communication/ImportExport')

' renders the element
ImportExport('ImportExport', 'Import Export', 'an optional tech label', 'an optional description')
@enduml
```

