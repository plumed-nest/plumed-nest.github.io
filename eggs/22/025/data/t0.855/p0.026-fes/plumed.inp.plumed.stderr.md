**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.2i2dUJ/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:65310] *** Process received signal ***
[pkrvmbietmlfzoi:65310] Signal: Aborted (6)
[pkrvmbietmlfzoi:65310] Signal code:  (-6)
[pkrvmbietmlfzoi:65310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc0c0645330]
[pkrvmbietmlfzoi:65310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc0c069eb2c]
[pkrvmbietmlfzoi:65310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc0c064527e]
[pkrvmbietmlfzoi:65310] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0c06288ff]
[pkrvmbietmlfzoi:65310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0c0aa5ff5]
[pkrvmbietmlfzoi:65310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0c0abb0da]
[pkrvmbietmlfzoi:65310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0c0aa5a55]
[pkrvmbietmlfzoi:65310] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0c0aa5a6f]
[pkrvmbietmlfzoi:65310] [ 8] plumed(+0x146dd)[0x55d56ac606dd]
[pkrvmbietmlfzoi:65310] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc0c062a1ca]
[pkrvmbietmlfzoi:65310] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc0c062a28b]
[pkrvmbietmlfzoi:65310] [11] plumed(+0x15365)[0x55d56ac61365]
[pkrvmbietmlfzoi:65310] *** End of error message ***
</pre>
{% endraw %}
