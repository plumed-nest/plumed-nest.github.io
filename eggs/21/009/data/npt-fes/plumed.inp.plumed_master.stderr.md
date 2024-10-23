**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.M9BUE4/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[fv-az1429-284:07700] *** Process received signal ***
[fv-az1429-284:07700] Signal: Aborted (6)
[fv-az1429-284:07700] Signal code:  (-6)
[fv-az1429-284:07700] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1cb1242520]
[fv-az1429-284:07700] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1cb12969fc]
[fv-az1429-284:07700] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1cb1242476]
[fv-az1429-284:07700] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1cb12287f3]
[fv-az1429-284:07700] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1cb16a2b9e]
[fv-az1429-284:07700] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1cb16ae20c]
[fv-az1429-284:07700] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1cb16ae277]
[fv-az1429-284:07700] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1cb16ae52b]
[fv-az1429-284:07700] [ 8] plumed_master(+0x14254)[0x556b60e23254]
[fv-az1429-284:07700] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1cb1229d90]
[fv-az1429-284:07700] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1cb1229e40]
[fv-az1429-284:07700] [11] plumed_master(+0x14eb5)[0x556b60e23eb5]
[fv-az1429-284:07700] *** End of error message ***
</pre>
{% endraw %}
