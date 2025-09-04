**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.h0uVAq/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.0.so ../src/bias/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:12101] *** Process received signal ***
[pkrvm7jw40e0xgp:12101] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12101] Signal code:  (-6)
[pkrvm7jw40e0xgp:12101] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4313245330]
[pkrvm7jw40e0xgp:12101] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f431329eb2c]
[pkrvm7jw40e0xgp:12101] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f431324527e]
[pkrvm7jw40e0xgp:12101] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43132288ff]
[pkrvm7jw40e0xgp:12101] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43136a5ff5]
[pkrvm7jw40e0xgp:12101] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43136bb0da]
[pkrvm7jw40e0xgp:12101] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43136a5a55]
[pkrvm7jw40e0xgp:12101] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43136a5a6f]
[pkrvm7jw40e0xgp:12101] [ 8] plumed(+0x146dd)[0x557705ccc6dd]
[pkrvm7jw40e0xgp:12101] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f431322a1ca]
[pkrvm7jw40e0xgp:12101] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f431322a28b]
[pkrvm7jw40e0xgp:12101] [11] plumed(+0x15365)[0x557705ccd365]
[pkrvm7jw40e0xgp:12101] *** End of error message ***
</pre>
{% endraw %}
