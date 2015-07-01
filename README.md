Velox 2 API
===============

This repository contains the third party API for Velox 2 extensions, in the form of a .nic template, for use with the theos makefiel system.

To get started, simply put the template in $(THEOS)/templates/, then run $(THEOS)/bin/nic.pl and select Velox plugin.

The file Velox Protocol documents all the methods available to you, the extension developer. The template also sets up a basic view for you, so it's easy and quick for you to get started.

Your main class must inherit from UIView, and it must conform to the VeloxView protocol. Many methods are optional, but a small handful are required. See the documentation for more details.

Contact me for any questions or concerns. You are free to publish Velox extensions without my knowledge or consent, but you may not redistribute the Velox binary with it.
