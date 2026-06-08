# Prompt — 19-glass-ui-suite

The original prompt used to generate this motion graphic:

Glass Music Player Duration: 18 seconds

A dark canvas, the kind of ambient dark that belongs behind music — deep navy to black, a single large soft color bloom that shifts slowly in hue over the duration of the scene, cycling from blue to purple to teal, representing the mood of the music. The bloom is the only background element, centered, large, filling half the canvas. Everything glass will sit above it.

A glass card materializes at canvas center — portrait proportion, 280×380px, border-radius 24px, the most sophisticated glass surface of any scene so far. Backdrop blur 28px, white tint 8%, a stronger inset rim highlight — 2px white at 50% opacity along the top edge only, thinner 0.5px along the other three edges. The card catches the shifting background bloom and its tint shifts with it — the glass is not a neutral white, it is tinted by whatever color lives behind it at that moment.

Inside the card, an album artwork area fills the top 55% — a rounded rectangle within the glass, its own backdrop blur surface showing the background bloom as abstract color, no actual artwork, just color through glass. A song title fades in word by word below the artwork. An artist name fades in beneath it in lighter weight.

A progress bar appears — a thin glass track, a filled glass pill as the playhead position indicator. The playhead travels rightward across the track at a steady pace, the filled portion of the track brightening as it fills. A timestamp counts upward on the left, counts downward on the right, both in sync with the playhead.

Three glass control buttons materialize in a row at the bottom — backward, play/pause, forward. Each a glass circle, 44px, the same frosted treatment. The play button is slightly larger — 52px — elevated in importance. A cursor taps it. It compresses on tap — scale 0.88 — and springs back. The playhead continues moving. The background bloom continues shifting color. The glass card tint shifts with it.

Scene 4 — Glass Settings Panel Duration: 16 seconds

A dark system-level canvas — the kind of dark that belongs to an operating system preferences panel. A subtle texture implied by the glass surfaces rather than the background. Two soft background blobs — both cool toned, blue and teal, positioned to create a generally cool ambient light behind the glass.

A glass panel slides in from the right edge — a tall side panel, 320px wide, full canvas height minus 48px top and bottom, border-radius 20px. It enters with a smooth ease-out deceleration, no spring — system panels don't bounce. Frosted glass: backdrop blur 20px, a slightly darker tint than previous scenes, white at 8% opacity, giving it a more serious, less playful quality. The panel settles at the right third of the canvas.

Inside the panel, a title fades in at the top — settings section name, 16px white weight 500. Below it, setting rows materialize one at a time with a tight top-to-bottom stagger — each row a glass inset strip, slightly darker than the panel surface, containing a label on the left and a control on the right. The controls vary: a glass toggle switch, a glass dropdown pill, a glass slider, another toggle, a glass segmented control with three options. Each control appears with its row.

The cursor enters and interacts with each control in sequence. The toggle flips — its thumb slides with a spring, the track color transitioning. The dropdown opens — a glass menu appearing below it, options listed, one selected, menu closing. The slider drags — the filled track growing. The segmented control taps — one segment brightening, the others dimming, the selection state clear. Each interaction is crisp and physical. After the final interaction, the panel holds with all controls in their new states.

Scene 5 — Glass Tooltip Cascade Duration: 12 seconds

A dark canvas with a row of five glass icon buttons arranged horizontally at vertical center — each a 48px glass circle, frosted surface, a Tabler icon inside. They sit still, evenly spaced, the background blobs drifting slowly behind them.

A cursor enters from the left and begins moving rightward across the row of icons. As the cursor passes over each icon, a glass tooltip materializes above it — a small glass pill, border-radius 999px, backdrop blur 12px, white tint 10%, inset rim, containing a short label in white 12px text. The tooltip appears with a spring pop — scaling from 0.7 to 1.05 to 1.0 — and disappears with a fast scale-down and fade as the cursor moves to the next icon.

The icon being hovered lifts slightly — translateY -6px, scale 1.1 — and its glass surface brightens. As the cursor leaves, it settles back through a spring. The tooltip for the departing icon scales down and fades as the tooltip for the arriving icon springs up. The two tooltips are never visible simultaneously — a clean handoff, one fading as the next appears.

The cursor reaches the fifth icon and pauses. The tooltip holds above it — longer than the others. The icon stays lifted. The cursor clicks. The icon's glass surface flashes bright for 2 frames — an inset highlight spike — then the icon compresses to scale 0.88 and springs back. The tooltip fades. The cursor moves away. All five icons settle to their resting state.

Scene 6 — Glass Onboarding Modal Duration: 20 seconds

A canvas that begins fully light — a blurred product interface behind a dark overlay. The overlay is semi-transparent black at 50% opacity, dimming the background. A glass modal sits above the overlay at canvas center — the most prominent glass element in the frame, catching the dim light coming through from the interface behind the overlay.

The modal enters with a spring scale-in from 0.88 to 1.04 to 1.0 over 16 frames, combined with a translateY from +16px to 0. It is a tall centered card — 480×520px, border-radius 24px, backdrop blur 32px, white tint 14%, strong inset rim highlighting the top edge at 55% opacity and the other three edges at 25%. It feels like a piece of illuminated glass held up to a window.

Inside, a large icon materializes first — a 64px glass circle, its own frosted surface, centered at the top of the modal. Below it, a headline builds word by word. A descriptor paragraph fades in. Three glass feature rows appear below the description — each row a glass inset strip with an icon on the left and two lines of text beside it, appearing with a 12-frame stagger.

At the bottom, two glass buttons sit side by side — a secondary ghost button and a primary button. The primary button's glass surface carries a subtle blue tint at 20% opacity, distinguishing it from the neutral-frosted secondary. A cursor clicks the primary button. It compresses and springs back. The modal scales down and fades simultaneously — both the scale and opacity animating together over 12 frames. The overlay fades. The background interface returns to full brightness. The modal is gone. The product is ready.

Scene 7 — Glass Context Menu Duration: 12 seconds

A dark canvas with a populated interface behind glass — enough visual complexity in the background that the context menu's frosted surface has rich material to refract. The background is a dark product UI, blurred, with color blobs drifting across it.

A cursor right-clicks at a specific point on the canvas — a brief visual indication of the click: a single frame scale-down of the cursor tip. The context menu materializes immediately at the cursor's position — not at canvas center, but exactly where the click happened, offset so the menu doesn't clip the canvas edge. The menu is a glass card — 200px wide, variable height depending on the number of items, border-radius 14px, backdrop blur 20px, white tint 10%, inset rim highlight. It scales in from 0.85 to 1.02 to 1.0 from the click point as the transform origin — the menu growing outward from where it was summoned.

Menu items fade in top to bottom with a 4-frame stagger — eight items total, each a row with an icon on the left and a label. A thin glass divider appears between item 3 and item 4, and between item 6 and item 7 — separating the groups. The cursor moves into the menu. The hovered item highlights — its glass surface brightening, a selection tint appearing. The cursor moves down through the items, each one lighting up and dimming as the cursor passes. A destructive item at the bottom — the last item before the final divider — highlights in a red tint rather than white when hovered.

The cursor clicks a non-destructive item. The menu scales back down toward the click point and fades out over 8 frames. Gone.

Scene 8 — Glass Lock Screen Duration: 20 seconds

A full-canvas phone screen — portrait 9:16. A rich wallpaper fills the entire frame — an abstract colorful scene, vivid and detailed, slightly animated with slow color shifts throughout the duration. This is what the glass will work against.

The lock screen assembles itself from top to bottom. A glass status ba

---

Glass Onboarding Modal
Duration: 20 seconds

A canvas that begins fully light — a blurred product interface behind a dark overlay. The overlay is semi-transparent black at 50% opacity, dimming the background. A glass modal sits above the overlay at canvas center — the most prominent glass element in the frame, catching the dim light coming through from the interface behind the overlay.
The modal enters with a spring scale-in from 0.88 to 1.04 to 1.0 over 16 frames, combined with a translateY from +16px to 0. It is a tall centered card — 480×520px, border-radius 24px, backdrop blur 32px, white tint 14%, strong inset rim highlighting the top edge at 55% opacity and the other three edges at 25%. It feels like a piece of illuminated glass held up to a window.
Inside, a large icon materializes first — a 64px glass circle, its own frosted surface, centered at the top of the modal. Below it, a headline builds word by word. A descriptor paragraph fades in. Three glass feature rows appear below the description — each row a glass inset strip with an icon on the left and two lines of text beside it, appearing with a 12-frame stagger.
At the bottom, two glass buttons sit side by side — a secondary ghost button and a primary button. The primary button's glass surface carries a subtle blue tint at 20% opacity, distinguishing it from the neutral-frosted secondary. A cursor clicks the primary button. It compresses and springs back. The modal scales down and fades simultaneously — both the scale and opacity animating together over 12 frames. The overlay fades. The background interface returns to full brightness. The modal is gone. The product is ready.
