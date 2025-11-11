**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.gTosU8/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmw9dnm:08206] *** Process received signal ***
[runnervmw9dnm:08206] Signal: Aborted (6)
[runnervmw9dnm:08206] Signal code:  (-6)
[runnervmw9dnm:08206] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6749645330]
[runnervmw9dnm:08206] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f674969eb2c]
[runnervmw9dnm:08206] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f674964527e]
[runnervmw9dnm:08206] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67496288ff]
[runnervmw9dnm:08206] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6749aa5ff5]
[runnervmw9dnm:08206] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6749abb0da]
[runnervmw9dnm:08206] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6749aa5a55]
[runnervmw9dnm:08206] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6749aa5a6f]
[runnervmw9dnm:08206] [ 8] plumed_master(+0x146dd)[0x56267dd7d6dd]
[runnervmw9dnm:08206] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f674962a1ca]
[runnervmw9dnm:08206] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f674962a28b]
[runnervmw9dnm:08206] [11] plumed_master(+0x15365)[0x56267dd7e365]
[runnervmw9dnm:08206] *** End of error message ***
</pre>
{% endraw %}
