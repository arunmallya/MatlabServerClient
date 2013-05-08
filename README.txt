Here's an implementation of a server and client in MATLAB using Java.

This uses channels for really quick transfer of files.
Without using channels, you can only transfer byte by byte and that is really slow.

Using channels helps you get around data input/output streams and allows use of a bytebuffer.