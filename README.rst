This is a Python (2 and 3) library to access the `Github API v3 <http://developer.github.com/v3>`_.
With it, you can manage your `Github <http://github.com>`_ resources (repositories, user profiles, organizations, etc.) from Python scripts.

It covers the **full** API, and all methods are tested against the real Github site.

Should you have any question, any remark, or if you find a bug, or if there is something you can do with the API but not with PyGithub, please `open an issue <https://github.com/jacquev6/PyGithub/issues>`_.

PyGithub is stable. I will maintain it up to date with the API, and fix bugs if any, but I don't plan new heavy developments.

What's new?
===========

`Version 1.14.0 <https://github.com/jacquev6/PyGithub/issues?milestone=24&state=closed>`_ (April 22nd, 2013)
------------------------------------------------------------------------------------------------------------

* `Improve <https://github.com/jacquev6/PyGithub/issues/156>`_ gist edition. Thank you `jasonwiener <https://github.com/jasonwiener>`_ for asking:
  * Delete a file with `gist.edit(files={"name.txt": None})`
  * Rename a file with `gist.edit(files={"old_name.txt": github.InputFileContent(gist.files["old_name.txt"].content, new_name="new_name.txt")})`
* `Raise <https://github.com/jacquev6/PyGithub/issues/152>`_ specific exceptions. Thank you `pconrad <https://github.com/pconrad>`_ for giving me the idea

Documentation
=============

All the documentation is here: http://jacquev6.github.com/PyGithub.
