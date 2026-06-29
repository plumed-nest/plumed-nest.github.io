**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.S6oZ9k/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmmklqx:08953] *** Process received signal ***
[runnervmmklqx:08953] Signal: Aborted (6)
[runnervmmklqx:08953] Signal code:  (-6)
[runnervmmklqx:08953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4099445330]
[runnervmmklqx:08953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f409949eb2c]
[runnervmmklqx:08953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f409944527e]
[runnervmmklqx:08953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40994288ff]
[runnervmmklqx:08953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40998a5ff5]
[runnervmmklqx:08953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40998bb0da]
[runnervmmklqx:08953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40998a5a55]
[runnervmmklqx:08953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40998a5a6f]
[runnervmmklqx:08953] [ 8] plumed_master(+0x146dd)[0x559f2d3196dd]
[runnervmmklqx:08953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f409942a1ca]
[runnervmmklqx:08953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f409942a28b]
[runnervmmklqx:08953] [11] plumed_master(+0x15365)[0x559f2d31a365]
[runnervmmklqx:08953] *** End of error message ***
</pre>
{% endraw %}
