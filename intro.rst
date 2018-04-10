Intro
=====

Project Structure
-----------------

The project consists of a main file ``Aratom_LCD.ino`` where all the logic of the program is defined, and a file ``Button.h`` where utility classes are defined.

Also, this project uses the Arduino ``TFT_HX8357`` driver, and a version of the STL.

There are also some utility scripts, which are not needed to compile the project.

* :doc:`converter.py`
	It is used to convert images to the required formats for working with the arduino.

* :doc:`Aratom_LCD.ino`
	Contains the logic of the main UI

* :doc:`Button.h`
	Contains base definitions to be used in ``Aratom_LCD.ino``
