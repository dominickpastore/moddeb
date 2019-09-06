# videb

Easily edit the control archive for a deb package

## Usage

    moddeb <somepackage>.deb

## Operation

When run, the control archive from the deb package will be extracted into a temp
directory. Then, moddeb will prompt you for which files you want to edit. Once
you are finished editing, it will write the new deb to
`<somepackage>.modified.deb` in the current directory. If that file already
exists, it asks you whether to overwrite, add a number to the name, or cancel.
