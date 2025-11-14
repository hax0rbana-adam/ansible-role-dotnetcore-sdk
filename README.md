# Ansible Role for .NET Core (SDK) on Ubuntu

This ansible role will install .NET Core (SDK) on Ubuntu.

## Requirements

_None_

## Role Variables

_None_

## Dependencies

_None_

## Example Playbook

```
- hosts: dotnetcore
  roles:
    - { role: hax0rbana_adam.dotnetcore_sdk }
```

```
- hosts: dotnetcore
  roles:
    - role: hax0rbana_adam.dotnetcore_sdk
      dotnet_version: 8
      dotnet_distro_major_version: 12
      dotnet_distro_codename: bookworm
      dotnet_key_filename: microsoft.asc
      dotnet_key_checksum: sha256:2fa9c05d591a1582a9aba276272478c262e95ad00acf60eaee1644d93941e3c6
```

## License

MIT

## Author Information

Gunter Grodotzki <gunter@grodotzki.co.za>

## Maintainer Information

Adam <adam@hax0rbana.org>
