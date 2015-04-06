1. Install cygport via Cygwin's installer.

2. Download source and perform all build steps.

  ```
    $ cygport nix/nix.cygport download all
  ```

  If cygport warns about missing dependencies, install them via Cygwin's installer and run all build steps again.

  ```
    $ cygport nix/nix.cygport all
  ```

3. Currently, none of our cygports needs a postinstall script; it is enough to unpack to ``/``.

  ```
    $ tar xvfJ nix/nix-1.8-1.x86_64/dist/nix/nix-1.8-1.tar.xz -C /
  ```
