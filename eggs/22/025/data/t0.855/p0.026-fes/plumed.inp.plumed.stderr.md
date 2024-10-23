**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.w8772v/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az775-215:06170] *** Process received signal ***
[fv-az775-215:06170] Signal: Aborted (6)
[fv-az775-215:06170] Signal code:  (-6)
[fv-az775-215:06170] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6315a42520]
[fv-az775-215:06170] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6315a969fc]
[fv-az775-215:06170] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6315a42476]
[fv-az775-215:06170] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6315a287f3]
[fv-az775-215:06170] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6315ea2b9e]
[fv-az775-215:06170] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6315eae20c]
[fv-az775-215:06170] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6315eae277]
[fv-az775-215:06170] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6315eae52b]
[fv-az775-215:06170] [ 8] plumed(+0x14254)[0x55b9f33ad254]
[fv-az775-215:06170] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6315a29d90]
[fv-az775-215:06170] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6315a29e40]
[fv-az775-215:06170] [11] plumed(+0x14eb5)[0x55b9f33adeb5]
[fv-az775-215:06170] *** End of error message ***
</pre>
{% endraw %}
