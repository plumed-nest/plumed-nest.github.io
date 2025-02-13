**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.sKy18O/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az1665-105:14247] *** Process received signal ***
[fv-az1665-105:14247] Signal: Aborted (6)
[fv-az1665-105:14247] Signal code:  (-6)
[fv-az1665-105:14247] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ac0245330]
[fv-az1665-105:14247] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ac029eb2c]
[fv-az1665-105:14247] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ac024527e]
[fv-az1665-105:14247] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ac02288ff]
[fv-az1665-105:14247] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ac06a5ff5]
[fv-az1665-105:14247] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ac06bb0da]
[fv-az1665-105:14247] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ac06a5a55]
[fv-az1665-105:14247] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ac06a5a6f]
[fv-az1665-105:14247] [ 8] plumed_master(+0x146dd)[0x5588c0ae86dd]
[fv-az1665-105:14247] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ac022a1ca]
[fv-az1665-105:14247] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ac022a28b]
[fv-az1665-105:14247] [11] plumed_master(+0x15365)[0x5588c0ae9365]
[fv-az1665-105:14247] *** End of error message ***
</pre>
{% endraw %}
