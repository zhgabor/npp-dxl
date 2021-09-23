### DXL Custom Language and Function List definitions for Notepad++

This custom language is for using IBM DOORS DXL in Notepad++ with codefolding and syntax highlighting.
To enable function list go to View>Function List in NPP

Installation
1. Copy DXLv2.udl.xml to `\userDefineLangs\`
2. Copy dxl.xml to `\functionList\`
3. add the line `<association id= "dxl.xml"	userDefinedLangName="DXL"/>` to `\functionList\overrideMap.xml`


Todo
* add includes also to functions list
