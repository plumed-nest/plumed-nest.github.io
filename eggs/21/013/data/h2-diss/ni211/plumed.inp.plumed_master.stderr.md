**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.3cGU2u/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1280-696:10712] *** Process received signal ***
[fv-az1280-696:10712] Signal: Aborted (6)
[fv-az1280-696:10712] Signal code:  (-6)
[fv-az1280-696:10712] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4a7e45330]
[fv-az1280-696:10712] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4a7e9eb2c]
[fv-az1280-696:10712] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4a7e4527e]
[fv-az1280-696:10712] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4a7e288ff]
[fv-az1280-696:10712] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4a82a5ff5]
[fv-az1280-696:10712] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4a82bb0da]
[fv-az1280-696:10712] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4a82a5a55]
[fv-az1280-696:10712] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4a82a5a6f]
[fv-az1280-696:10712] [ 8] plumed_master(+0x146dd)[0x55a8410456dd]
[fv-az1280-696:10712] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4a7e2a1ca]
[fv-az1280-696:10712] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4a7e2a28b]
[fv-az1280-696:10712] [11] plumed_master(+0x15365)[0x55a841046365]
[fv-az1280-696:10712] *** End of error message ***
</pre>
{% endraw %}
