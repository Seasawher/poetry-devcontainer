# Poetry Devcontainer

There are various obstacles to using Poetry with Devcontainer.

* Poetry creates a virtual environment by default, but this should be turned off when using Docker.
* Depending on the base image, there may be a problem where the Python environment used by Poetry differs from the Python environment on the system. This will result in packages added with `poetry add` not being usable.
* After installing Poetry, you need to update your PATH yourself as it is not automatically updated..

With this template, the above problems have already been solved, so you don't have to spend time solving them. 👍
