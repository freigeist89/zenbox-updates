# Zenbox Updates

Update-Feed für die Mac-App [Zenbox](https://www.thezenbox.de).

Dieses Repository enthält ausschließlich den Sparkle-Appcast. Die App selbst
ist nicht quelloffen; die Installationsdateien hängen an den Releases.

- Feed: https://freigeist89.github.io/zenbox-updates/appcast.xml
- Download der aktuellen Version: https://www.thezenbox.de

Der Appcast wird von `release.sh` im App-Repo erzeugt und ist mit einem
EdDSA-Schlüssel signiert. Sparkle installiert nur, was zum öffentlichen
Schlüssel in der App passt.
