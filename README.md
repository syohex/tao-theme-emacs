# Tao Theme for Emacs

## About

Tao is a natural & beautiful grayscale color theme for Emacs. Its palette is generated by the golden-mean.

## Installation

Tao will be available in [MELPA] (http://melpa.milkbox.net).

You can install `tao` with the following command:

`M-x package-install tao-theme`

Alternatively you can clone this repository, and then:

`M-x package-install-file tao-theme`

### Yin (Dark version)

![238195518_full](https://cloud.githubusercontent.com/assets/977130/9500092/3134df24-4c2c-11e5-9646-9646a042b679.png)

`M-x load-theme tao-yin`

### Yang (Light version)

![238195728_full](https://cloud.githubusercontent.com/assets/977130/9500093/3137dbfc-4c2c-11e5-87b4-27603fa676d2.png)

`M-x load-theme tao-yang`

## Customisation

`(defun tao-palette () (tao-theme-golden-grayscale-yin-palette))` then you can use `tao-with-color-variables` like this:

```
(tao-with-color-variables tao-palette 
  (progn
    (setq 
      hl-paren-colors (list color-14 color-11 color-9 color-7 color-6)
      hl-paren-background-colors (list color-4 color-4 color-4 color-4 color-4))))

```

[Here](https://github.com/11111000000/emacs-d) you can find `powerline-tao-theme` snippet.

### Credits

Original concept, design and development by Peter Kosov.  Additional
packaging, development and assistance from @jasonm23/emacsfodder.
