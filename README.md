# plasmoid-digital-clock-debarred
Fork of KDE Digital Clock plasmoid without the seperator bar added in 6.2-6.3.

The original widget is available here:
https://github.com/KDE/plasma-workspace/blob/master/applets/digital-clock/package/contents/ui/DigitalClock.qml

The only changes made are:
	* removing the new seperator bar that appeared when the date was shown next to the time on one line, as suggested by https://discuss.kde.org/u/zeekzag.
	* Updating the metadata to exist a separate package.

After installing into ~/.local/share/plasma/plasmoids/us.rbrent.digitalclock, right click an existing Digital Clock plasmoid and select "Show Alternatives" to replace.
