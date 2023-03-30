# v0.4.0

## MAJOR

-   added a new "run as administartor" mode for the FSdesktop input processor (which has been extracted into a separate process) to improve compatibiliy particularly with application that, themselves, run with elevated privileges.
-   added a slider to the core application to adjust the ingame panel's UI scale

---

# v0.3.0

## MAJOR

-   improved input recognition on Windows 11 machines
-   added selector for input processing speed to core application's settings tab
-   moved ingame panel settings (background color, framerate, and quality controls) to "burger menu"

## MINOR

-   changed ingame panel's stream quality default setting to "high"
-   improved ingame panel tab selector
-   migrated the entire ingame panel GUI from vanilla javascript to react

---

# v0.2.0

## MAJOR

-   added mouse wheel support
-   added a switch to select between a white and a black background for the streamed window
-   improved the layout of the window picker for the default size of FSdesktop's ingame panel in VR

## MINOR

-   added a settings page to the main application
-   added a dropdown menu to select the active log level and also access the log folder with a click of a button
-   added a button to restart the tour
-   migrated the entire server GUI from vanilla javascript to react

---

# v0.1.0

## MAJOR

-   improved the rendering canvas so that it will always fit the available screen real estate "from inside", i.e. users won't see any vertical overflow anymore
-   store resolution and refresh rate settings to "survive" across sessions
-   hide resolution and refresh rate selection buttons by default, reveal only on hover
-   added an update checker which checks for available updates for FSdesktop
-   hide serial number once submitted to prevent unintentional leaking by content creators or people seeking advice etc.

## MINOR

-   make FSdesktop trial period "version-based", i.e. the trial period will reset for every new version
-   show version number in title bar
-   remove default application menu bar
-   changed default server port to less commenly used port 9670
-   catch any unexpected errors on the process level and show a user-friendly dialog with a hint to restart FSdesktop and on how to get support

---

# v0.0.2

-   HOTFIX: updated installer GUID to allow for a separate installation when FSKneeboard is already installed

---

# v0.0.1

Initial Early Access Release
