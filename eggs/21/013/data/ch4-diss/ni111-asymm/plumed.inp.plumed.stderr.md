**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.AxxOxS/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:10437] *** Process received signal ***
[pkrvm7jw40e0xgp:10437] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10437] Signal code:  (-6)
[pkrvm7jw40e0xgp:10437] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f862b245330]
[pkrvm7jw40e0xgp:10437] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f862b29eb2c]
[pkrvm7jw40e0xgp:10437] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f862b24527e]
[pkrvm7jw40e0xgp:10437] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f862b2288ff]
[pkrvm7jw40e0xgp:10437] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f862b6a5ff5]
[pkrvm7jw40e0xgp:10437] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f862b6bb0da]
[pkrvm7jw40e0xgp:10437] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f862b6a5a55]
[pkrvm7jw40e0xgp:10437] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f862b6a5a6f]
[pkrvm7jw40e0xgp:10437] [ 8] plumed(+0x146dd)[0x55969f1676dd]
[pkrvm7jw40e0xgp:10437] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f862b22a1ca]
[pkrvm7jw40e0xgp:10437] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f862b22a28b]
[pkrvm7jw40e0xgp:10437] [11] plumed(+0x15365)[0x55969f168365]
[pkrvm7jw40e0xgp:10437] *** End of error message ***
</pre>
{% endraw %}
