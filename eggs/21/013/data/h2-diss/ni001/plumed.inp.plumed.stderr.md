**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.mAXVs7/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:66003] *** Process received signal ***
[pkrvmbietmlfzoi:66003] Signal: Aborted (6)
[pkrvmbietmlfzoi:66003] Signal code:  (-6)
[pkrvmbietmlfzoi:66003] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd395445330]
[pkrvmbietmlfzoi:66003] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd39549eb2c]
[pkrvmbietmlfzoi:66003] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd39544527e]
[pkrvmbietmlfzoi:66003] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3954288ff]
[pkrvmbietmlfzoi:66003] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3958a5ff5]
[pkrvmbietmlfzoi:66003] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3958bb0da]
[pkrvmbietmlfzoi:66003] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3958a5a55]
[pkrvmbietmlfzoi:66003] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3958a5a6f]
[pkrvmbietmlfzoi:66003] [ 8] plumed(+0x146dd)[0x55a892e486dd]
[pkrvmbietmlfzoi:66003] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd39542a1ca]
[pkrvmbietmlfzoi:66003] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd39542a28b]
[pkrvmbietmlfzoi:66003] [11] plumed(+0x15365)[0x55a892e49365]
[pkrvmbietmlfzoi:66003] *** End of error message ***
</pre>
{% endraw %}
