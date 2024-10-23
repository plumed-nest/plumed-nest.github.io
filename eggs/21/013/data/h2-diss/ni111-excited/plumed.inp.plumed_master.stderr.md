**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.wW0Urq/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:08968] *** Process received signal ***
[fv-az802-461:08968] Signal: Aborted (6)
[fv-az802-461:08968] Signal code:  (-6)
[fv-az802-461:08968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f65ef242520]
[fv-az802-461:08968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f65ef2969fc]
[fv-az802-461:08968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f65ef242476]
[fv-az802-461:08968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f65ef2287f3]
[fv-az802-461:08968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f65ef6a2b9e]
[fv-az802-461:08968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f65ef6ae20c]
[fv-az802-461:08968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f65ef6ae277]
[fv-az802-461:08968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f65ef6ae52b]
[fv-az802-461:08968] [ 8] plumed_master(+0x14254)[0x558fe1e33254]
[fv-az802-461:08968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f65ef229d90]
[fv-az802-461:08968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f65ef229e40]
[fv-az802-461:08968] [11] plumed_master(+0x14eb5)[0x558fe1e33eb5]
[fv-az802-461:08968] *** End of error message ***
</pre>
{% endraw %}
