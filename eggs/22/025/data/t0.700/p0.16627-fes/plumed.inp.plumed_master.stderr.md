**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16627-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.aF9BKU/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1344-582:64493] *** Process received signal ***
[fv-az1344-582:64493] Signal: Aborted (6)
[fv-az1344-582:64493] Signal code:  (-6)
[fv-az1344-582:64493] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f110a845330]
[fv-az1344-582:64493] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f110a89eb2c]
[fv-az1344-582:64493] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f110a84527e]
[fv-az1344-582:64493] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f110a8288ff]
[fv-az1344-582:64493] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f110aca5ff5]
[fv-az1344-582:64493] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f110acbb0da]
[fv-az1344-582:64493] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f110aca5a55]
[fv-az1344-582:64493] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f110aca5a6f]
[fv-az1344-582:64493] [ 8] plumed_master(+0x146dd)[0x56001be8c6dd]
[fv-az1344-582:64493] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f110a82a1ca]
[fv-az1344-582:64493] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f110a82a28b]
[fv-az1344-582:64493] [11] plumed_master(+0x15365)[0x56001be8d365]
[fv-az1344-582:64493] *** End of error message ***
</pre>
{% endraw %}
