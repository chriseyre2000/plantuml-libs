# Aiohttp


```text
simpleicons-7/A/Aiohttp
```

```text
include('simpleicons-7/A/Aiohttp')
```



| Illustration | Aiohttp |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Aiohttp.png) | ![illustration for Aiohttp](../../simpleicons-7/A/Aiohttp.Local.png) |




## Aiohttp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Aiohttp
include('simpleicons-7/A/Aiohttp')

' renders the element
Aiohttp('Aiohttp', 'Aiohttp', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Aiohttp
include('simpleicons-7/A/Aiohttp')

' renders the element
Aiohttp('Aiohttp', 'Aiohttp', 'an optional tech label', 'an optional description')
@enduml
```

