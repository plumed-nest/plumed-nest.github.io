**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.GVEesP/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:10012] *** Process received signal ***
[pkrvmbietmlfzoi:10012] Signal: Aborted (6)
[pkrvmbietmlfzoi:10012] Signal code:  (-6)
[pkrvmbietmlfzoi:10012] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f472f045330]
[pkrvmbietmlfzoi:10012] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f472f09eb2c]
[pkrvmbietmlfzoi:10012] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f472f04527e]
[pkrvmbietmlfzoi:10012] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f472f0288ff]
[pkrvmbietmlfzoi:10012] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f472f4a5ff5]
[pkrvmbietmlfzoi:10012] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f472f4bb0da]
[pkrvmbietmlfzoi:10012] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f472f4a5a55]
[pkrvmbietmlfzoi:10012] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f472f4a5a6f]
[pkrvmbietmlfzoi:10012] [ 8] plumed(+0x146dd)[0x5575e8fd66dd]
[pkrvmbietmlfzoi:10012] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f472f02a1ca]
[pkrvmbietmlfzoi:10012] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f472f02a28b]
[pkrvmbietmlfzoi:10012] [11] plumed(+0x15365)[0x5575e8fd7365]
[pkrvmbietmlfzoi:10012] *** End of error message ***
</pre>
{% endraw %}
