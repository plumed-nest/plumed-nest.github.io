**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.H5Ii6q/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmpptgkbjq6m:08989] *** Process received signal ***
[pkrvmpptgkbjq6m:08989] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08989] Signal code:  (-6)
[pkrvmpptgkbjq6m:08989] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8210045330]
[pkrvmpptgkbjq6m:08989] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f821009eb2c]
[pkrvmpptgkbjq6m:08989] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f821004527e]
[pkrvmpptgkbjq6m:08989] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82100288ff]
[pkrvmpptgkbjq6m:08989] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82104a5ff5]
[pkrvmpptgkbjq6m:08989] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82104bb0da]
[pkrvmpptgkbjq6m:08989] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82104a5a55]
[pkrvmpptgkbjq6m:08989] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82104a5a6f]
[pkrvmpptgkbjq6m:08989] [ 8] plumed(+0x146dd)[0x55d03d62f6dd]
[pkrvmpptgkbjq6m:08989] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f821002a1ca]
[pkrvmpptgkbjq6m:08989] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f821002a28b]
[pkrvmpptgkbjq6m:08989] [11] plumed(+0x15365)[0x55d03d630365]
[pkrvmpptgkbjq6m:08989] *** End of error message ***
</pre>
{% endraw %}
