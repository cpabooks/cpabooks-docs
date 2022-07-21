.. _testdrive:

.. index::
   single: CPAbooks Demo
   single: CPAbooks Runbot

==============================
How to test upcoming features?
==============================
CPAbooks offers a platform where you can test latest stable version of the CPAbooks software or you can also test the upcoming features from development version.

CPAbooks Online Demo
----------------
CPAbooks instant demonstration can be found at https://demo.CPAbooks.com. Online demo is perfect fit for the visitors who wanted to test the latest stable CPAbooks software without installing or creating an online instance, demo instance will be refreshed every 24 hours automatically so all the data created by you will be erased automatically.

.. image:: images/chapter_01_07.png
   :alt: CRM, Sales and Invoicing for 5 users
   :align: center

.. tip:: Don't worry if your URL will be changed form https://demo.CPAbooks.com to https://demo1.CPAbooks.com, https://demo2.CPAbooks.com or https://demo3.CPAbooks.com, CPAbooks started many demo instance, you will be redirected to the instance having low traffic.

Test upcoming features
----------------------
**CPAbooks Runbot** is automated test platform user for the continuous integration designed and developed by CPAbooks SA. It is integrated with github.com to test each and every committee made by the CPAbooks developers. CPAbooks Employees worldwide use this platform for the internal testing before merging any feature into the master branch.

.. image:: images/chapter_01_08.png
   :alt: runbot.CPAbooks.com
   :align: center

Background colours of committee represents the status of the committee, Green represents successfully tested without any ERROR while Red represents ERROR in the code, either code is not clean or there is any test-case failed. You can not connect the committee which are in Blue color as there are currently being tested by the runbot.

Most of the features under development can be found under ``CPAbooks-dev/CPAbooks`` or ``CPAbooks-dev/enterprise`` menu, branche name started with master- are the features under development while ``10-xxx-xxx`` or ``11-xxx-xxx`` are the fixes for the respective versions.

Connect to the test instance
----------------------------
You can connect and test every single committee on the development branch, click on the ``Sign in to this build`` icon.

.. tip:: The default username will be admin and password will be admin too for all the instance, if may not able to connect in case some visitor has changed the password.

You can perform the test on two different databases:

* Installed all the applications with demo data
* Installed only base application without demo data - you have to install additional applications you want to test.

.. danger:: **Online Demo** and **Runbot** is not suitable platform to prepare the demo as no guarantee to get the same data all the time, because several users using those instances so data may change without notifications.
