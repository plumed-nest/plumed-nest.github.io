**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.zrNYRF/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:10876] *** Process received signal ***
[pkrvm7jw40e0xgp:10876] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10876] Signal code:  (-6)
[pkrvm7jw40e0xgp:10876] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd478045330]
[pkrvm7jw40e0xgp:10876] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd47809eb2c]
[pkrvm7jw40e0xgp:10876] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd47804527e]
[pkrvm7jw40e0xgp:10876] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4780288ff]
[pkrvm7jw40e0xgp:10876] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4784a5ff5]
[pkrvm7jw40e0xgp:10876] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4784bb0da]
[pkrvm7jw40e0xgp:10876] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4784a5a55]
[pkrvm7jw40e0xgp:10876] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4784a5a6f]
[pkrvm7jw40e0xgp:10876] [ 8] plumed(+0x146dd)[0x5577b72906dd]
[pkrvm7jw40e0xgp:10876] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd47802a1ca]
[pkrvm7jw40e0xgp:10876] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd47802a28b]
[pkrvm7jw40e0xgp:10876] [11] plumed(+0x15365)[0x5577b7291365]
[pkrvm7jw40e0xgp:10876] *** End of error message ***
</pre>
{% endraw %}
