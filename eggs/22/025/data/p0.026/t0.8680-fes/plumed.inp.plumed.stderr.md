**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.FEdY3C/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:09110] *** Process received signal ***
[pkrvmberfyhpb9w:09110] Signal: Aborted (6)
[pkrvmberfyhpb9w:09110] Signal code:  (-6)
[pkrvmberfyhpb9w:09110] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f39445330]
[pkrvmberfyhpb9w:09110] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f3949eb2c]
[pkrvmberfyhpb9w:09110] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f3944527e]
[pkrvmberfyhpb9w:09110] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f394288ff]
[pkrvmberfyhpb9w:09110] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f398a5ff5]
[pkrvmberfyhpb9w:09110] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f398bb0da]
[pkrvmberfyhpb9w:09110] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f398a5a55]
[pkrvmberfyhpb9w:09110] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f398a5a6f]
[pkrvmberfyhpb9w:09110] [ 8] plumed(+0x146dd)[0x55de326366dd]
[pkrvmberfyhpb9w:09110] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f3942a1ca]
[pkrvmberfyhpb9w:09110] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f3942a28b]
[pkrvmberfyhpb9w:09110] [11] plumed(+0x15365)[0x55de32637365]
[pkrvmberfyhpb9w:09110] *** End of error message ***
</pre>
{% endraw %}
