**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16222-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.pGQnmS/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:09647] *** Process received signal ***
[pkrvmberfyhpb9w:09647] Signal: Aborted (6)
[pkrvmberfyhpb9w:09647] Signal code:  (-6)
[pkrvmberfyhpb9w:09647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19dfc45330]
[pkrvmberfyhpb9w:09647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19dfc9eb2c]
[pkrvmberfyhpb9w:09647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19dfc4527e]
[pkrvmberfyhpb9w:09647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19dfc288ff]
[pkrvmberfyhpb9w:09647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19e00a5ff5]
[pkrvmberfyhpb9w:09647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19e00bb0da]
[pkrvmberfyhpb9w:09647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19e00a5a55]
[pkrvmberfyhpb9w:09647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19e00a5a6f]
[pkrvmberfyhpb9w:09647] [ 8] plumed_master(+0x146dd)[0x56514ff566dd]
[pkrvmberfyhpb9w:09647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19dfc2a1ca]
[pkrvmberfyhpb9w:09647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19dfc2a28b]
[pkrvmberfyhpb9w:09647] [11] plumed_master(+0x15365)[0x56514ff57365]
[pkrvmberfyhpb9w:09647] *** End of error message ***
</pre>
{% endraw %}
