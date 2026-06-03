# Version 1.1.8

> [!fix] Empty Space When Editing (for real this time)  
> The callout preview's shadow-DOM body inherited a min-height from Obsidian, leaving a tall empty area below short callouts. Its box metrics are now reset so the preview hugs the callout.

# Version 1.1.7

> [!fix] Less Empty Space When Editing  
> The callout preview no longer leaves a large empty area below short callouts. The fix now covers the full reading-view container chain, so it works on the default theme too.

# Version 1.1.6

> [!fix] Aligned Section Headings  
> Section headings on the edit screen now line up with the text beneath them instead of being indented by some themes.

# Version 1.1.5

> [!new] Delete Custom Callouts  
> Custom callouts you created now have a clearly-labeled "Delete Callout" button (with a confirm step) at the bottom of their edit screen.

> [!fix] Tighter Edit Screen  
> The callout preview no longer reserves a large fixed height, so editing a callout no longer leaves a big empty gap.

# Version 1.1.4

> [!fix] Callout List Buttons Clickable Again  
> The edit and insert buttons in the "Manage Callouts" list now respond to clicks on the icon itself, not just the surrounding area.

# Version 1.1.3

> [!fix] Tidier Callout List Buttons  
> The edit and insert buttons in the "Manage Callouts" list are now borderless icon buttons instead of heavy filled boxes.

# Version 1.1.2

> [!fix] Modern Obsidian Color Compatibility  
> Callout colors are now written as 6-digit hex codes instead of `r, g, b` triplets, so picking a color works again on current Obsidian versions. Colors saved with older versions are upgraded automatically.

# Version 1.1.1

> [!new] Export Callouts as CSS  
> There's now a button to copy your callout changes.

> [!fix] Callout Previews  
> Previews are back!
>
> Thank you, [**@alythobani**](https://github.com/alythobani)!

> [!fix] Settings Pane (Mobile)  
> It's moved slightly to accomodate the updated Obsidian mobile layout.

# Version 1.1.0

> [!new] In-App Changelogs  
> Learn about plugin changes and new features straight from the horse's mouth.

> [!new] Insert Callouts  
> Goodbye to the days of needing to type callouts by hand, and hello to having more ways to suit your workflow. You now have the option to insert callouts directly from the "Manage Callouts" pane!
>
> Thank you, [**@decheine**](https://github.com/decheine)!

> [!new] Color Dropdown  
> Pick from a nifty dropdown instead of memorizing color values.
>
> Thank you, [**@decheine**](https://github.com/decheine)!

> [!new] Rename Callouts  
> You can now rename your custom callouts.

> [!fix] More Robust Callout Detection  
> The code monkey (developer) learned a couple new tricks, and now Callout Manager can detect Obsidian callouts on all platforms and versions without resorting to fallback lists.

> [!fix] Integration with Completr  
> You can now use [Completr](obsidian://show-plugin?id=obsidian-completr) to autocomplete callouts!

# Version 1.0.1
The first release available on Obsidian's community plugin browser!

# Version 1.0.0

> [!new] Callout Customization  
> Change callouts to your heart's content!

> [!new] Automatic Detection  
> Browse and search through your one and only list of available callouts.
