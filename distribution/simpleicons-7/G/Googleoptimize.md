# Googleoptimize


```text
simpleicons-7/G/Googleoptimize
```

```text
include('simpleicons-7/G/Googleoptimize')
```



| Illustration | Googleoptimize |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/G/Googleoptimize.png) | ![illustration for Googleoptimize](../../simpleicons-7/G/Googleoptimize.Local.png) |




## Googleoptimize

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Googleoptimize
include('simpleicons-7/G/Googleoptimize')

' renders the element
Googleoptimize('Googleoptimize', 'Googleoptimize', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Googleoptimize
include('simpleicons-7/G/Googleoptimize')

' renders the element
Googleoptimize('Googleoptimize', 'Googleoptimize', 'an optional tech label', 'an optional description')
@enduml
```

