**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.k7WpBI/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az787-589:62395] *** Process received signal ***
[fv-az787-589:62395] Signal: Aborted (6)
[fv-az787-589:62395] Signal code:  (-6)
[fv-az787-589:62395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbbc9a45330]
[fv-az787-589:62395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbbc9a9eb2c]
[fv-az787-589:62395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbbc9a4527e]
[fv-az787-589:62395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbbc9a288ff]
[fv-az787-589:62395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbbc9ea5ff5]
[fv-az787-589:62395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbbc9ebb0da]
[fv-az787-589:62395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbbc9ea5a55]
[fv-az787-589:62395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbbc9ea5a6f]
[fv-az787-589:62395] [ 8] plumed(+0x146dd)[0x55d3024506dd]
[fv-az787-589:62395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbbc9a2a1ca]
[fv-az787-589:62395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbbc9a2a28b]
[fv-az787-589:62395] [11] plumed(+0x15365)[0x55d302451365]
[fv-az787-589:62395] *** End of error message ***
</pre>
{% endraw %}
