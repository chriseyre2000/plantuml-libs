# Atlassian


```text
simpleicons-7/A/Atlassian
```

```text
include('simpleicons-7/A/Atlassian')
```



| Illustration | Atlassian |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Atlassian.png) | ![illustration for Atlassian](../../simpleicons-7/A/Atlassian.Local.png) |




## Atlassian

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Atlassian
include('simpleicons-7/A/Atlassian')

' renders the element
Atlassian('Atlassian', 'Atlassian', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Atlassian
include('simpleicons-7/A/Atlassian')

' renders the element
Atlassian('Atlassian', 'Atlassian', 'an optional tech label', 'an optional description')
@enduml
```

