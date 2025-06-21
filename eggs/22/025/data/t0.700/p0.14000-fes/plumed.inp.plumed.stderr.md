**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.ziqMkn/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmxyh4eaekms:10329] *** Process received signal ***
[pkrvmxyh4eaekms:10329] Signal: Aborted (6)
[pkrvmxyh4eaekms:10329] Signal code:  (-6)
[pkrvmxyh4eaekms:10329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b30445330]
[pkrvmxyh4eaekms:10329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b3049eb2c]
[pkrvmxyh4eaekms:10329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b3044527e]
[pkrvmxyh4eaekms:10329] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b304288ff]
[pkrvmxyh4eaekms:10329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b308a5ff5]
[pkrvmxyh4eaekms:10329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b308bb0da]
[pkrvmxyh4eaekms:10329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b308a5a55]
[pkrvmxyh4eaekms:10329] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b308a5a6f]
[pkrvmxyh4eaekms:10329] [ 8] plumed(+0x146dd)[0x5576a4ae36dd]
[pkrvmxyh4eaekms:10329] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b3042a1ca]
[pkrvmxyh4eaekms:10329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b3042a28b]
[pkrvmxyh4eaekms:10329] [11] plumed(+0x15365)[0x5576a4ae4365]
[pkrvmxyh4eaekms:10329] *** End of error message ***
</pre>
{% endraw %}
