**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.8owtcw/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:11282] *** Process received signal ***
[pkrvmberfyhpb9w:11282] Signal: Aborted (6)
[pkrvmberfyhpb9w:11282] Signal code:  (-6)
[pkrvmberfyhpb9w:11282] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f44e4c45330]
[pkrvmberfyhpb9w:11282] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f44e4c9eb2c]
[pkrvmberfyhpb9w:11282] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f44e4c4527e]
[pkrvmberfyhpb9w:11282] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f44e4c288ff]
[pkrvmberfyhpb9w:11282] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44e50a5ff5]
[pkrvmberfyhpb9w:11282] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44e50bb0da]
[pkrvmberfyhpb9w:11282] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44e50a5a55]
[pkrvmberfyhpb9w:11282] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44e50a5a6f]
[pkrvmberfyhpb9w:11282] [ 8] plumed_master(+0x146dd)[0x556942e216dd]
[pkrvmberfyhpb9w:11282] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f44e4c2a1ca]
[pkrvmberfyhpb9w:11282] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f44e4c2a28b]
[pkrvmberfyhpb9w:11282] [11] plumed_master(+0x15365)[0x556942e22365]
[pkrvmberfyhpb9w:11282] *** End of error message ***
</pre>
{% endraw %}
