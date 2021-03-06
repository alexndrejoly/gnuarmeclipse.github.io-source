---
layout: page
permalink: /developer/change-log/
title: The 2016 GNU ARM Eclipse Plug-ins Change Log
author: Liviu Ionescu

date: 2016-02-09 12:48:00 +0300

---

Entries in this file are in reverse chronological order.

## 2016

### 2016-03-28

* Merge pull request #107 from iulia-vasii/iulia-dev; allow Settings page to open in case toolchain is not defined

### 2016-03-19

* Merge pull request #103 from sukidog/issue102_pyocd; Fix issue #102. Do not prevent user from relying on gdbserver in PATH

### 2016-03-15

* Merge pull request #96 from marek-trmac/develop #94: Fixed access to local repository using file:/// schema
* mbs.cross: v2.2.1
* Merge pull request #99 from marek-trmac/develop; #95: Added support for file protocol used in URL
* packs.data: Repos also convert spaces to _
* packs.data: version 1.2.3

### 2016-03-13

* Merge pull request #93 from flit/develop; pyOCD plugin requested changes
* Merge pull request #91 from iulia-vasii/iulia-dev; fix Apply button in Toolchains tab

### 2016-02-22

* enable per project formatter, Eclipse (built-in)
* Merge pull request #86 from flit/develop; Fix remaining warnings in pyOCD plugin
* Merge pull request #87 from flit/develop; More adjustments to pyOCD launch GUI as per Liviu's request
* reformat

### 2016-02-21

* Merge pull request #84 from flit/pyocd-dev; Various improvements and fixes
* gdbjtag.pyocd: silence warnings, reformat

### 2016-02-15

* Merge pull request #76 from sukidog/cleanup_warn3; templates.ad: fix wrong Activator class specification
* Merge pull request #77 from sukidog/cleanup_warn4; Fix warnings with output specification in build.properties

### 2016-02-14

* core: fix sem ver parsing of short strings

### 2016-02-13

* core: add semVer library
* packs.core: add properties access & alias
* core: make semVer tolerant to partial version
* packs.core: silence warning
* packs.data: accept schema 1.4
* packs.core: version 1.1.3
* packs.data: version 1.2.2
* version: 2.12.1

### 2016-02-10

* version 2.11.3-201602101653 released
  * features/ilg.gnuarmeclipse.codered_1.1.1.201602101653.jar
  * features/ilg.gnuarmeclipse.debug.gdbjtag.jlink_3.2.1.201602101653.jar
  * features/ilg.gnuarmeclipse.debug.gdbjtag.openocd_3.2.1.201602101653.jar
  * features/ilg.gnuarmeclipse.debug.gdbjtag.qemu_2.1.3.201602101653.jar
  * features/ilg.gnuarmeclipse.doc.user_1.1.1.201602101653.jar
  * features/ilg.gnuarmeclipse.managedbuild.cross_2.1.1.201602101653.jar
  * features/ilg.gnuarmeclipse.packs_2.2.2.201602101653.jar
  * features/ilg.gnuarmeclipse.templates.ad_1.1.3.201602101653.jar
  * features/ilg.gnuarmeclipse.templates.cortexm_1.3.1.201602101653.jar
  * features/ilg.gnuarmeclipse.templates.freescale_2.2.7.201602101653.jar
  * features/ilg.gnuarmeclipse.templates.stm_2.5.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.codered_1.1.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.core_2.11.3.201602101653.jar
  * plugins/ilg.gnuarmeclipse.debug.core_1.2.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.jlink_3.2.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.openocd_3.2.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.qemu_2.1.3.201602101653.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.restart_1.3.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag_2.2.2.201602101653.jar
  * plugins/ilg.gnuarmeclipse.debug.packs_1.1.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.doc.user_1.1.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.managedbuild.cross_2.1.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.managedbuild.packs_1.3.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.packs.core_1.1.2.201602101653.jar
  * plugins/ilg.gnuarmeclipse.packs.data_1.2.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.packs.ui_1.2.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.packs_1.2.3.201602101653.jar
  * plugins/ilg.gnuarmeclipse.templates.ad_1.1.3.201602101653.jar
  * plugins/ilg.gnuarmeclipse.templates.core_2.5.4.201602101653.jar
  * plugins/ilg.gnuarmeclipse.templates.cortexm_1.3.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.templates.freescale.pe_1.2.1.201602101653.jar
  * plugins/ilg.gnuarmeclipse.templates.freescale_2.2.7.201602101653.jar
  * plugins/ilg.gnuarmeclipse.templates.stm_2.5.1.201602101653.jar
* templates.core: v2.5.4
* repo: v2.11.3
* templates.core: enable lazy activation

### 2016-02-09

* version 2.11.2-201602091039 released
  * features/ilg.gnuarmeclipse.codered_1.1.1.201602091039.jar
  * features/ilg.gnuarmeclipse.debug.gdbjtag.jlink_3.2.1.201602091039.jar
  * features/ilg.gnuarmeclipse.debug.gdbjtag.openocd_3.2.1.201602091039.jar
  * features/ilg.gnuarmeclipse.debug.gdbjtag.qemu_2.1.3.201602091039.jar
  * features/ilg.gnuarmeclipse.doc.user_1.1.1.201602091039.jar
  * features/ilg.gnuarmeclipse.managedbuild.cross_2.1.1.201602091039.jar
  * features/ilg.gnuarmeclipse.packs_2.2.2.201602091039.jar
  * features/ilg.gnuarmeclipse.templates.ad_1.1.3.201602091039.jar
  * features/ilg.gnuarmeclipse.templates.cortexm_1.3.1.201602091039.jar
  * features/ilg.gnuarmeclipse.templates.freescale_2.2.7.201602091039.jar
  * features/ilg.gnuarmeclipse.templates.stm_2.5.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.codered_1.1.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.core_2.11.2.201602091039.jar
  * plugins/ilg.gnuarmeclipse.debug.core_1.2.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.jlink_3.2.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.openocd_3.2.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.qemu_2.1.3.201602091039.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag.restart_1.3.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.debug.gdbjtag_2.2.2.201602091039.jar
  * plugins/ilg.gnuarmeclipse.debug.packs_1.1.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.doc.user_1.1.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.managedbuild.cross_2.1.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.managedbuild.packs_1.3.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.packs.core_1.1.2.201602091039.jar
  * plugins/ilg.gnuarmeclipse.packs.data_1.2.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.packs.ui_1.2.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.packs_1.2.3.201602091039.jar
  * plugins/ilg.gnuarmeclipse.templates.ad_1.1.3.201602091039.jar
  * plugins/ilg.gnuarmeclipse.templates.core_2.5.3.201602091039.jar
  * plugins/ilg.gnuarmeclipse.templates.cortexm_1.3.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.templates.freescale.pe_1.2.1.201602091039.jar
  * plugins/ilg.gnuarmeclipse.templates.freescale_2.2.7.201602091039.jar
  * plugins/ilg.gnuarmeclipse.templates.stm_2.5.1.201602091039.jar
* templates.stm: update to f4 hal 1.11.0, f7 hal 1.3.0
* templates.stm: update to f4 cmsis 2.7.0, f7 cmsis 2.4.0
* templates.core: _exit() add reference to __reset()
* add CONTRIBUTING.md
* templates.core: v2.5.3
* templates.stm: v2.5.1
* repo: v2.11.2

## 2015

See [2015]({{ site.baseurl }}/developer/change-log/2015/).
