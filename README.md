# annoying-arrows-mode.el

Entering annoying-arrows-mode makes emacs ring the bell in your face if you move
long distances in the buffer one char at a time.

    ;; Annoying arrows mode
    (require 'annoying-arrows-mode)
    (global-annoying-arrows-mode)

Set the `annoying-arrows-too-far-count' to adjust the length.

## Contributors

* [Piers Cawley](https://github.com/pdcawley) added `aa-add-suggestion` for easier extension

Thanks!
