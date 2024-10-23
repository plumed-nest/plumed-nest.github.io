**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.cLyMZJ/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[fv-az1429-284:07829] *** Process received signal ***
[fv-az1429-284:07829] Signal: Aborted (6)
[fv-az1429-284:07829] Signal code:  (-6)
[fv-az1429-284:07829] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6ed8c42520]
[fv-az1429-284:07829] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6ed8c969fc]
[fv-az1429-284:07829] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6ed8c42476]
[fv-az1429-284:07829] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6ed8c287f3]
[fv-az1429-284:07829] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6ed90a2b9e]
[fv-az1429-284:07829] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6ed90ae20c]
[fv-az1429-284:07829] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6ed90ae277]
[fv-az1429-284:07829] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6ed90ae52b]
[fv-az1429-284:07829] [ 8] plumed_master(+0x14254)[0x55fcae21a254]
[fv-az1429-284:07829] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6ed8c29d90]
[fv-az1429-284:07829] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6ed8c29e40]
[fv-az1429-284:07829] [11] plumed_master(+0x14eb5)[0x55fcae21aeb5]
[fv-az1429-284:07829] *** End of error message ***
</pre>
{% endraw %}
