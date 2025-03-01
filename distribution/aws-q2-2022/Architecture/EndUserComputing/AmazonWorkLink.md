# AmazonWorkLink


```text
aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink
```

```text
include('aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink')
```



| Illustration | AmazonWorkLink | AmazonWorkLinkCard | AmazonWorkLinkGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink.png) | ![illustration for AmazonWorkLink](../../../aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink.Local.png) | ![illustration for AmazonWorkLinkCard](../../../aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLinkCard.Local.png) | ![illustration for AmazonWorkLinkGroup](../../../aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLinkGroup.Local.png) |




## AmazonWorkLink

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonWorkLink
include('aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink')

' renders the element
AmazonWorkLink('AmazonWorkLink', 'Amazon Work Link', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonWorkLink
include('aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink')

' renders the element
AmazonWorkLink('AmazonWorkLink', 'Amazon Work Link', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonWorkLinkCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonWorkLinkCard
include('aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink')

' renders the element
AmazonWorkLinkCard('AmazonWorkLinkCard', 'Amazon Work Link Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonWorkLinkCard
include('aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink')

' renders the element
AmazonWorkLinkCard('AmazonWorkLinkCard', 'Amazon Work Link Card', 'an optional description')
@enduml
```

## AmazonWorkLinkGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonWorkLinkGroup
include('aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink')

' renders the element
AmazonWorkLinkGroup('AmazonWorkLinkGroup', 'Amazon Work Link Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonWorkLinkGroup
include('aws-q2-2022/Architecture/EndUserComputing/AmazonWorkLink')

' renders the element
AmazonWorkLinkGroup('AmazonWorkLinkGroup', 'Amazon Work Link Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

