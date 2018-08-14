.. _contributing:

Contributing to SimPEG
=======================

First of all, we are glad you are here! We welcome contributions and input
from the community.

This document is a set of guidelines for contributing to the repositories
hosted in the `SimPEG <https://github.com/simpeg>`_ organization on GitHub.
These repositories are maintained on a volunteer basis.


.. _questions:

Questions
---------

Please do not create an issue to ask a question. You will get a faster
response by posting on our mailing list:
https://groups.google.com/forum/#!forum/simpeg. If you prefer real-time chat,
you can join our slack group at http://slack.simpeg.xyz.

.. _bugs:

[I 17:39:58.098 NotebookApp] The port 8888 is already in use, trying another port.
[I 17:39:58.099 NotebookApp] The port 8889 is already in use, trying another port.
[I 17:39:58.100 NotebookApp] The port 8890 is already in use, trying another port.
[I 17:39:58.100 NotebookApp] The port 8891 is already in use, trying another port.
[I 17:39:58.140 NotebookApp] JupyterLab beta preview extension loaded from D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab
[I 17:39:58.140 NotebookApp] JupyterLab application directory is D:\Users\wangsheng\Anaconda3\share\jupyter\lab
[W 17:39:58.146 NotebookApp] Error loading server extension jupyterlab
Traceback (most recent call last):
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\commands.py", line 321, in __init__
self._run(['node', 'node-version-check.js'], cwd=HERE, quiet=True)
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\commands.py", line 1165, in _run
proc = Process(cmd, **kwargs)
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\process.py", line 73, in __init__
self.proc = self._create_process(cwd=cwd, env=env)
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\process.py", line 131, in _create_process
cmd[0] = which(cmd[0], kwargs.get('env'))
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\jlpmapp.py", line 59, in which
raise ValueError(msg)
ValueError: Please install nodejs 5+ and npm before continuing installation. nodejs may be installed using conda or directly from the nodejs website.

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\notebook\notebookapp.py", line 1454, in init_server_extensions
func(self)
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\extension.py", line 111, in load_jupyter_server_extension
info = get_app_info(app_dir)
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\commands.py", line 244, in get_app_info
handler = _AppHandler(app_dir, logger)
File "D:\Users\wangsheng\Anaconda3\lib\site-packages\jupyterlab\commands.py", line 324, in __init__
raise ValueError(msg)
ValueError: Please install nodejs 5+ and npm before continuing installation. nodejs may be installed using conda or directly from the nodejs website.
[I 17:39:58.285 NotebookApp] Serving notebooks from local directory: C:\Users\wangsheng
[I 17:39:58.285 NotebookApp] 0 active kernels
[I 17:39:58.285 NotebookApp] The Jupyter Notebook is running at:
[I 17:39:58.285 NotebookApp] http://localhost:8892/?token=f3216a1aa785923b008a8c600d520ea7b5423540e85b820c
[I 17:39:58.285 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 17:39:58.294 NotebookApp] 

Copy/paste this URL into your browser when you connect for the first time,
to login with a token:
http://localhost:8892/?token=f3216a1aa785923b008a8c600d520ea7b5423540e85b820c
[I 17:39:58.409 NotebookApp] Accepting one-time-token-authenticated connection from ::1

Bugs
----

When reporting an issue, please be as descriptive and provide sufficient
detail to reproduce the error. Whenever possible, if you can include a small
example that produces the error, this will help us resolve issues faster.


.. _suggesting_enhancements:

Suggesting enhancements
-----------------------

We welcome ideas for improvements on SimPEG! When writing an issue to suggest
an improvement, please

- use a descriptive title,
- explain where the gap in current functionality is,
- include a pseudocode sketch of the intended functionality

We will use the issue as a place to discuss and provide feedback. Please
remember that SimPEG is maintained on a volunteer basis. If you suggest an
enhancement, we certainly appreciate if you are also willing to take action
and start a pull request!


.. _contributing_new_code:

Contributing new code
---------------------

If you have an idea for how to improve SimPEG, please first create an issue
and :ref:`suggest an enhancement <suggesting_enhancements>`. We will use the
issue as a place to discuss and make decisions on the suggestion. Once you are
ready to take action and commit some code to SimPEG, please check out
:ref:`Getting Started for Developers <getting_started_developers>` for
tips on setting up a development environment and :ref:`Practices <practices>`
for a description of the development practices we aim to follow. In particular,

- :ref:`testing <testing>`
- :ref:`documentation <documentation>`
- :ref:`code style <style>`

are aspects we look for in all pull requests. We do code reviews on pull
requests, with the aim of promoting best practices and ensuring that new
contributions can be built upon by the SimPEG community.


Licensing
*********

The contributed code will be licensed under SimPEG's license
(https://github.com/simpeg/simpeg/blob/master/LICENSE). If you did not write
the code yourself, it is your responsibility to ensure that the existing
license is compatible and included in the contributed files or you can obtain
permission from the original author to relicense the code.





