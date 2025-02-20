**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.2XEJDz/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[fv-az802-475:11819] *** Process received signal ***
[fv-az802-475:11819] Signal: Aborted (6)
[fv-az802-475:11819] Signal code:  (-6)
[fv-az802-475:11819] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f46e6645330]
[fv-az802-475:11819] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f46e669eb2c]
[fv-az802-475:11819] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f46e664527e]
[fv-az802-475:11819] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46e66288ff]
[fv-az802-475:11819] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46e6aa5ff5]
[fv-az802-475:11819] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46e6abb0da]
[fv-az802-475:11819] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46e6aa5a55]
[fv-az802-475:11819] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46e6aa5a6f]
[fv-az802-475:11819] [ 8] plumed_master(+0x146dd)[0x55d0e8ba16dd]
[fv-az802-475:11819] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f46e662a1ca]
[fv-az802-475:11819] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f46e662a28b]
[fv-az802-475:11819] [11] plumed_master(+0x15365)[0x55d0e8ba2365]
[fv-az802-475:11819] *** End of error message ***
</pre>
{% endraw %}
