# BookSkull


```text
fontawesome-6/Solid/BookSkull
```

```text
include('fontawesome-6/Solid/BookSkull')
```



| Illustration | BookSkull |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BookSkull.png) | ![illustration for BookSkull](../../fontawesome-6/Solid/BookSkull.Local.png) |




## BookSkull

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BookSkull
include('fontawesome-6/Solid/BookSkull')

' renders the element
BookSkull('BookSkull', 'Book Skull', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BookSkull
include('fontawesome-6/Solid/BookSkull')

' renders the element
BookSkull('BookSkull', 'Book Skull', 'an optional tech label', 'an optional description')
@enduml
```

