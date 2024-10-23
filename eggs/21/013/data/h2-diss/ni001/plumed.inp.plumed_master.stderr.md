**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.KmDjvA/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:08900] *** Process received signal ***
[fv-az802-461:08900] Signal: Aborted (6)
[fv-az802-461:08900] Signal code:  (-6)
[fv-az802-461:08900] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fcc50e42520]
[fv-az802-461:08900] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fcc50e969fc]
[fv-az802-461:08900] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fcc50e42476]
[fv-az802-461:08900] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fcc50e287f3]
[fv-az802-461:08900] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fcc512a2b9e]
[fv-az802-461:08900] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fcc512ae20c]
[fv-az802-461:08900] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fcc512ae277]
[fv-az802-461:08900] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fcc512ae52b]
[fv-az802-461:08900] [ 8] plumed_master(+0x14254)[0x55f8c66f9254]
[fv-az802-461:08900] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fcc50e29d90]
[fv-az802-461:08900] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fcc50e29e40]
[fv-az802-461:08900] [11] plumed_master(+0x14eb5)[0x55f8c66f9eb5]
[fv-az802-461:08900] *** End of error message ***
</pre>
{% endraw %}
