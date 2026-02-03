**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.n7MhAf/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[runnervmkj6or:11382] *** Process received signal ***
[runnervmkj6or:11382] Signal: Aborted (6)
[runnervmkj6or:11382] Signal code:  (-6)
[runnervmkj6or:11382] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f96e1845330]
[runnervmkj6or:11382] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f96e189eb2c]
[runnervmkj6or:11382] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f96e184527e]
[runnervmkj6or:11382] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96e18288ff]
[runnervmkj6or:11382] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96e1ca5ff5]
[runnervmkj6or:11382] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96e1cbb0da]
[runnervmkj6or:11382] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96e1ca5a55]
[runnervmkj6or:11382] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96e1ca5a6f]
[runnervmkj6or:11382] [ 8] plumed_master(+0x146dd)[0x55aaacafb6dd]
[runnervmkj6or:11382] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f96e182a1ca]
[runnervmkj6or:11382] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f96e182a28b]
[runnervmkj6or:11382] [11] plumed_master(+0x15365)[0x55aaacafc365]
[runnervmkj6or:11382] *** End of error message ***
</pre>
{% endraw %}
