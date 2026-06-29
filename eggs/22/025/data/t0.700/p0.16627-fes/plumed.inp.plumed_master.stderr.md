**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16627-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.w1mBsz/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:09334] *** Process received signal ***
[runnervmmklqx:09334] Signal: Aborted (6)
[runnervmmklqx:09334] Signal code:  (-6)
[runnervmmklqx:09334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8281245330]
[runnervmmklqx:09334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f828129eb2c]
[runnervmmklqx:09334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f828124527e]
[runnervmmklqx:09334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82812288ff]
[runnervmmklqx:09334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82816a5ff5]
[runnervmmklqx:09334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82816bb0da]
[runnervmmklqx:09334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82816a5a55]
[runnervmmklqx:09334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82816a5a6f]
[runnervmmklqx:09334] [ 8] plumed_master(+0x146dd)[0x56276c9e06dd]
[runnervmmklqx:09334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f828122a1ca]
[runnervmmklqx:09334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f828122a28b]
[runnervmmklqx:09334] [11] plumed_master(+0x15365)[0x56276c9e1365]
[runnervmmklqx:09334] *** End of error message ***
</pre>
{% endraw %}
