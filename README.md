# Java package extension for Atom

## JAR Manifest Package

Provides JAR Manifest highlighting.

* To install, copy java-manifest folder to your Atom packages folder. On Linux, it's ~/.atom/packages
* To use, open MANIFEST.MF file. The language is mapped to MANIFEST.MF files.
* To understand, javamanifest.cson file contains two patterns. The header name matching begins with "{a-z}|{A-Z}|{0-9}|_|-" and ends with ":". The header value matching begins with a space and ends with a new line.
