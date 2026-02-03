**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.L0hpB6/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmkj6or:08225] *** Process received signal ***
[runnervmkj6or:08225] Signal: Aborted (6)
[runnervmkj6or:08225] Signal code:  (-6)
[runnervmkj6or:08225] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ac6a45330]
[runnervmkj6or:08225] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ac6a9eb2c]
[runnervmkj6or:08225] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ac6a4527e]
[runnervmkj6or:08225] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ac6a288ff]
[runnervmkj6or:08225] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ac6ea5ff5]
[runnervmkj6or:08225] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ac6ebb0da]
[runnervmkj6or:08225] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ac6ea5a55]
[runnervmkj6or:08225] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ac6ea5a6f]
[runnervmkj6or:08225] [ 8] plumed(+0x146dd)[0x5633026f06dd]
[runnervmkj6or:08225] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ac6a2a1ca]
[runnervmkj6or:08225] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ac6a2a28b]
[runnervmkj6or:08225] [11] plumed(+0x15365)[0x5633026f1365]
[runnervmkj6or:08225] *** End of error message ***
</pre>
{% endraw %}
