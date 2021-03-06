RichPushSample
==============

Introduction
------------

RichPushSample is an example implementation of Rich Push for Android, using the
latest Urban Airship client library.  You can use this sample for playing with
Rich Push, or as a reference point for integrating Rich Push into your own project.


Android Studio Setup
--------------------

Add Urban Airship Library SDK:
  - Copy Urban Airship Library JAR into RichPushSample/libs/

Android SDK Manager:
  - Install updates
  - Install Android Support Repository and Android Support Library under Extras

Import Project:
 - Open Android Studio to welcome screen
 - Import project, Select Samples root directory


Eclipse (ADT) Setup
-------------------

Add Urban Airship Library SDK:
  - Copy Urban Airship Library JAR into RichPushSample/libs/

Import project:
  - Eclipse -> Import Android Project -> Samples/RichPushSample

Setup Support Library:
 - Follow http://developer.android.com/tools/support-library/setup.html to setup
 both the v7 and v4 support library

If you have updated to ADT 22, you may need to include the Android Private Libraries:
  - Right-click on RichPushSample project -> Properties > Java Build Path > Order and Export and check the Android Private Libraries

Further Reading
---------------

For more information on using Rich Push for Android see our documentation_ site.

.. _documentation: http://docs.urbanairship.com
