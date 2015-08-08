# Bash-Apache-Operations
Some Bash commands to simplify certain Apache operations in Ubuntu

To install, clone this repository, then add the following into your ~/.bashrc
`source /path/to/apache.sh`
replacing "/path/to" with the actual file path

1. __Apache commands__
   	- `httpHeaders` - get HTTP headers for a remote web page
   		- __argument $@__ web page URL
   		- Usage example:  `httpHeaders text.example.com`
   	- `httpDebug` - download a remote web page and show info on what took time
   		- __argument $@__ web page URL
   		- Usage example:  `httpDebug text.example.com`
   	- `display_errors_on` - turn display errors on in php.ini
   	- `display_errors_off` - turn display errors off in php.ini
