**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.9dWlbm/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[runnervmmklqx:11556] *** Process received signal ***
[runnervmmklqx:11556] Signal: Aborted (6)
[runnervmmklqx:11556] Signal code:  (-6)
[runnervmmklqx:11556] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f76c2245330]
[runnervmmklqx:11556] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f76c229eb2c]
[runnervmmklqx:11556] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f76c224527e]
[runnervmmklqx:11556] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76c22288ff]
[runnervmmklqx:11556] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76c26a5ff5]
[runnervmmklqx:11556] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76c26bb0da]
[runnervmmklqx:11556] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76c26a5a55]
[runnervmmklqx:11556] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76c26a5a6f]
[runnervmmklqx:11556] [ 8] plumed_master(+0x146dd)[0x5612982c16dd]
[runnervmmklqx:11556] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f76c222a1ca]
[runnervmmklqx:11556] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f76c222a28b]
[runnervmmklqx:11556] [11] plumed_master(+0x15365)[0x5612982c2365]
[runnervmmklqx:11556] *** End of error message ***
</pre>
{% endraw %}
