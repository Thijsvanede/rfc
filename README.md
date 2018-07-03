# RFC
A small bash program to request the rfc from the source.

## Dependencies
Most dependencies are installed by default on most UNIX systems, except the following:
 * curl
 
If you experience any problems, check if `bash` and `less` are installed.

## Installation
Upon installation, run the ./install script, this will move the rfc to the ~/.local/bin directory from which it will be directly accessable.

## Usage
When using the installation script, rfc will be directly accessable from anywhere.
If the installation script was not used, the rfc can be accessed from the directory in which it resides.

```
Usage: $(basename "$0") [number | protocol] [--help] [-l ?search]
Retrieve RFC for given number or well-known port.

where:
	number		number denoting the RFC
	protocol	well known protocol for which to retrieve RFC, e.g. http
	-h			show this help text
	-l			list possible RFCs, optional argument to search in the RFCs.
```
