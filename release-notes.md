# Oraphim 1.0.0 Public Beta

Professional video editing, motion graphics, compositing, color, and procedural VFX in one native Windows application.

## Windows x64 package

Download `Oraphim-1.0.0-beta-Windows-x64.zip`.
The ZIP contains exactly one file: `OraphimSetup.exe`.

ZIP SHA-256: `7d9773d01dd1030aac8bb5264ae6fc72443aa36716522d70b956ca08388555f1`

Installer SHA-256: `92dfea3da541261de74462f3647137c35c958e10d94460309058738c39c081e0`

## Release certification

- Fresh Windows x64 Release build passed.
- Portable runtime validation passed for 517 staged files.
- Headless MCP / OpenColorIO smoke passed.
- Workspace UI Contract, Edit Workspace, and Timeline Preview Policy tests passed.
- The two previously failing market-gate shards were corrected and passed on the final test binary.
- Fresh silent installation passed with exit code 0.`r`n- Installed Oraphim remained running for 20 seconds in a normal launch smoke; the prior missing-integrity-manifest startup failure is fixed.`r`n- The release executable is Windows GUI subsystem, so normal Explorer/shortcut launch does not allocate a console window.`r`n- The payload is RSA-PSS-SHA256 integrity sealed; Authenticode signing is not yet available for this beta.

## System requirements

- Windows 10/11 64-bit
- Vulkan-capable GPU
- 8 GB RAM minimum
- SSD recommended

This beta installer is currently unsigned, so Windows may display an **Unknown publisher** or SmartScreen warning.
