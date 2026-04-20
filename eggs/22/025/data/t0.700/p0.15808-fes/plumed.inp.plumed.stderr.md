**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15808-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.qt2mLJ/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmeorf1:06841] *** Process received signal ***
[runnervmeorf1:06841] Signal: Aborted (6)
[runnervmeorf1:06841] Signal code:  (-6)
[runnervmeorf1:06841] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f882e645330]
[runnervmeorf1:06841] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f882e69eb2c]
[runnervmeorf1:06841] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f882e64527e]
[runnervmeorf1:06841] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f882e6288ff]
[runnervmeorf1:06841] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f882eaa5ff5]
[runnervmeorf1:06841] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f882eabb0da]
[runnervmeorf1:06841] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f882eaa5a55]
[runnervmeorf1:06841] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f882eaa5a6f]
[runnervmeorf1:06841] [ 8] plumed(+0x146dd)[0x562f7a15c6dd]
[runnervmeorf1:06841] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f882e62a1ca]
[runnervmeorf1:06841] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f882e62a28b]
[runnervmeorf1:06841] [11] plumed(+0x15365)[0x562f7a15d365]
[runnervmeorf1:06841] *** End of error message ***
</pre>
{% endraw %}
