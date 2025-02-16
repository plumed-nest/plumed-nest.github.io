**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8640-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Z08uEc/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az787-589:61443] *** Process received signal ***
[fv-az787-589:61443] Signal: Aborted (6)
[fv-az787-589:61443] Signal code:  (-6)
[fv-az787-589:61443] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff41a645330]
[fv-az787-589:61443] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff41a69eb2c]
[fv-az787-589:61443] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff41a64527e]
[fv-az787-589:61443] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff41a6288ff]
[fv-az787-589:61443] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff41aaa5ff5]
[fv-az787-589:61443] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff41aabb0da]
[fv-az787-589:61443] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff41aaa5a55]
[fv-az787-589:61443] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff41aaa5a6f]
[fv-az787-589:61443] [ 8] plumed(+0x146dd)[0x555def6606dd]
[fv-az787-589:61443] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff41a62a1ca]
[fv-az787-589:61443] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff41a62a28b]
[fv-az787-589:61443] [11] plumed(+0x15365)[0x555def661365]
[fv-az787-589:61443] *** End of error message ***
</pre>
{% endraw %}
