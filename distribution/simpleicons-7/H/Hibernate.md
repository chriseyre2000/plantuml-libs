# Hibernate


```text
simpleicons-7/H/Hibernate
```

```text
include('simpleicons-7/H/Hibernate')
```



| Illustration | Hibernate |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/H/Hibernate.png) | ![illustration for Hibernate](../../simpleicons-7/H/Hibernate.Local.png) |




## Hibernate

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Hibernate
include('simpleicons-7/H/Hibernate')

' renders the element
Hibernate('Hibernate', 'Hibernate', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Hibernate
include('simpleicons-7/H/Hibernate')

' renders the element
Hibernate('Hibernate', 'Hibernate', 'an optional tech label', 'an optional description')
@enduml
```

