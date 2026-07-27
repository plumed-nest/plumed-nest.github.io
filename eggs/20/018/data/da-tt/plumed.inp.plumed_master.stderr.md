**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.DMXiMS/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[runnervmvrwv9:09458] *** Process received signal ***
[runnervmvrwv9:09458] Signal: Aborted (6)
[runnervmvrwv9:09458] Signal code:  (-6)
[runnervmvrwv9:09458] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9374e45330]
[runnervmvrwv9:09458] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9374e9eb2c]
[runnervmvrwv9:09458] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9374e4527e]
[runnervmvrwv9:09458] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9374e288ff]
[runnervmvrwv9:09458] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93752a5ff5]
[runnervmvrwv9:09458] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93752bb0da]
[runnervmvrwv9:09458] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93752a5a55]
[runnervmvrwv9:09458] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93752a5a6f]
[runnervmvrwv9:09458] [ 8] plumed_master(+0x146dd)[0x564b1587d6dd]
[runnervmvrwv9:09458] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9374e2a1ca]
[runnervmvrwv9:09458] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9374e2a28b]
[runnervmvrwv9:09458] [11] plumed_master(+0x15365)[0x564b1587e365]
[runnervmvrwv9:09458] *** End of error message ***
</pre>
{% endraw %}
