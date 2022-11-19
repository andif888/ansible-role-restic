# ansible-role-restic

Installs Restic backup utility into /usr/local/bin

## Table of content

- [Default Variables](#default-variables)
  - [restic_download_url](#restic_download_url)
  - [restic_file_group](#restic_file_group)
  - [restic_file_mode](#restic_file_mode)
  - [restic_file_owner](#restic_file_owner)
  - [restic_filename_exe](#restic_filename_exe)
  - [restic_filename_zip](#restic_filename_zip)
  - [restic_install_folder](#restic_install_folder)
  - [restic_version](#restic_version)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### restic_download_url

#### Default value

```YAML
restic_download_url: https://github.com/restic/restic/releases/download/v{{ restic_version
  }}/restic_{{ restic_version }}_linux_amd64.bz2
```

### restic_file_group

#### Default value

```YAML
restic_file_group: root
```

### restic_file_mode

#### Default value

```YAML
restic_file_mode: 0775
```

### restic_file_owner

#### Default value

```YAML
restic_file_owner: root
```

### restic_filename_exe

#### Default value

```YAML
restic_filename_exe: restic_{{ restic_version }}_linux_amd64
```

### restic_filename_zip

#### Default value

```YAML
restic_filename_zip: restic_{{ restic_version }}_linux_amd64.bz2
```

### restic_install_folder

#### Default value

```YAML
restic_install_folder: /usr/local/bin
```

### restic_version

#### Default value

```YAML
restic_version: 0.14.0
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
