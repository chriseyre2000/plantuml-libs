# Elastic


```text
simpleicons-7/E/Elastic
```

```text
include('simpleicons-7/E/Elastic')
```



| Illustration | Elastic |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/E/Elastic.png) | ![illustration for Elastic](../../simpleicons-7/E/Elastic.Local.png) |




## Elastic

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Elastic
include('simpleicons-7/E/Elastic')

' renders the element
Elastic('Elastic', 'Elastic', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Elastic
include('simpleicons-7/E/Elastic')

' renders the element
Elastic('Elastic', 'Elastic', 'an optional tech label', 'an optional description')
@enduml
```

