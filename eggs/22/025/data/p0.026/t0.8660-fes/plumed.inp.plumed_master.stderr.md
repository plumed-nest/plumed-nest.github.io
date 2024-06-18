**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.AfeTLV/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1771-923:05880] *** Process received signal ***
[fv-az1771-923:05880] Signal: Aborted (6)
[fv-az1771-923:05880] Signal code:  (-6)
[fv-az1771-923:05880] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f85c0842520]
[fv-az1771-923:05880] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f85c08969fc]
[fv-az1771-923:05880] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f85c0842476]
[fv-az1771-923:05880] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f85c08287f3]
[fv-az1771-923:05880] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f85c0ca2b9e]
[fv-az1771-923:05880] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f85c0cae20c]
[fv-az1771-923:05880] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f85c0cae277]
[fv-az1771-923:05880] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f85c0cae52b]
[fv-az1771-923:05880] [ 8] plumed_master(+0x14274)[0x560b4df9c274]
[fv-az1771-923:05880] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f85c0829d90]
[fv-az1771-923:05880] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f85c0829e40]
[fv-az1771-923:05880] [11] plumed_master(+0x14ed5)[0x560b4df9ced5]
[fv-az1771-923:05880] *** End of error message ***
</pre>
{% endraw %}
