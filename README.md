This Repository Provides Two Flash Options.
* PPAPI [Pepper Flash] [ <= or > Visual Studio 2022]
* AxShockwave [Flash] [ =< Visual Studio 2019] (May work with 22)

The version you choose will affect which steps you need to follow for use and enabling.

Pepper Flash: is Dependant on a Browser that still has support, a.k.a. Custom Browsers/Etc...
* This Variant of Flash does not require you to register the File and enables Flash for that browser (If the browsers allows it)
* Security can be stored locally in the BaseDomain, allowing portability of the application with flash enabled.
* Safer than the Usual Flash install, or a Shady EXE variant on the internet as it does not need to install.

AxShockwave: Requires registering the OCX to the System. (can be done via Command-Line/C#)
* This is the more typical "Flash" install and must be placed in System32 && SysWoW64 Macromed/Macromedia Folder
* This version can be imported into a Visual Studio Project and Used for various purposes.
* This version will allow older flash applications to run again (Use the System32/SysWoW64 but place the 32-bit only if you want most applications to reconize the registered install) For Example..: Sothink Flash Decompiler works just fine once this version is registered (32-bit)

To find and choose your desired version of Flash, please select the appropriate branch from the Upper-left List.
There you will find the files needed (Not yet Complete, but for Developers that just need the Flash, Good already as for the Wiki, W.I.P.)
USE AT OWN RISK AND OWN LIABILITY. PROVIDED FOR EDUCATIONAL USE AND PURPOSES ONLY.
