# Chartdotjs


```text
simpleicons-7/C/Chartdotjs
```

```text
include('simpleicons-7/C/Chartdotjs')
```



| Illustration | Chartdotjs |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Chartdotjs.png) | ![illustration for Chartdotjs](../../simpleicons-7/C/Chartdotjs.Local.png) |




## Chartdotjs

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Chartdotjs
include('simpleicons-7/C/Chartdotjs')

' renders the element
Chartdotjs('Chartdotjs', 'Chartdotjs', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Chartdotjs
include('simpleicons-7/C/Chartdotjs')

' renders the element
Chartdotjs('Chartdotjs', 'Chartdotjs', 'an optional tech label', 'an optional description')
@enduml
```

