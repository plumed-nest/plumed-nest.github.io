**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.BNJYa1/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmeorf1:07434] *** Process received signal ***
[runnervmeorf1:07434] Signal: Aborted (6)
[runnervmeorf1:07434] Signal code:  (-6)
[runnervmeorf1:07434] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffba4045330]
[runnervmeorf1:07434] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffba409eb2c]
[runnervmeorf1:07434] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffba404527e]
[runnervmeorf1:07434] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffba40288ff]
[runnervmeorf1:07434] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffba44a5ff5]
[runnervmeorf1:07434] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffba44bb0da]
[runnervmeorf1:07434] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffba44a5a55]
[runnervmeorf1:07434] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffba44a5a6f]
[runnervmeorf1:07434] [ 8] plumed_master(+0x146dd)[0x5636fc3796dd]
[runnervmeorf1:07434] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffba402a1ca]
[runnervmeorf1:07434] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffba402a28b]
[runnervmeorf1:07434] [11] plumed_master(+0x15365)[0x5636fc37a365]
[runnervmeorf1:07434] *** End of error message ***
</pre>
{% endraw %}
