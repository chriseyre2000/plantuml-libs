# Musicbrainz


```text
simpleicons-7/M/Musicbrainz
```

```text
include('simpleicons-7/M/Musicbrainz')
```



| Illustration | Musicbrainz |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Musicbrainz.png) | ![illustration for Musicbrainz](../../simpleicons-7/M/Musicbrainz.Local.png) |




## Musicbrainz

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Musicbrainz
include('simpleicons-7/M/Musicbrainz')

' renders the element
Musicbrainz('Musicbrainz', 'Musicbrainz', 'an optional tech label', 'an optional description')
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
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Musicbrainz
include('simpleicons-7/M/Musicbrainz')

' renders the element
Musicbrainz('Musicbrainz', 'Musicbrainz', 'an optional tech label', 'an optional description')
@enduml
```

