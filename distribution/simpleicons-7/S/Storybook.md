# Storybook


```text
simpleicons-7/S/Storybook
```

```text
include('simpleicons-7/S/Storybook')
```



| Illustration | Storybook |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Storybook.png) | ![illustration for Storybook](../../simpleicons-7/S/Storybook.Local.png) |




## Storybook

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Storybook
include('simpleicons-7/S/Storybook')

' renders the element
Storybook('Storybook', 'Storybook', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Storybook
include('simpleicons-7/S/Storybook')

' renders the element
Storybook('Storybook', 'Storybook', 'an optional tech label', 'an optional description')
@enduml
```

