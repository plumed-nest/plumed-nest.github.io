**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8640-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.6HiThF/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmw9dnm:08293] *** Process received signal ***
[runnervmw9dnm:08293] Signal: Aborted (6)
[runnervmw9dnm:08293] Signal code:  (-6)
[runnervmw9dnm:08293] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1792a45330]
[runnervmw9dnm:08293] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1792a9eb2c]
[runnervmw9dnm:08293] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1792a4527e]
[runnervmw9dnm:08293] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1792a288ff]
[runnervmw9dnm:08293] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1792ea5ff5]
[runnervmw9dnm:08293] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1792ebb0da]
[runnervmw9dnm:08293] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1792ea5a55]
[runnervmw9dnm:08293] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1792ea5a6f]
[runnervmw9dnm:08293] [ 8] plumed_master(+0x146dd)[0x563a932c06dd]
[runnervmw9dnm:08293] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1792a2a1ca]
[runnervmw9dnm:08293] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1792a2a28b]
[runnervmw9dnm:08293] [11] plumed_master(+0x15365)[0x563a932c1365]
[runnervmw9dnm:08293] *** End of error message ***
</pre>
{% endraw %}
