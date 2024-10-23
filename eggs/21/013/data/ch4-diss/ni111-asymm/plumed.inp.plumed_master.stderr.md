**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.SAW2tP/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:09357] *** Process received signal ***
[fv-az802-461:09357] Signal: Aborted (6)
[fv-az802-461:09357] Signal code:  (-6)
[fv-az802-461:09357] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f686ea42520]
[fv-az802-461:09357] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f686ea969fc]
[fv-az802-461:09357] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f686ea42476]
[fv-az802-461:09357] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f686ea287f3]
[fv-az802-461:09357] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f686eea2b9e]
[fv-az802-461:09357] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f686eeae20c]
[fv-az802-461:09357] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f686eeae277]
[fv-az802-461:09357] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f686eeae52b]
[fv-az802-461:09357] [ 8] plumed_master(+0x14254)[0x55d7adfc2254]
[fv-az802-461:09357] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f686ea29d90]
[fv-az802-461:09357] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f686ea29e40]
[fv-az802-461:09357] [11] plumed_master(+0x14eb5)[0x55d7adfc2eb5]
[fv-az802-461:09357] *** End of error message ***
</pre>
{% endraw %}
