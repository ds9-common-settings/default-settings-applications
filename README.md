# default-settings-applications
Application settings (for example Qmmp, gmusicbrowser,...)

## Currently contains

* A gltron.desktop file to make it appear in kicker's since Debian stable has
  no gltron.desktop. This has been taken from the current Debian unstable
  release (0.70final-12.1)

* A synaptic-kde.desktop file that removes X-KDE-SubstituteUID=yes to correct
  pkexec usage

* A kdesurc to make kdesudo use sudo instead of su since we do not configure su
  on Netrunner Debian

* Custom layout for gmusicbrowser

* Configuration for audacious. The plugin registry contains hard coded paths
  to plugins, which must be configured at build time for each architecture
