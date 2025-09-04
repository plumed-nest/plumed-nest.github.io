**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Ve41P6/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:08567] *** Process received signal ***
[pkrvm7jw40e0xgp:08567] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08567] Signal code:  (-6)
[pkrvm7jw40e0xgp:08567] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd2d6245330]
[pkrvm7jw40e0xgp:08567] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd2d629eb2c]
[pkrvm7jw40e0xgp:08567] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd2d624527e]
[pkrvm7jw40e0xgp:08567] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2d62288ff]
[pkrvm7jw40e0xgp:08567] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2d66a5ff5]
[pkrvm7jw40e0xgp:08567] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2d66bb0da]
[pkrvm7jw40e0xgp:08567] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2d66a5a55]
[pkrvm7jw40e0xgp:08567] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2d66a5a6f]
[pkrvm7jw40e0xgp:08567] [ 8] plumed(+0x146dd)[0x55ad31ee46dd]
[pkrvm7jw40e0xgp:08567] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd2d622a1ca]
[pkrvm7jw40e0xgp:08567] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd2d622a28b]
[pkrvm7jw40e0xgp:08567] [11] plumed(+0x15365)[0x55ad31ee5365]
[pkrvm7jw40e0xgp:08567] *** End of error message ***
</pre>
{% endraw %}
