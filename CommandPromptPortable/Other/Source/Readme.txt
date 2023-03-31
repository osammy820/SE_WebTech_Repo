Command Prompt Portable Launcher
================================
Copyright 2004-2021 John T. Haller
Icon is from the Crystal Clear set by Everaldo

Website: http://PortableApps.com

This software is OSI Certified Open Source Software.
OSI Certified is a certification mark of the Open Source Initiative.

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.


ABOUT Command Prompt Portable
=============================
A simple stub launcher for starting a command prompt with your choice of options.  The file
\Data\Batch\commandprompt.bat will be run on start.

Paths can be passed on the command line and the prompt will start pointing to that path. (Note: This
works on Windows 2000 and up only)

Setting up a CommandPromptPortable.ini file with a head of [CommandPromptPortable] and an entry of
EnableAutoComplete=true will enable auto-complete within the command line window on the TAB character.
This affects all windows launched with Command Prompt Portable, but if you launch multiple windows and
then close the first one you launched, the setting will be switched back to the PC's original setting.


LICENSE
=======
This code is released under the GPL.  The full code is included with this package as CommandPromptPortable.nsi.