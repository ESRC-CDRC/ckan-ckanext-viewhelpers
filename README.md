ckanext-viewhelpers
===================

This extension adds a few helper methods that are useful for CKAN's views. It
uses the new Resource View developed in
https://github.com/ckan/ckan/tree/1251-resource-view.

Installation
------------

To use it, simply clone this repository and run ```python setup.py install```.
Then add ```viewhelpers``` to your ```ckan.plugins``` in your CKAN config file.
Make sure you add it before the other plugins that depend on it.

Finally, restart your webserver. The helpers are now available for the other
plugins.

License
-------

Copyright (C) 2014 Open Knowledge Foundation

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
