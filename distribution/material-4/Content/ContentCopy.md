# ContentCopy


```text
material-4/Content/ContentCopy
```

```text
include('material-4/Content/ContentCopy')
```



| Illustration | ContentCopy |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/ContentCopy.png) | ![illustration for ContentCopy](../../material-4/Content/ContentCopy.Local.png) |




## ContentCopy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ContentCopy
include('material-4/Content/ContentCopy')

' renders the element
ContentCopy('ContentCopy', 'Content Copy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ContentCopy
include('material-4/Content/ContentCopy')

' renders the element
ContentCopy('ContentCopy', 'Content Copy', 'an optional tech label', 'an optional description')
@enduml
```

