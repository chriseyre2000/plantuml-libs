# Trailer


```text
fontawesome-6/Solid/Trailer
```

```text
include('fontawesome-6/Solid/Trailer')
```



| Illustration | Trailer |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Trailer.png) | ![illustration for Trailer](../../fontawesome-6/Solid/Trailer.Local.png) |




## Trailer

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Trailer
include('fontawesome-6/Solid/Trailer')

' renders the element
Trailer('Trailer', 'Trailer', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Trailer
include('fontawesome-6/Solid/Trailer')

' renders the element
Trailer('Trailer', 'Trailer', 'an optional tech label', 'an optional description')
@enduml
```

