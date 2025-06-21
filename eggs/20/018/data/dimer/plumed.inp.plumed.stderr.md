**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.dRIgbK/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmxyh4eaekms:12822] *** Process received signal ***
[pkrvmxyh4eaekms:12822] Signal: Aborted (6)
[pkrvmxyh4eaekms:12822] Signal code:  (-6)
[pkrvmxyh4eaekms:12822] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6711445330]
[pkrvmxyh4eaekms:12822] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f671149eb2c]
[pkrvmxyh4eaekms:12822] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f671144527e]
[pkrvmxyh4eaekms:12822] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67114288ff]
[pkrvmxyh4eaekms:12822] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67118a5ff5]
[pkrvmxyh4eaekms:12822] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67118bb0da]
[pkrvmxyh4eaekms:12822] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67118a5a55]
[pkrvmxyh4eaekms:12822] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67118a5a6f]
[pkrvmxyh4eaekms:12822] [ 8] plumed(+0x146dd)[0x5642b35ce6dd]
[pkrvmxyh4eaekms:12822] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f671142a1ca]
[pkrvmxyh4eaekms:12822] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f671142a28b]
[pkrvmxyh4eaekms:12822] [11] plumed(+0x15365)[0x5642b35cf365]
[pkrvmxyh4eaekms:12822] *** End of error message ***
</pre>
{% endraw %}
