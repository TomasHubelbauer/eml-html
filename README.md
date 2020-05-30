# HTML support in EML

## `form`

Forms will render in some clients, but form submission does not seem to work
anywhere.

## `details`

Works in Fastmail.

## `svg`

The SVG XML cannot be embedded directly in EML, but it can be referenced using
an `img` tag using a data URI. The data URI must be split into lines of MIME
76 characters (or less) and Base64 encoded. The is likely also possible to use
a CID of an attachment for the `img` source.
