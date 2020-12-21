libsamplerate generally takes arbitrary inputs. Since the input from the PDP-8
simulator will always be 1s or 0s, this source file has been optimized to
assume only two distinct values. 

Follow the instructions to build libsamplerate on your system, ensuring the new
library is renamed to "libsamplerateint," which SimH's makefile references.
