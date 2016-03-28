# wHMI
Web Human-Machine Interface
An easy way to realize Web HMI for devices (PLC or industrial controls) which use:
 * Ethernet S7 Protocol communications. It is the backbone of the Siemens communications
 * FINS Protocol communications (UDP/IP or TCP/IP). It is used in the OMRON PLC
 * MODBUS RTU: Serial communication
 * MODBUS TCP/IP.
 * MQTT is a machine-to-machine "Internet of Things" connectivity protocol


# Main features
With wHMI is possible to:
 * define an arbitrary number of parameters;
 * design one or more pages to access at these parameters;
 * define an arbitrary number of variabes (data) that can be logged in a SQLite DB;
 * define the event (an external event or temporal event) to acquire and store the data/variables;
 * graph, directly from wHMI, the temporal trends of the individual variables;
 * load one or more SVG images to realize interactive synoptics;
    

# Libraries and tools used
wHMI uses many open source projects, the most important are:
 * Snap7: http://snap7.sourceforge.net/
 * libmodbus: http://libmodbus.org/
 * Paho: http://www.eclipse.org/paho/
 * Bootstrap: http://getbootstrap.com/
 * SQLite: https://www.sqlite.org/
 * D3.js: https://d3js.org/
 * openfins: https://github.com/gnlcosta/openfins


# License
GNU AFFERO GENERAL PUBLIC LICENSE
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
