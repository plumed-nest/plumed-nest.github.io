**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16627-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.oWmiJt/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az775-215:05831] *** Process received signal ***
[fv-az775-215:05831] Signal: Aborted (6)
[fv-az775-215:05831] Signal code:  (-6)
[fv-az775-215:05831] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6114642520]
[fv-az775-215:05831] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f61146969fc]
[fv-az775-215:05831] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6114642476]
[fv-az775-215:05831] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f61146287f3]
[fv-az775-215:05831] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6114aa2b9e]
[fv-az775-215:05831] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6114aae20c]
[fv-az775-215:05831] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6114aae277]
[fv-az775-215:05831] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6114aae52b]
[fv-az775-215:05831] [ 8] plumed(+0x14254)[0x563183b3b254]
[fv-az775-215:05831] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6114629d90]
[fv-az775-215:05831] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6114629e40]
[fv-az775-215:05831] [11] plumed(+0x14eb5)[0x563183b3beb5]
[fv-az775-215:05831] *** End of error message ***
</pre>
{% endraw %}
