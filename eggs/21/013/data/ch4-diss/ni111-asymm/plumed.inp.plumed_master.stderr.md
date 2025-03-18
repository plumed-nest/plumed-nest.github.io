**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lqfzbt/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az790-36:65570] *** Process received signal ***
[fv-az790-36:65570] Signal: Aborted (6)
[fv-az790-36:65570] Signal code:  (-6)
[fv-az790-36:65570] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb3e4e45330]
[fv-az790-36:65570] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb3e4e9eb2c]
[fv-az790-36:65570] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb3e4e4527e]
[fv-az790-36:65570] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb3e4e288ff]
[fv-az790-36:65570] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3e52a5ff5]
[fv-az790-36:65570] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3e52bb0da]
[fv-az790-36:65570] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3e52a5a55]
[fv-az790-36:65570] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3e52a5a6f]
[fv-az790-36:65570] [ 8] plumed_master(+0x146dd)[0x562f7013f6dd]
[fv-az790-36:65570] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb3e4e2a1ca]
[fv-az790-36:65570] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb3e4e2a28b]
[fv-az790-36:65570] [11] plumed_master(+0x15365)[0x562f70140365]
[fv-az790-36:65570] *** End of error message ***
</pre>
{% endraw %}
