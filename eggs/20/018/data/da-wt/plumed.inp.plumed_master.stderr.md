**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.RWXB91/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[runnervmvrwv9:09547] *** Process received signal ***
[runnervmvrwv9:09547] Signal: Aborted (6)
[runnervmvrwv9:09547] Signal code:  (-6)
[runnervmvrwv9:09547] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0acde45330]
[runnervmvrwv9:09547] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0acde9eb2c]
[runnervmvrwv9:09547] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0acde4527e]
[runnervmvrwv9:09547] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0acde288ff]
[runnervmvrwv9:09547] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ace2a5ff5]
[runnervmvrwv9:09547] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ace2bb0da]
[runnervmvrwv9:09547] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ace2a5a55]
[runnervmvrwv9:09547] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ace2a5a6f]
[runnervmvrwv9:09547] [ 8] plumed_master(+0x146dd)[0x55d6e594b6dd]
[runnervmvrwv9:09547] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0acde2a1ca]
[runnervmvrwv9:09547] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0acde2a28b]
[runnervmvrwv9:09547] [11] plumed_master(+0x15365)[0x55d6e594c365]
[runnervmvrwv9:09547] *** End of error message ***
</pre>
{% endraw %}
