# LocalMovies


```text
material-4/Maps/LocalMovies
```

```text
include('material-4/Maps/LocalMovies')
```



| Illustration | LocalMovies |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/LocalMovies.png) | ![illustration for LocalMovies](../../material-4/Maps/LocalMovies.Local.png) |




## LocalMovies

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element LocalMovies
include('material-4/Maps/LocalMovies')

' renders the element
LocalMovies('LocalMovies', 'Local Movies', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element LocalMovies
include('material-4/Maps/LocalMovies')

' renders the element
LocalMovies('LocalMovies', 'Local Movies', 'an optional tech label', 'an optional description')
@enduml
```

