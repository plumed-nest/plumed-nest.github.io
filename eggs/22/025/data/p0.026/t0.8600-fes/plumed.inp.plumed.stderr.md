**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.3vitV5/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az775-215:05178] *** Process received signal ***
[fv-az775-215:05178] Signal: Aborted (6)
[fv-az775-215:05178] Signal code:  (-6)
[fv-az775-215:05178] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f849e242520]
[fv-az775-215:05178] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f849e2969fc]
[fv-az775-215:05178] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f849e242476]
[fv-az775-215:05178] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f849e2287f3]
[fv-az775-215:05178] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f849e6a2b9e]
[fv-az775-215:05178] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f849e6ae20c]
[fv-az775-215:05178] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f849e6ae277]
[fv-az775-215:05178] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f849e6ae52b]
[fv-az775-215:05178] [ 8] plumed(+0x14254)[0x562d5e436254]
[fv-az775-215:05178] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f849e229d90]
[fv-az775-215:05178] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f849e229e40]
[fv-az775-215:05178] [11] plumed(+0x14eb5)[0x562d5e436eb5]
[fv-az775-215:05178] *** End of error message ***
</pre>
{% endraw %}
