# Podcast


```text
fontawesome-6/Solid/Podcast
```

```text
include('fontawesome-6/Solid/Podcast')
```



| Illustration | Podcast |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Podcast.png) | ![illustration for Podcast](../../fontawesome-6/Solid/Podcast.Local.png) |




## Podcast

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Podcast
include('fontawesome-6/Solid/Podcast')

' renders the element
Podcast('Podcast', 'Podcast', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Podcast
include('fontawesome-6/Solid/Podcast')

' renders the element
Podcast('Podcast', 'Podcast', 'an optional tech label', 'an optional description')
@enduml
```

