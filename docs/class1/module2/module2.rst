Module 2 - Interacting with an iControl LX extension
====================================================

In this module, we are going to introduce the basic themes and then review an
iControl LX extension.

The following exercises will be performed on the iWorkflow platform
(``https://10.1.10.20``).

While the iControl LX framework runs on both BIG-IP and iWorkflow, there are
many workflows that don't make sense to run directly on the BIG-IP. For
example, if we developed an extension that presented the status of a Fleet
of BIG-IP devices, it would make far more sense to do this from a central
platform, rather than on each individual BIG-IP.

.. NOTE:: This lab will NOT guide you through the iWorkflow or BIG-IP lab setup.
   For information on installing and configuring BIG-IP and iWorkflow, please
   visit:

   * `F5 iWorkflow <https://devcentral.f5.com/wiki/iWorkflow.HomePage.ashx>`_
   * `F5 BIG-IP <https://support.f5.com/csp/knowledge-center/software/BIG-IP?module=BIG-IP%20LTM>`_

**Exercises in this Module**

- Lab 2.1 - Interact with a REST extension

  - Task 1 - View the API via Web Browser
  - Task 2 - Interact with a REST Resource
  - Task 3 - The '/presentation#' Extension
  - Task 4 - Editing a REST Resource


.. toctree::
  :maxdepth: 1
  :glob:

  lab*
