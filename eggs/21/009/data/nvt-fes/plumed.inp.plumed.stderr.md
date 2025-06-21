**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lEGyVu/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10b.so ../codes/ReweightGeomFES.cpp

[pkrvmxyh4eaekms:12367] *** Process received signal ***
[pkrvmxyh4eaekms:12367] Signal: Aborted (6)
[pkrvmxyh4eaekms:12367] Signal code:  (-6)
[pkrvmxyh4eaekms:12367] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3e46e45330]
[pkrvmxyh4eaekms:12367] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3e46e9eb2c]
[pkrvmxyh4eaekms:12367] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3e46e4527e]
[pkrvmxyh4eaekms:12367] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3e46e288ff]
[pkrvmxyh4eaekms:12367] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3e472a5ff5]
[pkrvmxyh4eaekms:12367] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3e472bb0da]
[pkrvmxyh4eaekms:12367] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3e472a5a55]
[pkrvmxyh4eaekms:12367] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3e472a5a6f]
[pkrvmxyh4eaekms:12367] [ 8] plumed(+0x146dd)[0x56003f5a46dd]
[pkrvmxyh4eaekms:12367] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3e46e2a1ca]
[pkrvmxyh4eaekms:12367] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3e46e2a28b]
[pkrvmxyh4eaekms:12367] [11] plumed(+0x15365)[0x56003f5a5365]
[pkrvmxyh4eaekms:12367] *** End of error message ***
</pre>
{% endraw %}
