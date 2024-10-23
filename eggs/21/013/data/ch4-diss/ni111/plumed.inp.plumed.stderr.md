**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.F9dAFa/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:09533] *** Process received signal ***
[fv-az802-461:09533] Signal: Aborted (6)
[fv-az802-461:09533] Signal code:  (-6)
[fv-az802-461:09533] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6e6a842520]
[fv-az802-461:09533] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6e6a8969fc]
[fv-az802-461:09533] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6e6a842476]
[fv-az802-461:09533] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6e6a8287f3]
[fv-az802-461:09533] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6e6aca2b9e]
[fv-az802-461:09533] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6e6acae20c]
[fv-az802-461:09533] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6e6acae277]
[fv-az802-461:09533] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6e6acae52b]
[fv-az802-461:09533] [ 8] plumed(+0x14254)[0x56542a0bc254]
[fv-az802-461:09533] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6e6a829d90]
[fv-az802-461:09533] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6e6a829e40]
[fv-az802-461:09533] [11] plumed(+0x14eb5)[0x56542a0bceb5]
[fv-az802-461:09533] *** End of error message ***
</pre>
{% endraw %}
