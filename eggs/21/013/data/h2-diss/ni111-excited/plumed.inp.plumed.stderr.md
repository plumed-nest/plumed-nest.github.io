**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Q14MPC/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:08941] *** Process received signal ***
[fv-az802-461:08941] Signal: Aborted (6)
[fv-az802-461:08941] Signal code:  (-6)
[fv-az802-461:08941] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f868ca42520]
[fv-az802-461:08941] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f868ca969fc]
[fv-az802-461:08941] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f868ca42476]
[fv-az802-461:08941] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f868ca287f3]
[fv-az802-461:08941] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f868cea2b9e]
[fv-az802-461:08941] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f868ceae20c]
[fv-az802-461:08941] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f868ceae277]
[fv-az802-461:08941] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f868ceae52b]
[fv-az802-461:08941] [ 8] plumed(+0x14254)[0x56232a6ed254]
[fv-az802-461:08941] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f868ca29d90]
[fv-az802-461:08941] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f868ca29e40]
[fv-az802-461:08941] [11] plumed(+0x14eb5)[0x56232a6edeb5]
[fv-az802-461:08941] *** End of error message ***
</pre>
{% endraw %}
