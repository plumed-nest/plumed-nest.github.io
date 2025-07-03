**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-bend/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.CRtf8V/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:10274] *** Process received signal ***
[pkrvmbietmlfzoi:10274] Signal: Aborted (6)
[pkrvmbietmlfzoi:10274] Signal code:  (-6)
[pkrvmbietmlfzoi:10274] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9729845330]
[pkrvmbietmlfzoi:10274] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f972989eb2c]
[pkrvmbietmlfzoi:10274] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f972984527e]
[pkrvmbietmlfzoi:10274] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97298288ff]
[pkrvmbietmlfzoi:10274] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9729ca5ff5]
[pkrvmbietmlfzoi:10274] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9729cbb0da]
[pkrvmbietmlfzoi:10274] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9729ca5a55]
[pkrvmbietmlfzoi:10274] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9729ca5a6f]
[pkrvmbietmlfzoi:10274] [ 8] plumed(+0x146dd)[0x5572435066dd]
[pkrvmbietmlfzoi:10274] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f972982a1ca]
[pkrvmbietmlfzoi:10274] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f972982a28b]
[pkrvmbietmlfzoi:10274] [11] plumed(+0x15365)[0x557243507365]
[pkrvmbietmlfzoi:10274] *** End of error message ***
</pre>
{% endraw %}
