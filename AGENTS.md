# Hard Requirements

- **Autoscaling:** The layout MUST adapt to the viewport width and height. Grid cards MUST scale horizontally and vertically so the complete grid always fits inside the visible screen without horizontal or vertical scrolling.
- **Square grids:** Every grid card MUST remain a perfect square. The card size MUST be recalculated when the viewport changes or when sites are added or removed.
- **Uniform spacing:** The margin/gap between every grid card MUST be identical horizontally and vertically. No card may introduce extra spacing because of its content or intrinsic logo dimensions.
- **Logo sizing:** Each logo MUST scale proportionally with its card, remain fully visible, and stay centered both horizontally and vertically. Logos MUST NOT overflow, stretch, or determine the card size.
- **Dynamic site count:** Adding or removing a site MUST trigger the same fitting behavior automatically. Do not hard-code the current number of sites or a viewport-specific column count.
- **Viewport coverage:** The grid MUST use the available screen area efficiently while preserving square cards, uniform gaps, centered logos, and zero overflow.
