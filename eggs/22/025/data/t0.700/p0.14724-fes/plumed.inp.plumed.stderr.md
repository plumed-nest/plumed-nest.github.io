**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14724-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.G5r5D8/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmpptgkbjq6m:09843] *** Process received signal ***
[pkrvmpptgkbjq6m:09843] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09843] Signal code:  (-6)
[pkrvmpptgkbjq6m:09843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff87f845330]
[pkrvmpptgkbjq6m:09843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff87f89eb2c]
[pkrvmpptgkbjq6m:09843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff87f84527e]
[pkrvmpptgkbjq6m:09843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff87f8288ff]
[pkrvmpptgkbjq6m:09843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff87fca5ff5]
[pkrvmpptgkbjq6m:09843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff87fcbb0da]
[pkrvmpptgkbjq6m:09843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff87fca5a55]
[pkrvmpptgkbjq6m:09843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff87fca5a6f]
[pkrvmpptgkbjq6m:09843] [ 8] plumed(+0x146dd)[0x55b1888936dd]
[pkrvmpptgkbjq6m:09843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff87f82a1ca]
[pkrvmpptgkbjq6m:09843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff87f82a28b]
[pkrvmpptgkbjq6m:09843] [11] plumed(+0x15365)[0x55b188894365]
[pkrvmpptgkbjq6m:09843] *** End of error message ***
</pre>
{% endraw %}
