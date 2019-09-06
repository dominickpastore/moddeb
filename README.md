# moddeb

Easily edit the control archive for a deb package

## Usage

    moddeb <somepackage>.deb

## Operation

When run, the control archive from the deb package will be extracted into a temp
directory. Then, moddeb will prompt you for which files you want to edit. Once
you are finished editing, it will write the new deb to
`<somepackage>.modified.deb` in the current directory. If that file already
exists, it asks you whether to overwrite, add a number to the name, or cancel.

## References

Based on ideas from [this Unix & Linux Stack Exchange post](https://unix.stackexchange.com/questions/138188/easily-unpack-deb-edit-postinst-and-repack-deb/138190#138190)
and [this Ubuntu Forums thread](https://ubuntuforums.org/showthread.php?t=636724).

## License

See the file named LICENSE.
