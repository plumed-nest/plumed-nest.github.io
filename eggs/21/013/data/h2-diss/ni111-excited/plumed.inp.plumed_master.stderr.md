**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.q4eaSB/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1530-541:08175] *** Process received signal ***
[fv-az1530-541:08175] Signal: Aborted (6)
[fv-az1530-541:08175] Signal code:  (-6)
[fv-az1530-541:08175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0ce0442520]
[fv-az1530-541:08175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0ce04969fc]
[fv-az1530-541:08175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0ce0442476]
[fv-az1530-541:08175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0ce04287f3]
[fv-az1530-541:08175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0ce08a2b9e]
[fv-az1530-541:08175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0ce08ae20c]
[fv-az1530-541:08175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0ce08ae277]
[fv-az1530-541:08175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0ce08ae52b]
[fv-az1530-541:08175] [ 8] plumed_master(+0x14274)[0x56064e1d8274]
[fv-az1530-541:08175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0ce0429d90]
[fv-az1530-541:08175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0ce0429e40]
[fv-az1530-541:08175] [11] plumed_master(+0x14ed5)[0x56064e1d8ed5]
[fv-az1530-541:08175] *** End of error message ***
</pre>
{% endraw %}
