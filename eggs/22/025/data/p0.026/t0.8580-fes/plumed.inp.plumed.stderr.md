**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8580-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Q1BBv1/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:08731] *** Process received signal ***
[pkrvm7jw40e0xgp:08731] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08731] Signal code:  (-6)
[pkrvm7jw40e0xgp:08731] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe884e45330]
[pkrvm7jw40e0xgp:08731] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe884e9eb2c]
[pkrvm7jw40e0xgp:08731] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe884e4527e]
[pkrvm7jw40e0xgp:08731] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe884e288ff]
[pkrvm7jw40e0xgp:08731] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8852a5ff5]
[pkrvm7jw40e0xgp:08731] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8852bb0da]
[pkrvm7jw40e0xgp:08731] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8852a5a55]
[pkrvm7jw40e0xgp:08731] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8852a5a6f]
[pkrvm7jw40e0xgp:08731] [ 8] plumed(+0x146dd)[0x55cb773166dd]
[pkrvm7jw40e0xgp:08731] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe884e2a1ca]
[pkrvm7jw40e0xgp:08731] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe884e2a28b]
[pkrvm7jw40e0xgp:08731] [11] plumed(+0x15365)[0x55cb77317365]
[pkrvm7jw40e0xgp:08731] *** End of error message ***
</pre>
{% endraw %}
