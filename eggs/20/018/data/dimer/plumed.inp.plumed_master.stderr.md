**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.iAGF2m/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az585-767:08253] *** Process received signal ***
[fv-az585-767:08253] Signal: Aborted (6)
[fv-az585-767:08253] Signal code:  (-6)
[fv-az585-767:08253] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbab3a42520]
[fv-az585-767:08253] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbab3a969fc]
[fv-az585-767:08253] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbab3a42476]
[fv-az585-767:08253] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbab3a287f3]
[fv-az585-767:08253] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbab3ea2b9e]
[fv-az585-767:08253] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbab3eae20c]
[fv-az585-767:08253] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbab3eae277]
[fv-az585-767:08253] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbab3eae52b]
[fv-az585-767:08253] [ 8] plumed_master(+0x14254)[0x55cdc2994254]
[fv-az585-767:08253] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbab3a29d90]
[fv-az585-767:08253] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbab3a29e40]
[fv-az585-767:08253] [11] plumed_master(+0x14eb5)[0x55cdc2994eb5]
[fv-az585-767:08253] *** End of error message ***
</pre>
{% endraw %}
