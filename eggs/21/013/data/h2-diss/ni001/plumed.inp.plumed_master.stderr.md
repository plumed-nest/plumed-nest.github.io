**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.7IkteQ/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:10853] *** Process received signal ***
[pkrvmberfyhpb9w:10853] Signal: Aborted (6)
[pkrvmberfyhpb9w:10853] Signal code:  (-6)
[pkrvmberfyhpb9w:10853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2344a45330]
[pkrvmberfyhpb9w:10853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2344a9eb2c]
[pkrvmberfyhpb9w:10853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2344a4527e]
[pkrvmberfyhpb9w:10853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2344a288ff]
[pkrvmberfyhpb9w:10853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2344ea5ff5]
[pkrvmberfyhpb9w:10853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2344ebb0da]
[pkrvmberfyhpb9w:10853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2344ea5a55]
[pkrvmberfyhpb9w:10853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2344ea5a6f]
[pkrvmberfyhpb9w:10853] [ 8] plumed_master(+0x146dd)[0x55e39e1c26dd]
[pkrvmberfyhpb9w:10853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2344a2a1ca]
[pkrvmberfyhpb9w:10853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2344a2a28b]
[pkrvmberfyhpb9w:10853] [11] plumed_master(+0x15365)[0x55e39e1c3365]
[pkrvmberfyhpb9w:10853] *** End of error message ***
</pre>
{% endraw %}
