**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-bend/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.YIpxJP/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:09600] *** Process received signal ***
[fv-az802-461:09600] Signal: Aborted (6)
[fv-az802-461:09600] Signal code:  (-6)
[fv-az802-461:09600] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f81dc842520]
[fv-az802-461:09600] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f81dc8969fc]
[fv-az802-461:09600] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f81dc842476]
[fv-az802-461:09600] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f81dc8287f3]
[fv-az802-461:09600] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f81dcca2b9e]
[fv-az802-461:09600] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f81dccae20c]
[fv-az802-461:09600] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f81dccae277]
[fv-az802-461:09600] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f81dccae52b]
[fv-az802-461:09600] [ 8] plumed(+0x14254)[0x55b0f4de6254]
[fv-az802-461:09600] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f81dc829d90]
[fv-az802-461:09600] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f81dc829e40]
[fv-az802-461:09600] [11] plumed(+0x14eb5)[0x55b0f4de6eb5]
[fv-az802-461:09600] *** End of error message ***
</pre>
{% endraw %}
