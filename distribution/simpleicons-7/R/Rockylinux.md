# Rockylinux


```text
simpleicons-7/R/Rockylinux
```

```text
include('simpleicons-7/R/Rockylinux')
```



| Illustration | Rockylinux |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/R/Rockylinux.png) | ![illustration for Rockylinux](../../simpleicons-7/R/Rockylinux.Local.png) |




## Rockylinux

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Rockylinux
include('simpleicons-7/R/Rockylinux')

' renders the element
Rockylinux('Rockylinux', 'Rockylinux', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Rockylinux
include('simpleicons-7/R/Rockylinux')

' renders the element
Rockylinux('Rockylinux', 'Rockylinux', 'an optional tech label', 'an optional description')
@enduml
```

