**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.MXwgLE/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:11248] *** Process received signal ***
[pkrvmberfyhpb9w:11248] Signal: Aborted (6)
[pkrvmberfyhpb9w:11248] Signal code:  (-6)
[pkrvmberfyhpb9w:11248] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdb94a45330]
[pkrvmberfyhpb9w:11248] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdb94a9eb2c]
[pkrvmberfyhpb9w:11248] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdb94a4527e]
[pkrvmberfyhpb9w:11248] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdb94a288ff]
[pkrvmberfyhpb9w:11248] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdb94ea5ff5]
[pkrvmberfyhpb9w:11248] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdb94ebb0da]
[pkrvmberfyhpb9w:11248] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdb94ea5a55]
[pkrvmberfyhpb9w:11248] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdb94ea5a6f]
[pkrvmberfyhpb9w:11248] [ 8] plumed(+0x146dd)[0x557b788956dd]
[pkrvmberfyhpb9w:11248] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdb94a2a1ca]
[pkrvmberfyhpb9w:11248] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdb94a2a28b]
[pkrvmberfyhpb9w:11248] [11] plumed(+0x15365)[0x557b78896365]
[pkrvmberfyhpb9w:11248] *** End of error message ***
</pre>
{% endraw %}
