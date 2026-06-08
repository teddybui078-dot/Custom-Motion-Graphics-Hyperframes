# Prompt — 15-glass-dock-magnify

The original prompt used to generate this motion graphic:

Liquid Glass Dock — Hover Magnification Duration: 15 seconds

A dark cinematic canvas — a deep layered gradient from near-black purple 
#0f0c29 through midnight blue 
#302b63 to dark indigo 
#24243e. Four large soft color blobs drift slowly across the background throughout the entire scene — a purple bloom drifting from upper left, a teal bloom drifting from lower right, a pink-coral bloom sitting upper right, a cyan bloom sitting lower center. All blobs are blurred to pure softness, no hard edges, moving at a pace so slow the movement is felt rather than seen. The background is the reason the glass works — it is rich, colorful, and alive behind every surface.

The dock enters from below the canvas bottom edge. It slides upward with a spring — traveling fast, decelerating sharply, overshooting its resting position by 10px above center-bottom of the frame, bouncing back through two oscillations, settling. The dock is a frosted glass pill — backdrop blur 20px, white tint at 10% opacity, an inset highlight stroke along the top and left edges at 40% white opacity creating a physical rim of caught light, a deep drop shadow below at 50% black opacity. The dock pill itself has a border-radius of 28px. It feels like a piece of frosted acrylic floating above the background.

Inside the dock, eight app icons sit in a row with a thin vertical glass divider between icon 5 and icon 6 — a 1px frosted separator, the same glass treatment as the dock itself. Each icon is a 56×56px rounded square — border-radius 14px — with its own individual glass surface: a colored gradient fill visible through the frosting, a top-edge specular highlight as a semi-transparent white gradient covering the upper 45% of the icon, an inset border rim. Each icon has a small white dot beneath it indicating it is open.

The icons appear inside the dock one at a time after the dock settles — springing in left to right, each scaling from 0 to 1.06 to 1.0 with a spring pop, 6 frames between each. All eight icons placed within 1.5 seconds of the dock landing.

A cursor materializes at the left edge of the canvas. It is a precise macOS-style arrow cursor — white with a thin black outline, crisp, unmistakably an OS cursor. It drifts rightward toward the dock at a natural human pace — not perfectly linear, a slight curve in its path, the way a real hand moves a mouse.

As the cursor approaches the dock, the dock itself subtly brightens — its white tint increasing from 10% to 14% opacity, the inset highlight sharpening slightly. The cursor is close. The dock knows.

The cursor reaches the third icon. The magnification fires:

The hovered icon lifts — translateY -22px and scale 1.32 simultaneously, spring easing cubic-bezier(0.175, 0.885, 0.32, 2.2), the overshoot carrying it 3px past the target height before settling. Its glass surface brightens — the specular highlight intensifying, the inset rim flashing to 65% opacity for 3 frames then settling back to 50%. A label materializes above the icon — the app name, small white text, weight 500, fading in over 8 frames exactly as the icon reaches peak height.

Simultaneously, the two adjacent icons on each side respond with diminishing magnification — icons at distance 1 lift to translateY -10px and scale 1.15, icons at distance 2 lift to translateY -4px and scale 1.06. The magnification wave falls off cleanly with distance. Icons at distance 3 and beyond do not move. The entire dock reads as a physical surface under a gravitational pull centered on the cursor position — a wave of influence, physically motivated.

The cursor drifts rightward to the fifth icon. The magnification wave follows — the new hovered icon lifting to full height, the previous icons falling back to rest through the spring easing, the new neighbors lifting in sympathy. The label swaps — the previous app name fading out as the hovered icon descends, the new label fading in as the new icon rises. The cursor moves to icon six. Then icon seven. The wave travels across the dock, each transfer a smooth handoff of magnification energy from one icon to the next.

The cursor moves away from the dock entirely — drifting upward off the dock surface. All icons settle back to their resting positions simultaneously, each falling through the spring easing at slightly different rates because they were at different magnification levels when the cursor left. The smallest-magnification icons settle first, the most-magnified icon settles last. The dock returns to its resting state — eight flat icons, one lit dot beneath each, the frosted pill sitting still above the drifting background blobs.

The cursor fades out. The dock holds for two seconds — the background blobs still drifting, the glass surface still catching their color as they move beneath it. The scene ends on stillness.
create this using hyperframes
