# Chuck Dillinger — Personal Business Card

This repair starts from the **original working website** and makes only the requested content changes. The original CSS and JavaScript are preserved.

## Edit the site

Open `index.html` in a plain-text editor (such as TextEdit in plain-text mode or VS Code).

- **Name:** Search for `Chuck Dillinger`.
- **Home menu:** Search for `<!-- HOME:`.
- **About Me:** Search for `<!-- ABOUT ME:`.
- **Projects:** Search for `<!-- PROJECTS:`.
- **Phone/email:** Search for `tel:+14169493340` and `mailto:chuck@dillinger.ca`.
- **Background images:** Search for `maker-studio.jpg` and `maker-workspace.jpg` in the `<style>` section.
- **Profile photo:** Replace `headshot.png` with a photo of the same filename.
- **Contact download:** Replace `contact.vcf` if you want to change its contents.

Keep all files together in the same folder when uploading to GitHub Pages.

## Color and portrait adjustments

Near the end of the `<style>` section in `index.html`, find the heading
`CUSTOMIZATION — COLORFUL BUTTONS & PORTRAIT SPACING`.

- `#home .hero .portrait` controls the size of the home photograph.
- `#home .hero` `padding-top` moves the portrait higher/lower.
- `#home .hero h1` `margin-top` controls the open gap before the name.
- `.orb` controls the circular contact buttons.
- `.navitem` and `.navicon` control the menu rows and colorful icons.
- `.whatitem` controls the six About Me tiles.
- `.projecticon` controls the colorful project icons.

The underlying HTML, navigation JavaScript and contact links are unchanged.

## Adjust the Home portrait and text gap

In `index.html`, search for `HOME PORTRAIT / NAME / TAGLINE SPACING`. Change `margin-top` under `#home .hero h1` to make the gap larger or smaller. The name, role and tagline are now grouped in the Home hero.

## Fun icons
Project icons and About Me technology badges now use colourful illustrated symbols. Edit the icons by searching for `icon-illustration` and `tech-glyph` in `index.html`. Change colours in the `FUN ILLUSTRATED ICONS` CSS section.

## About Me technology icons
The iOS Apple logo, Swift bird logos (Swift and SwiftUI), and 3D Design Benchy are embedded SVGs in `index.html`, not emoji. Search for `ABOUT ME — TECHNOLOGY ICONS` to change their sizes. Xcode was not modified.

## Latest change — Home buttons moved down
The Home contact buttons and three menu cards now sit closer to the bottom of the screen. Edit the commented `HOME — LOWER THE CONTACT BUTTONS` section in `index.html` to fine-tune the spacing. All other pages are unchanged.
