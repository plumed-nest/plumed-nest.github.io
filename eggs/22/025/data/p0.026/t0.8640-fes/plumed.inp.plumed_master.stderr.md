**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8640-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.U09Vs0/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmvrwv9:07615] *** Process received signal ***
[runnervmvrwv9:07615] Signal: Aborted (6)
[runnervmvrwv9:07615] Signal code:  (-6)
[runnervmvrwv9:07615] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8eed045330]
[runnervmvrwv9:07615] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8eed09eb2c]
[runnervmvrwv9:07615] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8eed04527e]
[runnervmvrwv9:07615] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8eed0288ff]
[runnervmvrwv9:07615] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8eed4a5ff5]
[runnervmvrwv9:07615] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8eed4bb0da]
[runnervmvrwv9:07615] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8eed4a5a55]
[runnervmvrwv9:07615] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8eed4a5a6f]
[runnervmvrwv9:07615] [ 8] plumed_master(+0x146dd)[0x5603c68e46dd]
[runnervmvrwv9:07615] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8eed02a1ca]
[runnervmvrwv9:07615] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8eed02a28b]
[runnervmvrwv9:07615] [11] plumed_master(+0x15365)[0x5603c68e5365]
[runnervmvrwv9:07615] *** End of error message ***
</pre>
{% endraw %}
