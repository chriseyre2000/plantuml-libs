# PlaylistPlay


```text
material-4/Av/PlaylistPlay
```

```text
include('material-4/Av/PlaylistPlay')
```



| Illustration | PlaylistPlay |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/PlaylistPlay.png) | ![illustration for PlaylistPlay](../../material-4/Av/PlaylistPlay.Local.png) |




## PlaylistPlay

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PlaylistPlay
include('material-4/Av/PlaylistPlay')

' renders the element
PlaylistPlay('PlaylistPlay', 'Playlist Play', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PlaylistPlay
include('material-4/Av/PlaylistPlay')

' renders the element
PlaylistPlay('PlaylistPlay', 'Playlist Play', 'an optional tech label', 'an optional description')
@enduml
```

