Role Name
=========

ruby

Requirements
------------

none

Role Variables
--------------

ruby_gems - An array of hashes with the following keys:
  - name
  - state (defaults to 'present')
  - version (defaults to an empty string which will install latest)

  All values should correspond to the gem module. See
  http://docs.ansible.com/gem_module.html for details.

ruby_version: A string used to match from available packages. Defaults to
'ruby' which will leverage yum's default behavior of installing the latest
package. Useful when an older version of the package is desired.

  Example: ruby-1.9.3p392-1.el6

Dependencies
------------

none

