**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15808-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.usn1bP/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1719-82:63167] *** Process received signal ***
[fv-az1719-82:63167] Signal: Aborted (6)
[fv-az1719-82:63167] Signal code:  (-6)
[fv-az1719-82:63167] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c42245330]
[fv-az1719-82:63167] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c4229eb2c]
[fv-az1719-82:63167] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c4224527e]
[fv-az1719-82:63167] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c422288ff]
[fv-az1719-82:63167] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c426a5ff5]
[fv-az1719-82:63167] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c426bb0da]
[fv-az1719-82:63167] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c426a5a55]
[fv-az1719-82:63167] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c426a5a6f]
[fv-az1719-82:63167] [ 8] plumed_master(+0x146dd)[0x5646eb40c6dd]
[fv-az1719-82:63167] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c4222a1ca]
[fv-az1719-82:63167] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c4222a28b]
[fv-az1719-82:63167] [11] plumed_master(+0x15365)[0x5646eb40d365]
[fv-az1719-82:63167] *** End of error message ***
</pre>
{% endraw %}
