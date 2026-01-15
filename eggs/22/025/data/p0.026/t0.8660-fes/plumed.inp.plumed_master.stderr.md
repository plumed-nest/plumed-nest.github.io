**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.xw4pbL/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmi13qx:34812] *** Process received signal ***
[runnervmi13qx:34812] Signal: Aborted (6)
[runnervmi13qx:34812] Signal code:  (-6)
[runnervmi13qx:34812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8284c45330]
[runnervmi13qx:34812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8284c9eb2c]
[runnervmi13qx:34812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8284c4527e]
[runnervmi13qx:34812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8284c288ff]
[runnervmi13qx:34812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82850a5ff5]
[runnervmi13qx:34812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82850bb0da]
[runnervmi13qx:34812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82850a5a55]
[runnervmi13qx:34812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82850a5a6f]
[runnervmi13qx:34812] [ 8] plumed_master(+0x146dd)[0x55e4e36986dd]
[runnervmi13qx:34812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8284c2a1ca]
[runnervmi13qx:34812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8284c2a28b]
[runnervmi13qx:34812] [11] plumed_master(+0x15365)[0x55e4e3699365]
[runnervmi13qx:34812] *** End of error message ***
</pre>
{% endraw %}
