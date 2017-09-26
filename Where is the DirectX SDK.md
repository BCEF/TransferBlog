# [译]DirectX SDK去哪了？Where is the DirectX SDK?
MSDN地址：
`https://msdn.microsoft.com/en-us/library/windows/desktop/ee663275(v=vs.85).aspx`

> Starting with Windows 8, the DirectX SDK is included as part of the Windows SDK.

从Windows 8开始，DirectX SDK被包含在Windows SDK中，成为了Windows SDK的一部分。

> We originally created the DirectX SDK as a high-performance platform for game development on top of Windows. As DirectX technologies matured, they became relevant to a broader range of applications. Today, the availability of Direct3D hardware in computers drives even traditional desktop applications to use graphics hardware acceleration. In parallel, DirectX technologies are more integrated with Windows. DirectX is now a fundamental part of Windows.

我们最初创造的DirectX，是作为Windows上的一个高性能的游戏开发平台。随着DirectX技术日渐成熟，它变得和越来越多的应用息息相关。如今，计算机中的Direct3D硬件的可用性驱动着传统的桌面应用也使用图形硬件加速。同时，DirectX技术也愈发集成进Windows中。DirectX 现在是Windows的基本组成部分。

> Because the Windows SDK is the primary developer SDK for Windows, DirectX is now included in it. You can now use the Windows SDK to build great games for Windows. To download the Windows 8 SDK, see Windows SDK and emulator archive.

由于Windows SDK是Windows的主要开发人员的SDK，所以DirectX被包含在Windows SDK中了。现在，你可以使用Windows SDK去构建出色的Windows游戏了。要下载Windows 8 SDK，请参阅**Windows SDK和emulator文档**。

> The following technologies and tools, formerly part of the DirectX SDK, are now part of the Windows SDK:

下列的技术和工具，以往是DirectX SDK的一部分，现在是Windows SDK的一部分：

|技术或工具|描述|
|------|:---|
|Windows Graphics Components<br><br>Windows图形组件|The headers and libraries for **Direct3D** and other Windows graphics APIs, like **Direct2D**, are available in the Windows SDK.<br>`Note: D3DX is only available for download in previous versions of the DirectX SDK. The D3DCSX DirectCompute utility library is available in the Windows SDK.`<br><br>Direct3D的头文件和库，以及其他的Windows图形API，比如Direct2D，在Windows SDK中是可以使用的。<br>`注意：D3DX只可以在之前版本的SDK中下载。D3DCSX DirectCompute实用程序库在Windows SDK中可用。`|
|HLSL compiler (FXC.EXE)<br><br>HLSL编译器(FXC.EXE)|The **HLSL** compiler is a tool in the appropriate architecture subdirectory under the bin folder in the Windows SDK.<br>`Note:  The D3DCompiler API is available in the Windows SDK.`<br><br>HLSL编译器在Windows SDK中是一个在bin文件夹下对应架构子目录的工具<br>`注意：D3DCompiler API在Windows SDK中是可用的。`|
|PIX for Windows<br><br>Windows下的PIX|A replacement for the PIX for Windows tool is now a feature in Microsoft Visual Studio, called Visual Studio Graphics Debugger. This new feature has greatly improved usability, support for Windows 8, and Direct3D 11.1, and integration with traditional Microsoft Visual Studio features such as call stacks and debugging windows for **HLSL** debugging. For more info about this new feature, see **Debugging DirectX Graphics.**<br><br>Windows下的PIX的替代方案是使用Microsoft Visual Studio中的一个叫做Visual Studio Graphics Debugger的功能。这个新功能大幅提升了可用性，支持Windows 8、Direct3D 11.1，并与传统的Microsoft Visual Studio功能集成，如调用堆栈和调试窗口去调试**HLSL**。 关于此功能的更多信息请查阅**Debugging DirectX Graphics.**|

