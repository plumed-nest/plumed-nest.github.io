**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lcZfLC/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az1680-626:11696] *** Process received signal ***
[fv-az1680-626:11696] Signal: Aborted (6)
[fv-az1680-626:11696] Signal code:  (-6)
[fv-az1680-626:11696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f28ef245330]
[fv-az1680-626:11696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f28ef29eb2c]
[fv-az1680-626:11696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f28ef24527e]
[fv-az1680-626:11696] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f28ef2288ff]
[fv-az1680-626:11696] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f28ef6a5ff5]
[fv-az1680-626:11696] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f28ef6bb0da]
[fv-az1680-626:11696] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f28ef6a5a55]
[fv-az1680-626:11696] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f28ef6a5a6f]
[fv-az1680-626:11696] [ 8] plumed_master(+0x146dd)[0x556a62af66dd]
[fv-az1680-626:11696] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f28ef22a1ca]
[fv-az1680-626:11696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f28ef22a28b]
[fv-az1680-626:11696] [11] plumed_master(+0x15365)[0x556a62af7365]
[fv-az1680-626:11696] *** End of error message ***
</pre>
{% endraw %}
