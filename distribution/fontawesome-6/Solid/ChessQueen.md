# ChessQueen


```text
fontawesome-6/Solid/ChessQueen
```

```text
include('fontawesome-6/Solid/ChessQueen')
```



| Illustration | ChessQueen |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/ChessQueen.png) | ![illustration for ChessQueen](../../fontawesome-6/Solid/ChessQueen.Local.png) |




## ChessQueen

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ChessQueen
include('fontawesome-6/Solid/ChessQueen')

' renders the element
ChessQueen('ChessQueen', 'Chess Queen', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ChessQueen
include('fontawesome-6/Solid/ChessQueen')

' renders the element
ChessQueen('ChessQueen', 'Chess Queen', 'an optional tech label', 'an optional description')
@enduml
```

