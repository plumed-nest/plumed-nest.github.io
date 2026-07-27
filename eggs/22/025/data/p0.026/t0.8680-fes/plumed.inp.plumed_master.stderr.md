**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.LiPqH4/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmvrwv9:07701] *** Process received signal ***
[runnervmvrwv9:07701] Signal: Aborted (6)
[runnervmvrwv9:07701] Signal code:  (-6)
[runnervmvrwv9:07701] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5234845330]
[runnervmvrwv9:07701] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f523489eb2c]
[runnervmvrwv9:07701] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f523484527e]
[runnervmvrwv9:07701] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52348288ff]
[runnervmvrwv9:07701] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5234ca5ff5]
[runnervmvrwv9:07701] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5234cbb0da]
[runnervmvrwv9:07701] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5234ca5a55]
[runnervmvrwv9:07701] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5234ca5a6f]
[runnervmvrwv9:07701] [ 8] plumed_master(+0x146dd)[0x5558cf8166dd]
[runnervmvrwv9:07701] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f523482a1ca]
[runnervmvrwv9:07701] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f523482a28b]
[runnervmvrwv9:07701] [11] plumed_master(+0x15365)[0x5558cf817365]
[runnervmvrwv9:07701] *** End of error message ***
</pre>
{% endraw %}
