# Googletagmanager


```text
simpleicons-7/G/Googletagmanager
```

```text
include('simpleicons-7/G/Googletagmanager')
```



| Illustration | Googletagmanager |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/G/Googletagmanager.png) | ![illustration for Googletagmanager](../../simpleicons-7/G/Googletagmanager.Local.png) |




## Googletagmanager

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Googletagmanager
include('simpleicons-7/G/Googletagmanager')

' renders the element
Googletagmanager('Googletagmanager', 'Googletagmanager', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Googletagmanager
include('simpleicons-7/G/Googletagmanager')

' renders the element
Googletagmanager('Googletagmanager', 'Googletagmanager', 'an optional tech label', 'an optional description')
@enduml
```

