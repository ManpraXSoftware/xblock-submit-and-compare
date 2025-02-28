Submit and Compare XBlock
=========================

This XBlock provides a way to do an ungraded self assessment activity.
It is useful for synthesis questions, or questions which require the
student to answer in her own words.
After the student submits her answer, she is able to see the
instructor's answer, and compare her answer to the expert answer.

|badge-ci|
|badge-coveralls|

|image-lms-view-normal|


Installation
------------


System Administrator
~~~~~~~~~~~~~~~~~~~~

To install the XBlock on your platform,
add the following to your `requirements.txt` file:

    xblock-submit-and-compare

You'll also need to add this to your `INSTALLED_APPS`:

    submit_and_compare


Course Staff
~~~~~~~~~~~~

To install the XBlock in your course,
access your `Advanced Module List`:

    Settings -> Advanced Settings -> Advanced Module List

|image-cms-settings-menu|

and add the following:

    submit-and-compare

|image-cms-advanced-module-list|


Use
---


Course Staff
~~~~~~~~~~~~

To add a full-screen image to your course:

- upload the image file onto your course's Files & Uploads page

  - note: you can skip this step if you've already uploaded the image
    elsewhere, e.g.: S3.

- copy the URL on that page
- go to a unit in Studio
- select "Image Modal XBlock" from the Advanced Components menu

|image-cms-add|

You can now edit and preview the new component.

|image-cms-view|

Using the Studio editor, you can edit the following fields:

- display name
- image URL
- thumbnail URL (defaults to image URL, if not specified)
- description (useful for screen readers, longer descriptions)
- alt text (useful for screen readers, captions, tags; displays when image does not)

|image-cms-editor-1|
|image-cms-editor-2|


Participants
~~~~~~~~~~~~

|image-lms-view-normal|

Click on the image to zoom in full-screen.

|image-lms-view-zoom|

Click on the image again to zoom out.

Click and drag to pan around.

`View a demo of the CMS`_

`View a demo of the LMS`_


.. |badge-coveralls| image:: https://coveralls.io/repos/github/Stanford-Online/xblock-image-modal/badge.svg?branch=master
   :target: https://coveralls.io/github/Stanford-Online/xblock-image-modal?branch=master
.. |badge-ci| image:: https://github.com/edx/xblock-submit-and-compare/workflows/Python%20CI/badge.svg?branch=master
   :target: https://github.com/edx/xblock-submit-and-compare/actions?query=workflow%3A%22Python+CI%22
.. |image-cms-add| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/cms-add.jpg
   :width: 100%
.. |image-cms-advanced-module-list| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/advanced-module-list.png
   :width: 100%
.. |image-cms-editor-1| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/studio-editor-1.png
   :width: 100%
.. |image-cms-editor-2| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/studio-editor-2.png
   :width: 100%
.. |image-cms-settings-menu| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/settings-menu.png
   :width: 100%
.. |image-cms-view| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/studio-view.png
   :width: 100%
.. |image-lms-view-normal| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/lms-view-normal.png
   :width: 100%
.. |image-lms-view-zoom| image:: https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/lms-view-zoom.png
   :width: 100%
.. _View a demo of the CMS: https://youtu.be/IcbGYfbav2w
.. _View a demo of the LMS: https://youtu.be/0mpjuThDoyE
.. https://s3-us-west-1.amazonaws.com/stanford-openedx-docs/xblocks/image-modal/static/images/xblock-image-modal-demo-lms.mov
