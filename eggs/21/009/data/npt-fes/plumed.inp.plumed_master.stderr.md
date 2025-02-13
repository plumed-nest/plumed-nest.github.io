**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.vkdz7F/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[fv-az1665-105:13114] *** Process received signal ***
[fv-az1665-105:13114] Signal: Aborted (6)
[fv-az1665-105:13114] Signal code:  (-6)
[fv-az1665-105:13114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0667c45330]
[fv-az1665-105:13114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0667c9eb2c]
[fv-az1665-105:13114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0667c4527e]
[fv-az1665-105:13114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0667c288ff]
[fv-az1665-105:13114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06680a5ff5]
[fv-az1665-105:13114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06680bb0da]
[fv-az1665-105:13114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06680a5a55]
[fv-az1665-105:13114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06680a5a6f]
[fv-az1665-105:13114] [ 8] plumed_master(+0x146dd)[0x561e07ce26dd]
[fv-az1665-105:13114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0667c2a1ca]
[fv-az1665-105:13114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0667c2a28b]
[fv-az1665-105:13114] [11] plumed_master(+0x15365)[0x561e07ce3365]
[fv-az1665-105:13114] *** End of error message ***
</pre>
{% endraw %}
