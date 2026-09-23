# LoadingIndicator

A [Spinner](./spinner) that scales by a percentage instead of a size step. Use
`Spinner` unless you need a size between or beyond its steps.

<ComponentPreview name="LoadingIndicator-ChartPanel" />

## Behavior

### Scale

`scale` is a percentage of the default 16px spinner: `50` draws it at 8px and
`150` at 24px. It is applied with the CSS `scale` property, so the spinner's
layout box stays 16px and surrounding content does not move. The default is
`100`.

### Color

The spinner takes the text color of its parent. Set a `text-ink-*` class on
the indicator or a wrapper to change it.

## Accessibility

The spinner has `role="status"` and the label "Loading".

<!-- @include: ./LoadingIndicator.api.md -->
