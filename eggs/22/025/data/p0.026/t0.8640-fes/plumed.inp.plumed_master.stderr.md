**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8640-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.4KYOZk/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:08830] *** Process received signal ***
[runnervmmklqx:08830] Signal: Aborted (6)
[runnervmmklqx:08830] Signal code:  (-6)
[runnervmmklqx:08830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d94445330]
[runnervmmklqx:08830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d9449eb2c]
[runnervmmklqx:08830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d9444527e]
[runnervmmklqx:08830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d944288ff]
[runnervmmklqx:08830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d948a5ff5]
[runnervmmklqx:08830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d948bb0da]
[runnervmmklqx:08830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d948a5a55]
[runnervmmklqx:08830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d948a5a6f]
[runnervmmklqx:08830] [ 8] plumed_master(+0x146dd)[0x562b914e26dd]
[runnervmmklqx:08830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d9442a1ca]
[runnervmmklqx:08830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d9442a28b]
[runnervmmklqx:08830] [11] plumed_master(+0x15365)[0x562b914e3365]
[runnervmmklqx:08830] *** End of error message ***
</pre>
{% endraw %}
