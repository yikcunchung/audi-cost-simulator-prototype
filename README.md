# Audi Cost Simulator (prototype)

An interaction demo of the Audi running cost simulator. It shows how the screen looks and responds, so the live tool can be compared with the design. It is not production code.

## Open it
Open `index.html` in a browser. There is nothing to install or build, and it works offline.

## Files
| File | What it is |
|---|---|
| `index.html` | The default page, as on the live tool |
| `index-cta-group.html` | Work in progress: result section with call-to-action buttons. Not the default. |
| `assets/` | Fonts, icons and model images |

## What you can try
- Set how many miles you drive a year.
- Answer the We Charge and THG questions, and move the sliders to show where and how often you charge.
- Change the petrol and diesel prices used for the comparison. The Reset button sets the sliders and prices back.
- Pick a model and powertrain next to the result. The car image changes.
- Click the (i) buttons for an explanation. `Esc` or a click outside closes it.
- Open the FAQ rows (one at a time).
- Make the window narrower than 1024 px to see the result bar stick to the bottom of the screen.

## Design reference
Figma, page `[All] Ready for Dev`, section "Cost" (six frames: 320, 375, 768, 1024, 1440, 1920).

## Good to know
- Colours, type and spacing come from the DS3 Web UI Kit 2.1 tokens. They are the `--sys-*` custom properties at the top of the file; change a value there, not in the rules below.
- Copy is English (UK).
- The calculation logic is simplified and not the production logic. Accessibility is out of scope.
- The top bar imitates the live Audi header for context.
