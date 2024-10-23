**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.o4hnSI/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:09398] *** Process received signal ***
[fv-az802-461:09398] Signal: Aborted (6)
[fv-az802-461:09398] Signal code:  (-6)
[fv-az802-461:09398] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7285042520]
[fv-az802-461:09398] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f72850969fc]
[fv-az802-461:09398] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7285042476]
[fv-az802-461:09398] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f72850287f3]
[fv-az802-461:09398] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f72854a2b9e]
[fv-az802-461:09398] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f72854ae20c]
[fv-az802-461:09398] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f72854ae277]
[fv-az802-461:09398] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f72854ae52b]
[fv-az802-461:09398] [ 8] plumed(+0x14254)[0x55fd55832254]
[fv-az802-461:09398] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7285029d90]
[fv-az802-461:09398] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7285029e40]
[fv-az802-461:09398] [11] plumed(+0x14eb5)[0x55fd55832eb5]
[fv-az802-461:09398] *** End of error message ***
</pre>
{% endraw %}
