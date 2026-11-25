..
   SPDX-License-Identifier: AGPL-3.0-or-later

   -------------------------------------------------------
   Copyright © 2024, 2025, 2026
               Pellegrino Prevete

   All rights reserved
   -------------------------------------------------------

   This program is free software: you can redistribute it
   and/or modify it under the terms of the
   GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the
   License, or (at your option) any later version.

   This program is distributed in the hope that it will
   be useful, but WITHOUT ANY WARRANTY; without even the
   implied warranty of MERCHANTABILITY or FITNESS FOR A
   PARTICULAR PURPOSE.
   See the GNU Affero General Public License
   for more details.

   You should have received a copy of the
   GNU Affero General Public License
   along with this program.
   If not, see <https://www.gnu.org/licenses/>.


========================
mksshconfig
========================

--------------------------------------------------------------
Make SSH configuration
--------------------------------------------------------------
:Version: evm-contract-call |version|
:Manual section: 1


Synopsis
========

mksshconfig *[options]* *out-file* *host* *hostname* *user* *port*


Description
===========

Generates an SSH configuration file programmatically.

It depends on the Crash Bash library.


Arguments
===========

 - *out-file*
   
   Path of the resulting
   configuration file.

 - *host*
   
   Name of the resulting host.

 - *hostname*

   Target IP address or domain name
   or seed name.

 - *user*

   User to connect to.

 - *port*

   Port to connect to.

Options
==========

-m proxy-command

  Proxy command.


-p proxy-address

  Proxy address.


-P proxy-port

  Proxy port.


-l local-port

  Tunnel on given local port.


-r remote-port

  Tunnel on given remote port.


Application options
=====================

-h

  This message


-c

  Enable color output


-v

  Enable verbose output


Bugs
====

https://github.com/themartiancompany/evm-contracts-tools/-/issues


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.


See also
========

* dynssh

.. include:: variables.rst
