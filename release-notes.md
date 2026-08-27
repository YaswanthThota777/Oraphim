# Oraphim 1.0.0 Public Beta

Professional video editing, motion graphics, compositing, color, and procedural VFX in one native Windows application.

## Windows x64 package

Download `Oraphim-1.0.0-beta-Windows-x64.zip`.
The ZIP contains exactly one file: `OraphimSetup.exe`.

ZIP SHA-256: `bc4a268937a59b653ce7b55f3d8d971653de9d416dfa1de9254898885612bdb9`

Installer SHA-256: `9a9db7e1e1cc3189d733669ae63d35fb01a210bc0d52b08a3e6ef32d926f9026`

## Release certification

- Fresh Windows x64 Release build passed.
- Portable runtime validation passed for 517 staged files.
- Headless MCP / OpenColorIO smoke passed.
- Final studio-path certification passed 11/11 focused tests across Edit, Composition, Motion Graph/VFX, Color, timeline preview invalidation, rendering diagnostics, and performance.
- Imported still-image -> V1 clip -> timeline -> MP4 render was verified headlessly with decoded source-color quadrant preservation.
- Color Node Graph drag ownership now prevents node drags from activating marquee/multi-selection; media drag feedback is compact.
- The two previously failing market-gate shards were corrected and passed on the final test binary.
- Fresh silent installation passed with exit code 0.
- Installed Oraphim remained running for 20 seconds in a normal launch smoke; the prior missing-integrity-manifest startup failure is fixed.
- The release executable is Windows GUI subsystem, so normal Explorer/shortcut launch does not allocate a console window.
- The payload is RSA-PSS-SHA256 integrity sealed; Authenticode signing is not yet available for this beta.

## System requirements

- Windows 10/11 64-bit
- Vulkan-capable GPU
- 8 GB RAM minimum
- SSD recommended

This beta installer is currently unsigned, so Windows may display an **Unknown publisher** or SmartScreen warning.
