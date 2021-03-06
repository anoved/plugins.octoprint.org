---
layout: plugin

id: autoselect
title: Autoselect
description: Automatically selects freshly uploaded files for printing if no print job is currently active.
author: Gina Häußge
license: AGPLv3

date: 2015-06-27

homepage: https://github.com/OctoPrint/OctoPrint-Autoselect
source: https://github.com/OctoPrint/OctoPrint-Autoselect
archive: https://github.com/OctoPrint/OctoPrint-Autoselect/archive/master.zip

tags:
- ux
- upload
- filemanagement

compatibility:
  # list of compatible versions, for example 1.2.0. If left empty no specific version requirement will be assumed
  octoprint:
  - 1.2.0
---

The Autoselect Plugin will automatically select newly uploaded files for
printing if there is an active connection to a printer and currently no print
job running.
