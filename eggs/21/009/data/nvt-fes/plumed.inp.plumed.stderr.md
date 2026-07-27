**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.GbgbHf/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.1.so ../codes/ReweightGeomFES.cpp

[runnervmvrwv9:09767] *** Process received signal ***
[runnervmvrwv9:09767] Signal: Aborted (6)
[runnervmvrwv9:09767] Signal code:  (-6)
[runnervmvrwv9:09767] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f76b2445330]
[runnervmvrwv9:09767] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f76b249eb2c]
[runnervmvrwv9:09767] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f76b244527e]
[runnervmvrwv9:09767] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76b24288ff]
[runnervmvrwv9:09767] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76b28a5ff5]
[runnervmvrwv9:09767] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76b28bb0da]
[runnervmvrwv9:09767] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76b28a5a55]
[runnervmvrwv9:09767] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76b28a5a6f]
[runnervmvrwv9:09767] [ 8] plumed(+0x146dd)[0x55629ff5c6dd]
[runnervmvrwv9:09767] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f76b242a1ca]
[runnervmvrwv9:09767] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f76b242a28b]
[runnervmvrwv9:09767] [11] plumed(+0x15365)[0x55629ff5d365]
[runnervmvrwv9:09767] *** End of error message ***
</pre>
{% endraw %}
