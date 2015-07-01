sample_ubuntu1204_python
=====================

This sample helps you create a shippable.yml file for your Python project on Shippable with tests using Nose and Coverage. Please refer to our [language specific documentation on Python](http://docs.shippable.com/languages/#python) for more details.

### Build Image

The sample uses a python specific build image that's available for public use:
[shippableimages/ubuntu1204_python](https://registry.hub.docker.com/u/shippableimages/ubuntu1204_python)  ([Dockerfile](https://github.com/shippableImages/ubuntu1204_python/blob/master/Dockerfile)).

To set your build image in Shippable:
- Login to [Shippable](https://www.shippable.com) 
- Navigate to your project page by clicking on the project link
- Click on **Settings** and choose the following option:

`Pull Image from : shippableimages/ubuntu1204_python`

For more details on project settings, you can refer our docs on  [Build and Project Settings](http://docs.shippable.com/project_settings).
