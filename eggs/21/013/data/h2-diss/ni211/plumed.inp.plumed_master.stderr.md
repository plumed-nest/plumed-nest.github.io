**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.os3qzY/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmi13qx:38366] *** Process received signal ***
[runnervmi13qx:38366] Signal: Aborted (6)
[runnervmi13qx:38366] Signal code:  (-6)
[runnervmi13qx:38366] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8459845330]
[runnervmi13qx:38366] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f845989eb2c]
[runnervmi13qx:38366] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f845984527e]
[runnervmi13qx:38366] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f84598288ff]
[runnervmi13qx:38366] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8459ca5ff5]
[runnervmi13qx:38366] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8459cbb0da]
[runnervmi13qx:38366] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8459ca5a55]
[runnervmi13qx:38366] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8459ca5a6f]
[runnervmi13qx:38366] [ 8] plumed_master(+0x146dd)[0x5589b7b336dd]
[runnervmi13qx:38366] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f845982a1ca]
[runnervmi13qx:38366] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f845982a28b]
[runnervmi13qx:38366] [11] plumed_master(+0x15365)[0x5589b7b34365]
[runnervmi13qx:38366] *** End of error message ***
</pre>
{% endraw %}
