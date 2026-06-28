# Accessibility

Accessible software is better software. Nerrowake interfaces should be usable by
people with different devices, abilities, and contexts.

## Baseline Expectations

- use semantic HTML when building web interfaces
- provide keyboard access for interactive controls
- preserve visible focus states
- provide text alternatives for meaningful images
- use sufficient color contrast
- avoid relying on color alone
- keep motion purposeful and reducible
- write clear labels and error messages

## Forms

Forms should include labels, helpful validation, and clear error states. Errors
should explain what happened and how to fix it.

## Dashboards

Dashboards should support scanning and comparison without requiring perfect
vision or pointer precision. Use clear hierarchy, readable tables, and accessible
chart alternatives where practical.

## Testing

Accessibility review may include:

- keyboard navigation
- screen reader checks
- color contrast checks
- reduced motion checks
- browser zoom checks
- mobile layout checks

UI pull requests should include accessibility notes when the change affects
interaction, navigation, content structure, or visual state.
