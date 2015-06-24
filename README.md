# PopupExtended
A more feature rich ArcGIS javascript api Popup.

The current ArcGIS popup didn't do everything I needed, so subclassed it and added some features.

Popup extended allows the following:
- Implements the existing functionality of a popup
- Multiple popups can be opened at once
- Ability to drag a popup from the title bar off it's anchored point and have it stay on screen
- Ability to resize a popup once it's been dragged off it's anchor
- Easier way of adding custom actions to the actions bar through a PopupTemplate or the PopupExtended constructor.
- Can use multiple themes on the one map. A theme class can be set in the PopupExtended constructor or in a PopupTemplate that applies to a layer or individual feature.

Check out the code to see what options are available.

A crude example is here:
http://popupextended.azurewebsites.net/


