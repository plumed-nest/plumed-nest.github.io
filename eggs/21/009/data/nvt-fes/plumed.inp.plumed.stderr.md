**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lQSJJy/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.0.so ../codes/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:10141] *** Process received signal ***
[pkrvm7jw40e0xgp:10141] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10141] Signal code:  (-6)
[pkrvm7jw40e0xgp:10141] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d15045330]
[pkrvm7jw40e0xgp:10141] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d1509eb2c]
[pkrvm7jw40e0xgp:10141] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d1504527e]
[pkrvm7jw40e0xgp:10141] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d150288ff]
[pkrvm7jw40e0xgp:10141] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d154a5ff5]
[pkrvm7jw40e0xgp:10141] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d154bb0da]
[pkrvm7jw40e0xgp:10141] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d154a5a55]
[pkrvm7jw40e0xgp:10141] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d154a5a6f]
[pkrvm7jw40e0xgp:10141] [ 8] plumed(+0x146dd)[0x56151f33a6dd]
[pkrvm7jw40e0xgp:10141] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d1502a1ca]
[pkrvm7jw40e0xgp:10141] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d1502a28b]
[pkrvm7jw40e0xgp:10141] [11] plumed(+0x15365)[0x56151f33b365]
[pkrvm7jw40e0xgp:10141] *** End of error message ***
</pre>
{% endraw %}
