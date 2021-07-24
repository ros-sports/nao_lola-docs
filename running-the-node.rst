Running the Node
################

.. warning::

    The **effector commands have not been tested on a real NAO yet**, due to the maintainer's difficulty in accessing
    a physical robot. Please raise an issue or a PR with a fix on `Github`_ if the package doesn't work as expected.

After sourcing the setup file, all you have to do is run:

.. code-block:: console

    ros2 run nao_lola nao_lola


To see all the topics being published and subscribed, in a new terminal, run

.. code-block:: console

    ros2 topic list -t


.. _Github: https://github.com/ijnek/nao_lola