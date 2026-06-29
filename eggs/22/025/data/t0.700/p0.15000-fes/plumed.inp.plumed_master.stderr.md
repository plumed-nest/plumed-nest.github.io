**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.NV9z6e/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:09684] *** Process received signal ***
[runnervmmklqx:09684] Signal: Aborted (6)
[runnervmmklqx:09684] Signal code:  (-6)
[runnervmmklqx:09684] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a5c045330]
[runnervmmklqx:09684] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a5c09eb2c]
[runnervmmklqx:09684] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a5c04527e]
[runnervmmklqx:09684] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a5c0288ff]
[runnervmmklqx:09684] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a5c4a5ff5]
[runnervmmklqx:09684] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a5c4bb0da]
[runnervmmklqx:09684] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a5c4a5a55]
[runnervmmklqx:09684] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a5c4a5a6f]
[runnervmmklqx:09684] [ 8] plumed_master(+0x146dd)[0x55f83e1f76dd]
[runnervmmklqx:09684] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a5c02a1ca]
[runnervmmklqx:09684] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a5c02a28b]
[runnervmmklqx:09684] [11] plumed_master(+0x15365)[0x55f83e1f8365]
[runnervmmklqx:09684] *** End of error message ***
</pre>
{% endraw %}
