^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package tesseract_srdf
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.9.11 (2022-06-30)
-------------------
* Updated CPack (`#786 <https://github.com/tesseract-robotics/tesseract/issues/786>`_)
* Update to use find_gtest macro
* Contributors: Levi Armstrong, Michael Ripperger

0.9.10 (2022-06-14)
-------------------

0.9.9 (2022-05-30)
------------------

0.9.8 (2022-05-30)
------------------

0.9.7 (2022-05-30)
------------------

0.9.6 (2022-05-02)
------------------

0.9.5 (2022-04-24)
------------------

0.9.4 (2022-04-22)
------------------
* Windows fixes with passing unit tests (`#751 <https://github.com/tesseract-robotics/tesseract/issues/751>`_)
  * Fix bug in OFKTStateSolver::moveLinkHelper
  * Use binary ifstream ond ofstream in serialization.h
  * Add c++17 flag to windows_noetic_build.yml
  * Fix SceneGraph move constructor, restore modified unit tests
* Contributors: John Wason

0.9.3 (2022-04-18)
------------------

0.9.2 (2022-04-03)
------------------

0.9.1 (2022-04-01)
------------------

0.9.0 (2022-03-31)
------------------
* Make ResourceLocator serializable
* Contributors: Levi Armstrong

0.8.7 (2022-03-24)
------------------

0.8.6 (2022-03-24)
------------------

0.8.5 (2022-03-24)
------------------
* Add boost serialization for Environment commands and all underlying types (`#726 <https://github.com/tesseract-robotics/tesseract/issues/726>`_)
  * Add serialization macros to tesseract_common
  * Add serialization for tesseract_geometry primatives
  * Add serialization for meshes and octree
  * Add serialization for Link and Joint
  * Add serialization for tesseract_common types
  * Add serialization for SceneGraph and SceneState
  * Add serialization for tesseract_srdf and tesseract_common types
  * Add serialization for environment commands
  * Fix bug in getCollisionObjectPairs
* Contributors: Matthew Powelson

0.8.4 (2022-03-03)
------------------
* cmake format
* Add TESSERACT_ENABLE_EXAMPLES compile option
* Contributors: John Wason

0.8.3 (2022-02-22)
------------------
* Python patches for Feb 2022 update (`#716 <https://github.com/tesseract-robotics/tesseract/issues/716>`_)
* Sort ACM alphabetically when writing
* Contributors: John Wason, Matthew Powelson

0.8.2 (2022-01-27)
------------------
* Add ability to provide calibration information in the SRDF (`#703 <https://github.com/tesseract-robotics/tesseract/issues/703>`_)
  * Add missing package tesseract_srdf in CI after script
  * Add support for calibration info in SRDF
* Contributors: Levi Armstrong

0.8.1 (2022-01-24)
------------------

0.8.0 (2022-01-19)
------------------

0.7.5 (2022-01-10)
------------------

0.7.4 (2021-12-15)
------------------

0.7.3 (2021-12-15)
------------------

0.7.2 (2021-12-15)
------------------

0.7.1 (2021-12-15)
------------------

0.7.0 (2021-12-04)
------------------
* Move AllowedCollisionMatrix into tesseract_common
* Contributors: Matthew Powelson

0.6.9 (2021-11-29)
------------------

0.6.8 (2021-11-29)
------------------
* Fix spelling errors
* Contributors: Levi Armstrong

0.6.7 (2021-11-16)
------------------

0.6.6 (2021-11-10)
------------------

0.5.0 (2021-07-02)
------------------
* Fix SRDF REP and ROP positioner joint parsing
* Contributors: Levi Armstrong

0.4.1 (2021-04-24)
------------------

0.4.0 (2021-04-23)
------------------
* Fix test names in tesseract_srdf
* Fix spelling in tesseract_srdf package.xml
* Update tesseract_srdf to leverage nested exceptions
* Move srdf code to its own package tesseract_srdf
* Contributors: Levi Armstrong
