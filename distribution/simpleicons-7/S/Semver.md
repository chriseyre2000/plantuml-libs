# Semver


```text
simpleicons-7/S/Semver
```

```text
include('simpleicons-7/S/Semver')
```



| Illustration | Semver |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Semver.png) | ![illustration for Semver](../../simpleicons-7/S/Semver.Local.png) |




## Semver

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Semver
include('simpleicons-7/S/Semver')

' renders the element
Semver('Semver', 'Semver', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Semver
include('simpleicons-7/S/Semver')

' renders the element
Semver('Semver', 'Semver', 'an optional tech label', 'an optional description')
@enduml
```

