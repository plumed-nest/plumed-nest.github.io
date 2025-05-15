**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.fbBpSe/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmberfyhpb9w:11157] *** Process received signal ***
[pkrvmberfyhpb9w:11157] Signal: Aborted (6)
[pkrvmberfyhpb9w:11157] Signal code:  (-6)
[pkrvmberfyhpb9w:11157] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe5c9845330]
[pkrvmberfyhpb9w:11157] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe5c989eb2c]
[pkrvmberfyhpb9w:11157] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe5c984527e]
[pkrvmberfyhpb9w:11157] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5c98288ff]
[pkrvmberfyhpb9w:11157] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5c9ca5ff5]
[pkrvmberfyhpb9w:11157] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5c9cbb0da]
[pkrvmberfyhpb9w:11157] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5c9ca5a55]
[pkrvmberfyhpb9w:11157] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5c9ca5a6f]
[pkrvmberfyhpb9w:11157] [ 8] plumed(+0x146dd)[0x560baea1c6dd]
[pkrvmberfyhpb9w:11157] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe5c982a1ca]
[pkrvmberfyhpb9w:11157] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe5c982a28b]
[pkrvmberfyhpb9w:11157] [11] plumed(+0x15365)[0x560baea1d365]
[pkrvmberfyhpb9w:11157] *** End of error message ***
</pre>
{% endraw %}
