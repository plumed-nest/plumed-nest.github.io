**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.JR7jVv/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az1665-105:14334] *** Process received signal ***
[fv-az1665-105:14334] Signal: Aborted (6)
[fv-az1665-105:14334] Signal code:  (-6)
[fv-az1665-105:14334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f156b845330]
[fv-az1665-105:14334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f156b89eb2c]
[fv-az1665-105:14334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f156b84527e]
[fv-az1665-105:14334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f156b8288ff]
[fv-az1665-105:14334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f156bca5ff5]
[fv-az1665-105:14334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f156bcbb0da]
[fv-az1665-105:14334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f156bca5a55]
[fv-az1665-105:14334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f156bca5a6f]
[fv-az1665-105:14334] [ 8] plumed_master(+0x146dd)[0x560bf21e76dd]
[fv-az1665-105:14334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f156b82a1ca]
[fv-az1665-105:14334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f156b82a28b]
[fv-az1665-105:14334] [11] plumed_master(+0x15365)[0x560bf21e8365]
[fv-az1665-105:14334] *** End of error message ***
</pre>
{% endraw %}
