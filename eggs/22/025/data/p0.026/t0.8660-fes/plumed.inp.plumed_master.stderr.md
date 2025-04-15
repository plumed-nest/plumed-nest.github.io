**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.ZkyWZN/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1719-82:62219] *** Process received signal ***
[fv-az1719-82:62219] Signal: Aborted (6)
[fv-az1719-82:62219] Signal code:  (-6)
[fv-az1719-82:62219] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f847e845330]
[fv-az1719-82:62219] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f847e89eb2c]
[fv-az1719-82:62219] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f847e84527e]
[fv-az1719-82:62219] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f847e8288ff]
[fv-az1719-82:62219] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f847eca5ff5]
[fv-az1719-82:62219] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f847ecbb0da]
[fv-az1719-82:62219] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f847eca5a55]
[fv-az1719-82:62219] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f847eca5a6f]
[fv-az1719-82:62219] [ 8] plumed_master(+0x146dd)[0x5597575b86dd]
[fv-az1719-82:62219] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f847e82a1ca]
[fv-az1719-82:62219] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f847e82a28b]
[fv-az1719-82:62219] [11] plumed_master(+0x15365)[0x5597575b9365]
[fv-az1719-82:62219] *** End of error message ***
</pre>
{% endraw %}
