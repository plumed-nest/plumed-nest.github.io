**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Q91EPU/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:10614] *** Process received signal ***
[pkrvm7jw40e0xgp:10614] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10614] Signal code:  (-6)
[pkrvm7jw40e0xgp:10614] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6702845330]
[pkrvm7jw40e0xgp:10614] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f670289eb2c]
[pkrvm7jw40e0xgp:10614] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f670284527e]
[pkrvm7jw40e0xgp:10614] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67028288ff]
[pkrvm7jw40e0xgp:10614] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6702ca5ff5]
[pkrvm7jw40e0xgp:10614] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6702cbb0da]
[pkrvm7jw40e0xgp:10614] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6702ca5a55]
[pkrvm7jw40e0xgp:10614] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6702ca5a6f]
[pkrvm7jw40e0xgp:10614] [ 8] plumed(+0x146dd)[0x55b1577e26dd]
[pkrvm7jw40e0xgp:10614] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f670282a1ca]
[pkrvm7jw40e0xgp:10614] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f670282a28b]
[pkrvm7jw40e0xgp:10614] [11] plumed(+0x15365)[0x55b1577e3365]
[pkrvm7jw40e0xgp:10614] *** End of error message ***
</pre>
{% endraw %}
