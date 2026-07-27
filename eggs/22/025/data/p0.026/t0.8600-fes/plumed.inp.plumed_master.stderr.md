**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Pu6krW/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmvrwv9:07351] *** Process received signal ***
[runnervmvrwv9:07351] Signal: Aborted (6)
[runnervmvrwv9:07351] Signal code:  (-6)
[runnervmvrwv9:07351] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff665a45330]
[runnervmvrwv9:07351] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff665a9eb2c]
[runnervmvrwv9:07351] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff665a4527e]
[runnervmvrwv9:07351] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff665a288ff]
[runnervmvrwv9:07351] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff665ea5ff5]
[runnervmvrwv9:07351] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff665ebb0da]
[runnervmvrwv9:07351] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff665ea5a55]
[runnervmvrwv9:07351] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff665ea5a6f]
[runnervmvrwv9:07351] [ 8] plumed_master(+0x146dd)[0x560f0c51c6dd]
[runnervmvrwv9:07351] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff665a2a1ca]
[runnervmvrwv9:07351] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff665a2a28b]
[runnervmvrwv9:07351] [11] plumed_master(+0x15365)[0x560f0c51d365]
[runnervmvrwv9:07351] *** End of error message ***
</pre>
{% endraw %}
