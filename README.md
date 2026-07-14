# File Hosting

This repository stores Windows artifacts used for testing and tooling. Files are
grouped by artifact type so that the repository root stays easy to navigate.

## Structure

```text
artifacts/
└── windows/
    ├── archives/      Compressed packages (`.zip`)
    ├── encoded/       Text-encoded artifacts
    ├── executables/   Windows executables (`.exe`)
    └── libraries/     Windows libraries (`.dll`)
```

## Artifact inventory

### Archives

- [Executables.zip](artifacts/windows/archives/Executables.zip)
- [HelloANDLHF.zip](artifacts/windows/archives/HelloANDLHF.zip)
- [Release.zip](artifacts/windows/archives/Release.zip)
- [Rubeus.zip](artifacts/windows/archives/Rubeus.zip)
- [SharpHound.zip](artifacts/windows/archives/SharpHound.zip)
- [SharpSuccessor.zip](artifacts/windows/archives/SharpSuccessor.zip)
- [Winpeas-part1-password-2026.zip](artifacts/windows/archives/Winpeas-part1-password-2026.zip)
- [hello_world_quiet_pass_2026.zip](artifacts/windows/archives/hello_world_quiet_pass_2026.zip)
- [miniserver_pass_2025.zip](artifacts/windows/archives/miniserver_pass_2025.zip)
- [poc.lnk.zip](artifacts/windows/archives/poc.lnk.zip)
- [winPEAS.bat-password-2026.zip](artifacts/windows/archives/winPEAS.bat-password-2026.zip)
- [winpeas-part2-password-2026.zip](artifacts/windows/archives/winpeas-part2-password-2026.zip)

### Encoded artifacts

- [LHF_x64.exe_B64.txt](artifacts/windows/encoded/LHF_x64.exe_B64.txt)

### Executables

- [Akagi64.exe](artifacts/windows/executables/Akagi64.exe)
- [CurrentUserAclHunter.exe](artifacts/windows/executables/CurrentUserAclHunter.exe)
- [SharpView.exe](artifacts/windows/executables/SharpView.exe)
- [SystemSettings.exe](artifacts/windows/executables/SystemSettings.exe)
- [TcbS4uAssignTokenVariant.exe](artifacts/windows/executables/TcbS4uAssignTokenVariant.exe)
- [TcbS4uAssignTokenVariant_low_mandatory_level.exe](artifacts/windows/executables/TcbS4uAssignTokenVariant_low_mandatory_level.exe)
- [explorer-path-test.exe](artifacts/windows/executables/explorer-path-test.exe)
- [hello_whoami.exe](artifacts/windows/executables/hello_whoami.exe)

### Libraries

- [WptsExtensions.dll](artifacts/windows/libraries/WptsExtensions.dll)
- [hello_world.dll](artifacts/windows/libraries/hello_world.dll)
- [hijackme.dll](artifacts/windows/libraries/hijackme.dll)

## Existing links

The filenames are unchanged, but artifacts formerly stored at the repository root
now live below `artifacts/windows/`. Update existing raw links by inserting the
appropriate directory before the filename. For example:

```text
SharpView.exe
artifacts/windows/executables/SharpView.exe
```

> **Safety:** Treat all hosted artifacts as untrusted. Inspect them in an isolated
> environment before execution.
