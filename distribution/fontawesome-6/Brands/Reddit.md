# Reddit


```text
fontawesome-6/Brands/Reddit
```

```text
include('fontawesome-6/Brands/Reddit')
```



| Illustration | Reddit |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Reddit.png) | ![illustration for Reddit](../../fontawesome-6/Brands/Reddit.Local.png) |




## Reddit

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Reddit
include('fontawesome-6/Brands/Reddit')

' renders the element
Reddit('Reddit', 'Reddit', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Reddit
include('fontawesome-6/Brands/Reddit')

' renders the element
Reddit('Reddit', 'Reddit', 'an optional tech label', 'an optional description')
@enduml
```

