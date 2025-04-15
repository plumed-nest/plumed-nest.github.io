**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.wF3vPQ/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[fv-az1910-428:66450] *** Process received signal ***
[fv-az1910-428:66450] Signal: Aborted (6)
[fv-az1910-428:66450] Signal code:  (-6)
[fv-az1910-428:66450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1837245330]
[fv-az1910-428:66450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f183729eb2c]
[fv-az1910-428:66450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f183724527e]
[fv-az1910-428:66450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18372288ff]
[fv-az1910-428:66450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18376a5ff5]
[fv-az1910-428:66450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18376bb0da]
[fv-az1910-428:66450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18376a5a55]
[fv-az1910-428:66450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18376a5a6f]
[fv-az1910-428:66450] [ 8] plumed_master(+0x146dd)[0x561efad036dd]
[fv-az1910-428:66450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f183722a1ca]
[fv-az1910-428:66450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f183722a28b]
[fv-az1910-428:66450] [11] plumed_master(+0x15365)[0x561efad04365]
[fv-az1910-428:66450] *** End of error message ***
</pre>
{% endraw %}
