Engine Overview
================

Cryengine is made up of multiple components with different functionalities that are connected to facilitate
the engines features. This Page outlines how these modules are connected and how they work together.
Furthermore we will create an outline of how the engine is initialized and how the core engine loop operates through the different modules.

Module Overview
^^^^^^^^^^^^^^^
.. role:: raw-html(raw)
 :format: html

+--------------------+----------------------------------------------------------------------------------------------------------+
|CrySystem           | The core engine system. :raw-html:`<br />`                                                               |
|                    | Responsible for loading the modules as well as all System related tasks. :raw-html:`<br />`              |
|                    | Fore Example: :raw-html:`<br />`                                                                         |
|                    | - Memory Allocation :raw-html:`<br />`                                                                   |
|                    | - Platform Interaction  :raw-html:`<br />`                                                               |
|                    | - File Interaction :raw-html:`<br />`                                                                    |
|                    | - Thread Management :raw-html:`<br />`                                                                   |
|                    | - Profiling :raw-html:`<br />`                                                                           |
+--------------------+----------------------------------------------------------------------------------------------------------+
|CryRenderer*        |The main Renderer. Shared core codebase, :raw-html:`<br />`                                               |
|                    |but implemented as different modules for each target Platform. :raw-html:`<br />`                         |
+--------------------+----------------------------------------------------------------------------------------------------------+
|CryRendererD3D11    |DirectX 11 implementation of the Renderer.                                                                |
+--------------------+----------------------------------------------------------------------------------------------------------+
|CryRendererD3D12    |DirectX 12 implementation of the Renderer.                                                                |
+--------------------+----------------------------------------------------------------------------------------------------------+
|CryRendererVulkan   |Vulkan implementation of the Renderer.                                                                    |
+--------------------+----------------------------------------------------------------------------------------------------------+
|CryRendererOpenGL   |OpenGL implementation of the Renderer.                                                                    |
+--------------------+----------------------------------------------------------------------------------------------------------+

