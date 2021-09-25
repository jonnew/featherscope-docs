.. |download_image| image:: /_static/download.svg
  :height: 18
.. |copy_image| image:: /_static/copy.svg
  :height: 18

.. _bonsai_ref:

Software Guide
===================================
.. toctree::
    :maxdepth: 2
    :hidden:

    installation
    Bonsai.ONIX/index
    Bonsai.Miniscope/index

Featherscopes use `Bonsai <https://bonsai-rx.org/>`__ for acquisition. There are
two libraries that can be used depending on what hardware is used to
acquire data from your scope. 

#. :ref:`bonsai_onix` - Bonsai library for the `ONIX acqusition system <https://open-ephys.github.io/onix-docs/index.html>`__.
#. :ref:`bonsai_miniscope` - Bonsai library for the `Miniscope DAQ <https://open-ephys.org/miniscope-daqs/daq>`__.

Using this Documentation
--------------------------
This documentation contains functional workflows and operators. You can
download workflows by clicking the |download_image| icon.  Alternatively, you
can copy and paste them into the `Bonsai Workflow Editor
<https://bonsai-rx.org/docs/editor/>`__ by clicking the |copy_image| icon and
using ``Ctrl+v`` or equivalent in the editor:

.. raw:: html

    {% with static_path = '../../_static', name = 'HelloWorld' %}
        {% include 'workflow.html' %}
    {% endwith %}
