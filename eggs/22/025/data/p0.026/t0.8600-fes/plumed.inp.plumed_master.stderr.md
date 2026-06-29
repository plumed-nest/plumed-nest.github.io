**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.YzfW6W/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:08565] *** Process received signal ***
[runnervmmklqx:08565] Signal: Aborted (6)
[runnervmmklqx:08565] Signal code:  (-6)
[runnervmmklqx:08565] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d9b845330]
[runnervmmklqx:08565] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d9b89eb2c]
[runnervmmklqx:08565] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d9b84527e]
[runnervmmklqx:08565] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d9b8288ff]
[runnervmmklqx:08565] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d9bca5ff5]
[runnervmmklqx:08565] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d9bcbb0da]
[runnervmmklqx:08565] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d9bca5a55]
[runnervmmklqx:08565] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d9bca5a6f]
[runnervmmklqx:08565] [ 8] plumed_master(+0x146dd)[0x5570458be6dd]
[runnervmmklqx:08565] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d9b82a1ca]
[runnervmmklqx:08565] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d9b82a28b]
[runnervmmklqx:08565] [11] plumed_master(+0x15365)[0x5570458bf365]
[runnervmmklqx:08565] *** End of error message ***
</pre>
{% endraw %}
