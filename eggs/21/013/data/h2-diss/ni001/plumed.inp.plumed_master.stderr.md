**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.az9n63/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmmklqx:08323] *** Process received signal ***
[runnervmmklqx:08323] Signal: Aborted (6)
[runnervmmklqx:08323] Signal code:  (-6)
[runnervmmklqx:08323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95f5e45330]
[runnervmmklqx:08323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95f5e9eb2c]
[runnervmmklqx:08323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95f5e4527e]
[runnervmmklqx:08323] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95f5e288ff]
[runnervmmklqx:08323] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95f62a5ff5]
[runnervmmklqx:08323] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95f62bb0da]
[runnervmmklqx:08323] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95f62a5a55]
[runnervmmklqx:08323] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95f62a5a6f]
[runnervmmklqx:08323] [ 8] plumed_master(+0x146dd)[0x5619d064b6dd]
[runnervmmklqx:08323] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95f5e2a1ca]
[runnervmmklqx:08323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95f5e2a28b]
[runnervmmklqx:08323] [11] plumed_master(+0x15365)[0x5619d064c365]
[runnervmmklqx:08323] *** End of error message ***
</pre>
{% endraw %}
