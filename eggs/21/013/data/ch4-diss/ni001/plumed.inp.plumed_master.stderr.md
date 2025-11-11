**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lnhRm0/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmw9dnm:10729] *** Process received signal ***
[runnervmw9dnm:10729] Signal: Aborted (6)
[runnervmw9dnm:10729] Signal code:  (-6)
[runnervmw9dnm:10729] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7623a45330]
[runnervmw9dnm:10729] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7623a9eb2c]
[runnervmw9dnm:10729] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7623a4527e]
[runnervmw9dnm:10729] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7623a288ff]
[runnervmw9dnm:10729] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7623ea5ff5]
[runnervmw9dnm:10729] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7623ebb0da]
[runnervmw9dnm:10729] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7623ea5a55]
[runnervmw9dnm:10729] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7623ea5a6f]
[runnervmw9dnm:10729] [ 8] plumed_master(+0x146dd)[0x55f1a41256dd]
[runnervmw9dnm:10729] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7623a2a1ca]
[runnervmw9dnm:10729] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7623a2a28b]
[runnervmw9dnm:10729] [11] plumed_master(+0x15365)[0x55f1a4126365]
[runnervmw9dnm:10729] *** End of error message ***
</pre>
{% endraw %}
