**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.HELzRn/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.0-dev.so ../codes/ReweightGeomFES.cpp

[fv-az530-623:09397] *** Process received signal ***
[fv-az530-623:09397] Signal: Aborted (6)
[fv-az530-623:09397] Signal code:  (-6)
[fv-az530-623:09397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3b5f442520]
[fv-az530-623:09397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3b5f4969fc]
[fv-az530-623:09397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3b5f442476]
[fv-az530-623:09397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3b5f4287f3]
[fv-az530-623:09397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3b5f8a2b9e]
[fv-az530-623:09397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3b5f8ae20c]
[fv-az530-623:09397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3b5f8ae277]
[fv-az530-623:09397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3b5f8ae52b]
[fv-az530-623:09397] [ 8] plumed_master(+0x14274)[0x560c2fedf274]
[fv-az530-623:09397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3b5f429d90]
[fv-az530-623:09397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3b5f429e40]
[fv-az530-623:09397] [11] plumed_master(+0x14ed5)[0x560c2fedfed5]
[fv-az530-623:09397] *** End of error message ***
</pre>
{% endraw %}
