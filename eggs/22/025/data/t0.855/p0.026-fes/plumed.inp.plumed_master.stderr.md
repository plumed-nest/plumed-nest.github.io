**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.isJUiX/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az775-215:06196] *** Process received signal ***
[fv-az775-215:06196] Signal: Aborted (6)
[fv-az775-215:06196] Signal code:  (-6)
[fv-az775-215:06196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc804c42520]
[fv-az775-215:06196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc804c969fc]
[fv-az775-215:06196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc804c42476]
[fv-az775-215:06196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc804c287f3]
[fv-az775-215:06196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc8050a2b9e]
[fv-az775-215:06196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc8050ae20c]
[fv-az775-215:06196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc8050ae277]
[fv-az775-215:06196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc8050ae52b]
[fv-az775-215:06196] [ 8] plumed_master(+0x14254)[0x55a483625254]
[fv-az775-215:06196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc804c29d90]
[fv-az775-215:06196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc804c29e40]
[fv-az775-215:06196] [11] plumed_master(+0x14eb5)[0x55a483625eb5]
[fv-az775-215:06196] *** End of error message ***
</pre>
{% endraw %}