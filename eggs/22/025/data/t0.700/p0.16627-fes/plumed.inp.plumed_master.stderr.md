**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16627-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.cV7eCe/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmvrwv9:08116] *** Process received signal ***
[runnervmvrwv9:08116] Signal: Aborted (6)
[runnervmvrwv9:08116] Signal code:  (-6)
[runnervmvrwv9:08116] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2d64245330]
[runnervmvrwv9:08116] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2d6429eb2c]
[runnervmvrwv9:08116] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2d6424527e]
[runnervmvrwv9:08116] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2d642288ff]
[runnervmvrwv9:08116] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2d646a5ff5]
[runnervmvrwv9:08116] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2d646bb0da]
[runnervmvrwv9:08116] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2d646a5a55]
[runnervmvrwv9:08116] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2d646a5a6f]
[runnervmvrwv9:08116] [ 8] plumed_master(+0x146dd)[0x559645f2d6dd]
[runnervmvrwv9:08116] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2d6422a1ca]
[runnervmvrwv9:08116] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2d6422a28b]
[runnervmvrwv9:08116] [11] plumed_master(+0x15365)[0x559645f2e365]
[runnervmvrwv9:08116] *** End of error message ***
</pre>
{% endraw %}
