# Waybar Project Instructions

## CSS Ordering

- In `style.css`, keep module-related selectors in the same visual order as the bar configuration in `config.jsonc`: left modules, center modules, right modules, then overlay modules.
- Do not alphabetize Waybar module selectors when ordering them would conflict with the configured bar order.
- Use single-line `/* MARK: ... */` comments in `style.css` for the major bar regions and supporting UI so the file is easy to navigate.
