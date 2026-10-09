# Ultimate Gorilla Expedition

**Status: design + source scaffold only; not a playable or publishable release.**

A solo Gorilla Tag expedition that opens in immediate crossover chaos: a truck rolls into base camp, collectible supplies fall from above, a cookie-production counter accelerates, and an unpaid bill appears. The player uses Gorilla Tag's arm-based movement to explore and complete suspicious tasks.

## Important truth about this build
This folder is not a finished game mod. The current workspace could not connect to Melty and does not contain the user's installed Windows game folders, so I could not inspect Gorilla Tag's actual version/loader, read the companion games' installed content, launch the host game, capture real gameplay, run Melty's recipe checks, or publish. No stand-ins are presented as the actual games. The source files below document the intended vertical slice and the integration work still required.

## Intended real-game integration
- **Primary host:** Gorilla Tag. Its real game must launch and remain the game the player controls.
- **Companions required:** Among Us, Bills Must Be Paid Demo, Euro Truck Simulator 2, Cookie Clicker, Fortnite, and Gorilla Tag's own installed files. Companion game files must be read from the player's own installed copies; none are redistributed here.
- **Among Us:** real task/crew concepts and content, subject to technical and licensing validation.
- **Bills Must Be Paid Demo:** actual content and mechanics read from its installed folder; exact executable/data format must be inspected first.
- **Euro Truck Simulator 2:** actual truck/route content; its supported mod content and data formats must be inspected first.
- **Cookie Clicker:** actual cookie/upgrade content; its installed distribution and data format must be inspected first.
- **Fortnite:** companion-only content read from the player's installed copy. Never launch it with a mod or modify its client.
- **Gorilla Tag:** real arm locomotion, host environment and character.

## First playable slice target
1. Start Gorilla Tag through its normal launch route.
2. At base camp, show a truck-arrival event, falling collectible supplies, a rapidly increasing cookie total, and a bill due.
3. Let the player physically reach and complete one suspicious task.
4. Verify every cross-game reference resolves to actual files in the player's installed copies; if a game's data cannot legally or technically be read, stop and document the blocker rather than substitute a look-alike.

## Credits, license, remixing
Not set. No permission to remix or redistribute has been inferred. Before listing, establish credits, project license, and whether remixing is allowed. This scaffold contains no game assets.
