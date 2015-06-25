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
- Cater for small/mobile popups. No need to use a different object (eg: PopupMobile) to handle small screens. Just hides the content pane when in small mode and adds a small class so it can be styled differently from normal ones easily.

Check out the code to see options and their use.

I only tested this for the use cases I had at the moment...I didn't try it out with media, attachments or anything particularly funky. Theoretically it should work the same as a normal popup...theoretically :).


A crude example is here:
http://popupextended.azurewebsites.net/


