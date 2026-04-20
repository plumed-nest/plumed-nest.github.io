**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.2GO8Uy/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmeorf1:07696] *** Process received signal ***
[runnervmeorf1:07696] Signal: Aborted (6)
[runnervmeorf1:07696] Signal code:  (-6)
[runnervmeorf1:07696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a44445330]
[runnervmeorf1:07696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a4449eb2c]
[runnervmeorf1:07696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a4444527e]
[runnervmeorf1:07696] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a444288ff]
[runnervmeorf1:07696] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a448a5ff5]
[runnervmeorf1:07696] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a448bb0da]
[runnervmeorf1:07696] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a448a5a55]
[runnervmeorf1:07696] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a448a5a6f]
[runnervmeorf1:07696] [ 8] plumed_master(+0x146dd)[0x562323bf56dd]
[runnervmeorf1:07696] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a4442a1ca]
[runnervmeorf1:07696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a4442a28b]
[runnervmeorf1:07696] [11] plumed_master(+0x15365)[0x562323bf6365]
[runnervmeorf1:07696] *** End of error message ***
</pre>
{% endraw %}
