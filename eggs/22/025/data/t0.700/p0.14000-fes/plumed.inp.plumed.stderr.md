**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.I9n6gL/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az787-589:61864] *** Process received signal ***
[fv-az787-589:61864] Signal: Aborted (6)
[fv-az787-589:61864] Signal code:  (-6)
[fv-az787-589:61864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1569c45330]
[fv-az787-589:61864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1569c9eb2c]
[fv-az787-589:61864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1569c4527e]
[fv-az787-589:61864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1569c288ff]
[fv-az787-589:61864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f156a0a5ff5]
[fv-az787-589:61864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f156a0bb0da]
[fv-az787-589:61864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f156a0a5a55]
[fv-az787-589:61864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f156a0a5a6f]
[fv-az787-589:61864] [ 8] plumed(+0x146dd)[0x55777d83b6dd]
[fv-az787-589:61864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1569c2a1ca]
[fv-az787-589:61864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1569c2a28b]
[fv-az787-589:61864] [11] plumed(+0x15365)[0x55777d83c365]
[fv-az787-589:61864] *** End of error message ***
</pre>
{% endraw %}
