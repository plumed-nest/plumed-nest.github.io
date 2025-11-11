**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.rlIlwA/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmw9dnm:09146] *** Process received signal ***
[runnervmw9dnm:09146] Signal: Aborted (6)
[runnervmw9dnm:09146] Signal code:  (-6)
[runnervmw9dnm:09146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7a6c645330]
[runnervmw9dnm:09146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7a6c69eb2c]
[runnervmw9dnm:09146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7a6c64527e]
[runnervmw9dnm:09146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7a6c6288ff]
[runnervmw9dnm:09146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7a6caa5ff5]
[runnervmw9dnm:09146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7a6cabb0da]
[runnervmw9dnm:09146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7a6caa5a55]
[runnervmw9dnm:09146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7a6caa5a6f]
[runnervmw9dnm:09146] [ 8] plumed_master(+0x146dd)[0x55f42d1836dd]
[runnervmw9dnm:09146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7a6c62a1ca]
[runnervmw9dnm:09146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7a6c62a28b]
[runnervmw9dnm:09146] [11] plumed_master(+0x15365)[0x55f42d184365]
[runnervmw9dnm:09146] *** End of error message ***
</pre>
{% endraw %}
