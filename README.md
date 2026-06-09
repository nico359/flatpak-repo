# Flatpak repo

So here you can find the flatpak repo to my vibe coded apps (and maybe some others as well). If you want to know more about each app, please see the respective Github page.
All of the apps aim to be mobile friendly for devices such as the Pine- or Furiphone.

Included as of now are:
- Expeneses: Expense Tracker which aims to be compatible with MyExpenses database
- SimpleSync: Very simple app to push/pull or sync local folders such as photos to a WebDAV instance like Nextcloud
- PinePal: Pinetime companion app. The main connection logic is borrowed/stolen from Watchmate but it should be a lot more reliable
- Speedometer: Simple speedometer app that displays speed in kmh or mph
- Loci: Turn-by-turn navigation app using libshumate tile renderer (like Gnome Maps) - very early development,

Apps not created by me:
- Tuta Mail: Regular Tuta Mail client but for arm64 because the Flathub version only has a x86_64 build
- Flexify: Workout tracker made with Flutter - developer was not interested in publishing on Flathub so I added it here

## Download

See the release section for the .flatpakrepo file https://github.com/nico359/flatpak-repo/releases
Please note that the description of the .flatpakrepo file might not always be up to date so take a look at the section above or the manifests itself to see which apps are included.

Alternatively you can also download the individual .flatpak bundles. Please keep in mind that they will not be automatically updated though.
To get a bundle you can go to the Actions tab https://github.com/nico359/flatpak-repo/actions and select the latest workflow run. Then scroll down a little bit to Artifacts and select the app and architecture you want.
You have to extract them first because they are uploaded as .zip file. Then you can install the .flatpak bundle.

## Credits

The Flatpak repo itself is built with a Flatter workflow so thanks a lot to Andy Holmes for creating this project https://github.com/andyholmes/flatter
