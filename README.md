# ct-ng_configs
Here are some preconfiged .config files which not included in crosstool-ng-1.24.0 samples

Notes:
  1.all these .config files were generated from sample templates;
  2.added IPv6 gdb  companion tools for target gcc;
  3.set Tuple prefix "gnu"
  4.set target gcc compiler "GCC-7.4.0"
  5.set target Linux version "3.4.113"

Usage:
  1.clone a branch and copy it to your crosstool-ng-(#version)/samples directory;
  2.ct-ng <sample_name>
  3.ct-ng build
