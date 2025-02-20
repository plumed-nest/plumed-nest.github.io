**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16222-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.zxq22C/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az1372-996:09941] *** Process received signal ***
[fv-az1372-996:09941] Signal: Aborted (6)
[fv-az1372-996:09941] Signal code:  (-6)
[fv-az1372-996:09941] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f57cdc45330]
[fv-az1372-996:09941] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f57cdc9eb2c]
[fv-az1372-996:09941] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f57cdc4527e]
[fv-az1372-996:09941] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f57cdc288ff]
[fv-az1372-996:09941] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f57ce0a5ff5]
[fv-az1372-996:09941] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f57ce0bb0da]
[fv-az1372-996:09941] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f57ce0a5a55]
[fv-az1372-996:09941] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f57ce0a5a6f]
[fv-az1372-996:09941] [ 8] plumed(+0x146dd)[0x55b9d6b476dd]
[fv-az1372-996:09941] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f57cdc2a1ca]
[fv-az1372-996:09941] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f57cdc2a28b]
[fv-az1372-996:09941] [11] plumed(+0x15365)[0x55b9d6b48365]
[fv-az1372-996:09941] *** End of error message ***
</pre>
{% endraw %}
