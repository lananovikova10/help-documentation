# APIs

This is the top-level directory for all externally visible APIs, plus some
private APIs under `internal/` directories.
See API Style Guide for more information.

*TL;DR*: API definitions and configurations should be defined in `.proto` files,
checked into `apis/`.

<code-block lang="plantuml">
    <![CDATA[
    @startuml
    Class01 <|-- Class02
    Class03 *-- Class04
    Class05 o-- Class06
    Class07 .. Class08
    Class09 -- Class10
    @enduml
    ]]>
</code-block>

[//]: # (<api-doc openapi-path="../JONATHANALGARGITHUB-alttexter-0.1-resolved.yaml"></api-doc>)

<api-doc openapi-path="../../petstore.yaml"/>
