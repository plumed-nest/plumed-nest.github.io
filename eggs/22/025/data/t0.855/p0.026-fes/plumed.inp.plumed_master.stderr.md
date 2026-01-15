**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.XL0xNn/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmi13qx:35935] *** Process received signal ***
[runnervmi13qx:35935] Signal: Aborted (6)
[runnervmi13qx:35935] Signal code:  (-6)
[runnervmi13qx:35935] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd7c4645330]
[runnervmi13qx:35935] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd7c469eb2c]
[runnervmi13qx:35935] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd7c464527e]
[runnervmi13qx:35935] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7c46288ff]
[runnervmi13qx:35935] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7c4aa5ff5]
[runnervmi13qx:35935] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7c4abb0da]
[runnervmi13qx:35935] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7c4aa5a55]
[runnervmi13qx:35935] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7c4aa5a6f]
[runnervmi13qx:35935] [ 8] plumed_master(+0x146dd)[0x56482ca186dd]
[runnervmi13qx:35935] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd7c462a1ca]
[runnervmi13qx:35935] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd7c462a28b]
[runnervmi13qx:35935] [11] plumed_master(+0x15365)[0x56482ca19365]
[runnervmi13qx:35935] *** End of error message ***
</pre>
{% endraw %}
