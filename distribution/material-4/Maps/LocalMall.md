# LocalMall


```text
material-4/Maps/LocalMall
```

```text
include('material-4/Maps/LocalMall')
```



| Illustration | LocalMall |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/LocalMall.png) | ![illustration for LocalMall](../../material-4/Maps/LocalMall.Local.png) |




## LocalMall

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element LocalMall
include('material-4/Maps/LocalMall')

' renders the element
LocalMall('LocalMall', 'Local Mall', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element LocalMall
include('material-4/Maps/LocalMall')

' renders the element
LocalMall('LocalMall', 'Local Mall', 'an optional tech label', 'an optional description')
@enduml
```

