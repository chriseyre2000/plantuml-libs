# PermIdentity


```text
material-4/Action/PermIdentity
```

```text
include('material-4/Action/PermIdentity')
```



| Illustration | PermIdentity |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/PermIdentity.png) | ![illustration for PermIdentity](../../material-4/Action/PermIdentity.Local.png) |




## PermIdentity

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PermIdentity
include('material-4/Action/PermIdentity')

' renders the element
PermIdentity('PermIdentity', 'Perm Identity', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PermIdentity
include('material-4/Action/PermIdentity')

' renders the element
PermIdentity('PermIdentity', 'Perm Identity', 'an optional tech label', 'an optional description')
@enduml
```

