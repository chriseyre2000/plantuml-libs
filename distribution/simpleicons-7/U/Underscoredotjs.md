# Underscoredotjs


```text
simpleicons-7/U/Underscoredotjs
```

```text
include('simpleicons-7/U/Underscoredotjs')
```



| Illustration | Underscoredotjs |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/U/Underscoredotjs.png) | ![illustration for Underscoredotjs](../../simpleicons-7/U/Underscoredotjs.Local.png) |




## Underscoredotjs

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Underscoredotjs
include('simpleicons-7/U/Underscoredotjs')

' renders the element
Underscoredotjs('Underscoredotjs', 'Underscoredotjs', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Underscoredotjs
include('simpleicons-7/U/Underscoredotjs')

' renders the element
Underscoredotjs('Underscoredotjs', 'Underscoredotjs', 'an optional tech label', 'an optional description')
@enduml
```

