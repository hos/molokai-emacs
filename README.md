# Molokai for Emacs

My attempt to create a better implementation of Molokai in Emacs. It is based on
the awesome `oneKelvinSmith/monokai-emacs`, with the colors borrowed from
`hbin/molokai-theme`.

*This is work in progress. Please do not use it yet.*

## Installation

Clone this repository to your Emacs configuration under `/themes`

    git clone https://github.com/hos/molokai-theme /path-to-your-emacs-config/themes

Then add the following lines to your configuration, assuming your Emacs
configuration is under `~/.emacs.d/`

    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes/molokai-theme")
    (load-theme 'molokai t)
