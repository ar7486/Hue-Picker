# Hue-Picker
Just a simple tool to help clients pick colors in real time
# FlexiLogo — Project Description

## Story

When clients don't know what color to pick, designers export endless new versions.
FlexiLogo lets clients pick any color live from one file. Problem solved.

## Use case

Send a single file. The client previews colors, chooses instantly, no technical skills required.

## Designer — Prepare a single-file HTML

1. Collect your `Mylogo.svg` and water-drop PNG.
2. Convert the PNG to a Base64 data URI (use any image-to-base64 tool).
3. Open `Mylogo.svg` in a text editor and remove hardcoded color fills.
4. Group hanger paths under an element with id `hanger`.(Open Mylogo.svg in a text editor (VS Code).
    Find the <path> (or <g> / <line>) that represents the hanger.
    Copy-paste that path into id="hanger" section in my code.)
5. Replace the PNG `href` with the PNG Base64 data URI inside the SVG `<image>`.
6. Embed the modified SVG into the HTML template with the color-picker code.
7. Save as `index.html` and test by double-clicking it in a browser.

## Designer — Alternative: single-folder share

1. Put `index.html`, `Mylogo.svg`, and PNG in one folder.
2. Tell the client to double-click `index.html` to open the viewer.

## Client — How to use

1. Double-click `index.html` to open in any browser.
2. Use the color picker to change the logo color live.
3. If needed, tell the designer the chosen hex code.
4. Optionally, right-click the image and save the recolored SVG.

## Optional: Host online (one-click link)

1. Push `index.html` to a GitHub repo.
2. Enable GitHub Pages to serve the file as a web link.
3. Share the link instead of any files.

## Files you’ll deliver

* A folder containing `index.html`, `Mylogo.svg`, and PNG.
