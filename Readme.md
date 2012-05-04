
# Dialog

  Dialog component.

## Installation

```
$ npm install dialog-component
```

## Events

  - `show` the dialog is shown
  - `hide` the dialog is hidden

## API
  
### dialog(msg)

  Display a dialog with a `msg` only.

### dialog(title, msg)

  Display a dialog with `title` and `msg`.

### Dialog#closable()

  Make the dialog closable, this adds a ×
  that users make click to forcefully close
  the dialog.

### Dialog#effect(name)

  Assign the effect name, driven by CSS transitions.
  Out of the box the following are available:

  - `slide`
  - `fade`
  - `scale`

### Dialog#overlay()

  Add a clickable overlay, which closes the dialog.

### Dialog#modal()

  Add a non-clickable overlay making it modal.

### Dialog#escapable()

  This is __private__ as it is implied by other options.
  If no overlay is used, or the overlay is non-modal
  then a user may close the dialog by pressing the escape key.

### Dialog#show()

  Show the dialog.

### Dialog#hide([ms])

  Hide the dialog immediately or wait `ms`.