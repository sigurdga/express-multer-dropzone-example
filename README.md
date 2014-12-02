A simple example of using Express and Multer, with or without Dropzone
======================================================================

This is just a very simple example of using Express and Multer to upload files.
There are two examples:

- Using Dropzone for drag and drop (sending multiple single post requests)
- Using simple form (sending one or more files per post request)

The example is saving, but not doing anything more. To get some details,
uncomment the ``console.log(req.files)`` line of the post route.

To be a bit helpful, it is console.logging how many files were sent, to show if
it got an array of files or a single file.

License
-------

MIT
