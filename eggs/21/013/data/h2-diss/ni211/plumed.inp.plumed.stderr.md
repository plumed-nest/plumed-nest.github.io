**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.rRyWnB/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az802-461:09076] *** Process received signal ***
[fv-az802-461:09076] Signal: Aborted (6)
[fv-az802-461:09076] Signal code:  (-6)
[fv-az802-461:09076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1bc7442520]
[fv-az802-461:09076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1bc74969fc]
[fv-az802-461:09076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1bc7442476]
[fv-az802-461:09076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1bc74287f3]
[fv-az802-461:09076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1bc78a2b9e]
[fv-az802-461:09076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1bc78ae20c]
[fv-az802-461:09076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1bc78ae277]
[fv-az802-461:09076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1bc78ae52b]
[fv-az802-461:09076] [ 8] plumed(+0x14254)[0x55fe60e3f254]
[fv-az802-461:09076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1bc7429d90]
[fv-az802-461:09076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1bc7429e40]
[fv-az802-461:09076] [11] plumed(+0x14eb5)[0x55fe60e3feb5]
[fv-az802-461:09076] *** End of error message ***
</pre>
{% endraw %}
