**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.vTYMmS/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:10701] *** Process received signal ***
[pkrvm7jw40e0xgp:10701] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10701] Signal code:  (-6)
[pkrvm7jw40e0xgp:10701] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff819c45330]
[pkrvm7jw40e0xgp:10701] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff819c9eb2c]
[pkrvm7jw40e0xgp:10701] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff819c4527e]
[pkrvm7jw40e0xgp:10701] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff819c288ff]
[pkrvm7jw40e0xgp:10701] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff81a0a5ff5]
[pkrvm7jw40e0xgp:10701] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff81a0bb0da]
[pkrvm7jw40e0xgp:10701] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff81a0a5a55]
[pkrvm7jw40e0xgp:10701] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff81a0a5a6f]
[pkrvm7jw40e0xgp:10701] [ 8] plumed(+0x146dd)[0x564175b486dd]
[pkrvm7jw40e0xgp:10701] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff819c2a1ca]
[pkrvm7jw40e0xgp:10701] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff819c2a28b]
[pkrvm7jw40e0xgp:10701] [11] plumed(+0x15365)[0x564175b49365]
[pkrvm7jw40e0xgp:10701] *** End of error message ***
</pre>
{% endraw %}
