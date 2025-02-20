**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8580-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.xwyzzw/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1372-996:09606] *** Process received signal ***
[fv-az1372-996:09606] Signal: Aborted (6)
[fv-az1372-996:09606] Signal code:  (-6)
[fv-az1372-996:09606] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c32445330]
[fv-az1372-996:09606] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c3249eb2c]
[fv-az1372-996:09606] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c3244527e]
[fv-az1372-996:09606] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c324288ff]
[fv-az1372-996:09606] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c328a5ff5]
[fv-az1372-996:09606] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c328bb0da]
[fv-az1372-996:09606] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c328a5a55]
[fv-az1372-996:09606] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c328a5a6f]
[fv-az1372-996:09606] [ 8] plumed_master(+0x146dd)[0x56236e9eb6dd]
[fv-az1372-996:09606] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c3242a1ca]
[fv-az1372-996:09606] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c3242a28b]
[fv-az1372-996:09606] [11] plumed_master(+0x15365)[0x56236e9ec365]
[fv-az1372-996:09606] *** End of error message ***
</pre>
{% endraw %}
