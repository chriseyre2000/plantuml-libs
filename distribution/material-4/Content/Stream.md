# Stream


```text
material-4/Content/Stream
```

```text
include('material-4/Content/Stream')
```



| Illustration | Stream |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Stream.png) | ![illustration for Stream](../../material-4/Content/Stream.Local.png) |




## Stream

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Stream
include('material-4/Content/Stream')

' renders the element
Stream('Stream', 'Stream', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Stream
include('material-4/Content/Stream')

' renders the element
Stream('Stream', 'Stream', 'an optional tech label', 'an optional description')
@enduml
```

