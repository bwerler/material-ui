---
title: Fab React component
components: Fab
githubLabel:
  component: Fab
materialDesign: https://material.io/components/buttons-floating-action-button
---

# Floating action button

<p class="description">A floating action button (FAB) performs the primary, or most common, action on a screen.</p>

A [floating action button](https://material.io/design/components/buttons-floating-action-button.html) appears in front of all screen content, typically as a circular shape with an icon in its center. Il existe deux types de FAB: régulier et étendu.

Utilisez un FAB uniquement si c'est le moyen le plus approprié pour présenter l'action principale d'un écran. Only one component is recommended per screen to represent the most common action.

{{"component": "modules/components/ComponentLinkHeader.js"}}

## Floating Action Button

{{"demo": "pages/components/floating-action-button/FloatingActionButtons.js"}}

## Size

Use the `size` prop for larger or smaller floating action buttons.

{{"demo": "pages/components/floating-action-button/FloatingActionButtonSize.js"}}

## Animation

Le bouton d'action flottante s'anime sur l'écran en tant que matériau en expansion, par défaut.

Un bouton d'action flottant qui s'étend sur plusieurs écrans latéraux (tels que des écrans à onglets) devrait disparaître brièvement, puis sur si son action change.

La transition Zoom peut être utilisée pour y parvenir. Notez que, comme les animations sortantes et entrantes sont déclenchées simultanément, nous utilisons `enterDelay` pour permettre à l'animation du bouton d'action flottant sortant de se terminer avant l'entrée de la nouvelle.

{{"demo": "pages/components/floating-action-button/FloatingActionButtonZoom.js", "bg": true}}
