Stats Preview Card Component This project is a solution to the "Stats preview card component" challenge. It's a single-page component demonstrating a common landing page layout: a 50/50 split between text content and an image.

The key feature is the vibrant purple color filter (matching the "insights" text color) applied to the image. This effect is achieved purely with CSS using:

A ::before pseudo-element as an overlay.

The background-color property set to #aa5cdb.

The opacity and mix-blend-mode: multiply properties to blend the color with the image underneath.