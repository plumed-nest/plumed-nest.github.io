**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.vGxtU1/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az787-589:67196] *** Process received signal ***
[fv-az787-589:67196] Signal: Aborted (6)
[fv-az787-589:67196] Signal code:  (-6)
[fv-az787-589:67196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f36de845330]
[fv-az787-589:67196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f36de89eb2c]
[fv-az787-589:67196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f36de84527e]
[fv-az787-589:67196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36de8288ff]
[fv-az787-589:67196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36deca5ff5]
[fv-az787-589:67196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36decbb0da]
[fv-az787-589:67196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36deca5a55]
[fv-az787-589:67196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36deca5a6f]
[fv-az787-589:67196] [ 8] plumed_master(+0x146dd)[0x555a3b9ac6dd]
[fv-az787-589:67196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f36de82a1ca]
[fv-az787-589:67196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f36de82a28b]
[fv-az787-589:67196] [11] plumed_master(+0x15365)[0x555a3b9ad365]
[fv-az787-589:67196] *** End of error message ***
</pre>
{% endraw %}
