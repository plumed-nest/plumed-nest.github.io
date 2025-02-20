**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.CsRCp1/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1372-996:09048] *** Process received signal ***
[fv-az1372-996:09048] Signal: Aborted (6)
[fv-az1372-996:09048] Signal code:  (-6)
[fv-az1372-996:09048] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d15645330]
[fv-az1372-996:09048] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d1569eb2c]
[fv-az1372-996:09048] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d1564527e]
[fv-az1372-996:09048] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d156288ff]
[fv-az1372-996:09048] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d15aa5ff5]
[fv-az1372-996:09048] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d15abb0da]
[fv-az1372-996:09048] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d15aa5a55]
[fv-az1372-996:09048] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d15aa5a6f]
[fv-az1372-996:09048] [ 8] plumed_master(+0x146dd)[0x5636982e16dd]
[fv-az1372-996:09048] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d1562a1ca]
[fv-az1372-996:09048] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d1562a28b]
[fv-az1372-996:09048] [11] plumed_master(+0x15365)[0x5636982e2365]
[fv-az1372-996:09048] *** End of error message ***
</pre>
{% endraw %}
