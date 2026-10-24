# E-Waste Recycling Plant, Chennai

A private project website for LAN & Family. It is password protected.

Live site: https://vigneshannamalai-ai.github.io/E-waste-Recycling-Plant-/

`index.html` holds the page content encrypted (AES-256-GCM, with the key derived from the password using PBKDF2-SHA256 at 600,000 iterations). The page decrypts in the browser only after the correct password is entered.

## Plant drawings

The architectural drawing set (revision P6, 11 sheets: site plan, fire-safety plan, main hall and machine layout, admin floors, refinery, utilities, raw e-waste store and canteen) is in the `drawings/` folder. Each sheet image and the combined PDF are stored encrypted (`.enc`, AES-256-GCM, same password and key derivation as the proposal) and are decrypted in the browser after unlocking. The proposal's Plant section links to it.

Live page: https://vigneshannamalai-ai.github.io/E-waste-Recycling-Plant-/drawings/

## Garbage Recycling Plant, Chennai

A second proposal site, in the `garbage/` folder, built in the same format and protected the same way.

Live site: https://vigneshannamalai-ai.github.io/E-waste-Recycling-Plant-/garbage/

## Medical Waste Recycling Plant, Chennai

A third proposal site, in the `medical/` folder, built in the same format and protected the same way.

Live site: https://vigneshannamalai-ai.github.io/E-waste-Recycling-Plant-/medical/
