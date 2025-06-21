**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.T6i7hw/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmxyh4eaekms:12909] *** Process received signal ***
[pkrvmxyh4eaekms:12909] Signal: Aborted (6)
[pkrvmxyh4eaekms:12909] Signal code:  (-6)
[pkrvmxyh4eaekms:12909] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3608045330]
[pkrvmxyh4eaekms:12909] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f360809eb2c]
[pkrvmxyh4eaekms:12909] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f360804527e]
[pkrvmxyh4eaekms:12909] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36080288ff]
[pkrvmxyh4eaekms:12909] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36084a5ff5]
[pkrvmxyh4eaekms:12909] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36084bb0da]
[pkrvmxyh4eaekms:12909] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36084a5a55]
[pkrvmxyh4eaekms:12909] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36084a5a6f]
[pkrvmxyh4eaekms:12909] [ 8] plumed(+0x146dd)[0x55a2797406dd]
[pkrvmxyh4eaekms:12909] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f360802a1ca]
[pkrvmxyh4eaekms:12909] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f360802a28b]
[pkrvmxyh4eaekms:12909] [11] plumed(+0x15365)[0x55a279741365]
[pkrvmxyh4eaekms:12909] *** End of error message ***
</pre>
{% endraw %}
