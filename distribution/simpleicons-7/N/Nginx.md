# Nginx


```text
simpleicons-7/N/Nginx
```

```text
include('simpleicons-7/N/Nginx')
```



| Illustration | Nginx |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/N/Nginx.png) | ![illustration for Nginx](../../simpleicons-7/N/Nginx.Local.png) |




## Nginx

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Nginx
include('simpleicons-7/N/Nginx')

' renders the element
Nginx('Nginx', 'Nginx', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Nginx
include('simpleicons-7/N/Nginx')

' renders the element
Nginx('Nginx', 'Nginx', 'an optional tech label', 'an optional description')
@enduml
```

