**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.JVSQFR/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:08087] *** Process received signal ***
[pkrvmbietmlfzoi:08087] Signal: Aborted (6)
[pkrvmbietmlfzoi:08087] Signal code:  (-6)
[pkrvmbietmlfzoi:08087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5378c45330]
[pkrvmbietmlfzoi:08087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5378c9eb2c]
[pkrvmbietmlfzoi:08087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5378c4527e]
[pkrvmbietmlfzoi:08087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5378c288ff]
[pkrvmbietmlfzoi:08087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53790a5ff5]
[pkrvmbietmlfzoi:08087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53790bb0da]
[pkrvmbietmlfzoi:08087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53790a5a55]
[pkrvmbietmlfzoi:08087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53790a5a6f]
[pkrvmbietmlfzoi:08087] [ 8] plumed(+0x146dd)[0x555b246636dd]
[pkrvmbietmlfzoi:08087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5378c2a1ca]
[pkrvmbietmlfzoi:08087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5378c2a28b]
[pkrvmbietmlfzoi:08087] [11] plumed(+0x15365)[0x555b24664365]
[pkrvmbietmlfzoi:08087] *** End of error message ***
</pre>
{% endraw %}
