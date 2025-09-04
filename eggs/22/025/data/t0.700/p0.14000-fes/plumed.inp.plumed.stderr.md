**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.x6ErIS/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:08919] *** Process received signal ***
[pkrvm7jw40e0xgp:08919] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08919] Signal code:  (-6)
[pkrvm7jw40e0xgp:08919] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbde8245330]
[pkrvm7jw40e0xgp:08919] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbde829eb2c]
[pkrvm7jw40e0xgp:08919] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbde824527e]
[pkrvm7jw40e0xgp:08919] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbde82288ff]
[pkrvm7jw40e0xgp:08919] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbde86a5ff5]
[pkrvm7jw40e0xgp:08919] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbde86bb0da]
[pkrvm7jw40e0xgp:08919] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbde86a5a55]
[pkrvm7jw40e0xgp:08919] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbde86a5a6f]
[pkrvm7jw40e0xgp:08919] [ 8] plumed(+0x146dd)[0x564323fdd6dd]
[pkrvm7jw40e0xgp:08919] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbde822a1ca]
[pkrvm7jw40e0xgp:08919] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbde822a28b]
[pkrvm7jw40e0xgp:08919] [11] plumed(+0x15365)[0x564323fde365]
[pkrvm7jw40e0xgp:08919] *** End of error message ***
</pre>
{% endraw %}
