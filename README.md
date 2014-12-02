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

Getting started
---------------

* ``git clone https://github.com/sigurdga/express-multer-dropzone-example``
* ``cd express-multer-dropzone-example``
* ``npm install``
* ``npm start``

Then take a look at ``http://localhost:3000/``.

Uploaded files will be saved to the ``./uploads/`` folder, as specified in the
Multer’s ``dest`` configuration option.

License
-------

MIT
