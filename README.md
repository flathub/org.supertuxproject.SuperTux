SuperTux Nightly Builds
-----------------------

Experimental SuperTux nightly builds for Linux are available via [FlatPak](https://flatpak.org/):

    sudo flatpak remote-add --no-gpg-verify supertux "https://gitlab.com/supertux/flatpak/-/jobs/artifacts/master/raw/build-flatpak-repo?job=build:flatpak"
    sudo flatpak install supertux org.supertuxproject.Supertux
