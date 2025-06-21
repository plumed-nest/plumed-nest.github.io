**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.DxQPKg/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmxyh4eaekms:10541] *** Process received signal ***
[pkrvmxyh4eaekms:10541] Signal: Aborted (6)
[pkrvmxyh4eaekms:10541] Signal code:  (-6)
[pkrvmxyh4eaekms:10541] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4efcc45330]
[pkrvmxyh4eaekms:10541] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4efcc9eb2c]
[pkrvmxyh4eaekms:10541] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4efcc4527e]
[pkrvmxyh4eaekms:10541] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4efcc288ff]
[pkrvmxyh4eaekms:10541] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4efd0a5ff5]
[pkrvmxyh4eaekms:10541] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4efd0bb0da]
[pkrvmxyh4eaekms:10541] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4efd0a5a55]
[pkrvmxyh4eaekms:10541] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4efd0a5a6f]
[pkrvmxyh4eaekms:10541] [ 8] plumed(+0x146dd)[0x55ee5405b6dd]
[pkrvmxyh4eaekms:10541] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4efcc2a1ca]
[pkrvmxyh4eaekms:10541] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4efcc2a28b]
[pkrvmxyh4eaekms:10541] [11] plumed(+0x15365)[0x55ee5405c365]
[pkrvmxyh4eaekms:10541] *** End of error message ***
</pre>
{% endraw %}
