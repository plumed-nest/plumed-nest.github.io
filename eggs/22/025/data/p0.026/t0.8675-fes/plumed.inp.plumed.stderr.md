**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.gu9W94/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az775-215:05312] *** Process received signal ***
[fv-az775-215:05312] Signal: Aborted (6)
[fv-az775-215:05312] Signal code:  (-6)
[fv-az775-215:05312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7feac2e42520]
[fv-az775-215:05312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7feac2e969fc]
[fv-az775-215:05312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7feac2e42476]
[fv-az775-215:05312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7feac2e287f3]
[fv-az775-215:05312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7feac32a2b9e]
[fv-az775-215:05312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7feac32ae20c]
[fv-az775-215:05312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7feac32ae277]
[fv-az775-215:05312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7feac32ae52b]
[fv-az775-215:05312] [ 8] plumed(+0x14254)[0x55a5b1422254]
[fv-az775-215:05312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7feac2e29d90]
[fv-az775-215:05312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7feac2e29e40]
[fv-az775-215:05312] [11] plumed(+0x14eb5)[0x55a5b1422eb5]
[fv-az775-215:05312] *** End of error message ***
</pre>
{% endraw %}
