**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.vx4ZE0/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmxyh4eaekms:10717] *** Process received signal ***
[pkrvmxyh4eaekms:10717] Signal: Aborted (6)
[pkrvmxyh4eaekms:10717] Signal code:  (-6)
[pkrvmxyh4eaekms:10717] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbbf7245330]
[pkrvmxyh4eaekms:10717] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbbf729eb2c]
[pkrvmxyh4eaekms:10717] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbbf724527e]
[pkrvmxyh4eaekms:10717] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbbf72288ff]
[pkrvmxyh4eaekms:10717] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbbf76a5ff5]
[pkrvmxyh4eaekms:10717] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbbf76bb0da]
[pkrvmxyh4eaekms:10717] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbbf76a5a55]
[pkrvmxyh4eaekms:10717] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbbf76a5a6f]
[pkrvmxyh4eaekms:10717] [ 8] plumed(+0x146dd)[0x563c080f96dd]
[pkrvmxyh4eaekms:10717] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbbf722a1ca]
[pkrvmxyh4eaekms:10717] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbbf722a28b]
[pkrvmxyh4eaekms:10717] [11] plumed(+0x15365)[0x563c080fa365]
[pkrvmxyh4eaekms:10717] *** End of error message ***
</pre>
{% endraw %}
