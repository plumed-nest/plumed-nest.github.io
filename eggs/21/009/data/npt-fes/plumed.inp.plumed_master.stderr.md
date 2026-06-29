**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.RROW1U/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[runnervmmklqx:09393] *** Process received signal ***
[runnervmmklqx:09393] Signal: Aborted (6)
[runnervmmklqx:09393] Signal code:  (-6)
[runnervmmklqx:09393] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc9dce45330]
[runnervmmklqx:09393] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc9dce9eb2c]
[runnervmmklqx:09393] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc9dce4527e]
[runnervmmklqx:09393] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9dce288ff]
[runnervmmklqx:09393] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9dd2a5ff5]
[runnervmmklqx:09393] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9dd2bb0da]
[runnervmmklqx:09393] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9dd2a5a55]
[runnervmmklqx:09393] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9dd2a5a6f]
[runnervmmklqx:09393] [ 8] plumed_master(+0x146dd)[0x5589ac3d16dd]
[runnervmmklqx:09393] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc9dce2a1ca]
[runnervmmklqx:09393] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc9dce2a28b]
[runnervmmklqx:09393] [11] plumed_master(+0x15365)[0x5589ac3d2365]
[runnervmmklqx:09393] *** End of error message ***
</pre>
{% endraw %}
