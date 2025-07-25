**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.4zlr7Z/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmpptgkbjq6m:08902] *** Process received signal ***
[pkrvmpptgkbjq6m:08902] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08902] Signal code:  (-6)
[pkrvmpptgkbjq6m:08902] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f32c3045330]
[pkrvmpptgkbjq6m:08902] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f32c309eb2c]
[pkrvmpptgkbjq6m:08902] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f32c304527e]
[pkrvmpptgkbjq6m:08902] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32c30288ff]
[pkrvmpptgkbjq6m:08902] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32c34a5ff5]
[pkrvmpptgkbjq6m:08902] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32c34bb0da]
[pkrvmpptgkbjq6m:08902] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32c34a5a55]
[pkrvmpptgkbjq6m:08902] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32c34a5a6f]
[pkrvmpptgkbjq6m:08902] [ 8] plumed(+0x146dd)[0x5638f330a6dd]
[pkrvmpptgkbjq6m:08902] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f32c302a1ca]
[pkrvmpptgkbjq6m:08902] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f32c302a28b]
[pkrvmpptgkbjq6m:08902] [11] plumed(+0x15365)[0x5638f330b365]
[pkrvmpptgkbjq6m:08902] *** End of error message ***
</pre>
{% endraw %}
