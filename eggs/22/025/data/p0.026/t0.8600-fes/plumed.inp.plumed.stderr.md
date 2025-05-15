**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.OgaKTN/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:08755] *** Process received signal ***
[pkrvmberfyhpb9w:08755] Signal: Aborted (6)
[pkrvmberfyhpb9w:08755] Signal code:  (-6)
[pkrvmberfyhpb9w:08755] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a07445330]
[pkrvmberfyhpb9w:08755] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a0749eb2c]
[pkrvmberfyhpb9w:08755] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a0744527e]
[pkrvmberfyhpb9w:08755] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a074288ff]
[pkrvmberfyhpb9w:08755] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a078a5ff5]
[pkrvmberfyhpb9w:08755] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a078bb0da]
[pkrvmberfyhpb9w:08755] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a078a5a55]
[pkrvmberfyhpb9w:08755] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a078a5a6f]
[pkrvmberfyhpb9w:08755] [ 8] plumed(+0x146dd)[0x565485c1a6dd]
[pkrvmberfyhpb9w:08755] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a0742a1ca]
[pkrvmberfyhpb9w:08755] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a0742a28b]
[pkrvmberfyhpb9w:08755] [11] plumed(+0x15365)[0x565485c1b365]
[pkrvmberfyhpb9w:08755] *** End of error message ***
</pre>
{% endraw %}
