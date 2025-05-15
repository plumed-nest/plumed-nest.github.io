**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.07BVYe/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:10672] *** Process received signal ***
[pkrvmberfyhpb9w:10672] Signal: Aborted (6)
[pkrvmberfyhpb9w:10672] Signal code:  (-6)
[pkrvmberfyhpb9w:10672] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc077045330]
[pkrvmberfyhpb9w:10672] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc07709eb2c]
[pkrvmberfyhpb9w:10672] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc07704527e]
[pkrvmberfyhpb9w:10672] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0770288ff]
[pkrvmberfyhpb9w:10672] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0774a5ff5]
[pkrvmberfyhpb9w:10672] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0774bb0da]
[pkrvmberfyhpb9w:10672] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0774a5a55]
[pkrvmberfyhpb9w:10672] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0774a5a6f]
[pkrvmberfyhpb9w:10672] [ 8] plumed_master(+0x146dd)[0x557f8c31e6dd]
[pkrvmberfyhpb9w:10672] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc07702a1ca]
[pkrvmberfyhpb9w:10672] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc07702a28b]
[pkrvmberfyhpb9w:10672] [11] plumed_master(+0x15365)[0x557f8c31f365]
[pkrvmberfyhpb9w:10672] *** End of error message ***
</pre>
{% endraw %}
