**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15808-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.3o2jeM/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:09562] *** Process received signal ***
[runnervmmklqx:09562] Signal: Aborted (6)
[runnervmmklqx:09562] Signal code:  (-6)
[runnervmmklqx:09562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd9c8445330]
[runnervmmklqx:09562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd9c849eb2c]
[runnervmmklqx:09562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd9c844527e]
[runnervmmklqx:09562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9c84288ff]
[runnervmmklqx:09562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9c88a5ff5]
[runnervmmklqx:09562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9c88bb0da]
[runnervmmklqx:09562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9c88a5a55]
[runnervmmklqx:09562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9c88a5a6f]
[runnervmmklqx:09562] [ 8] plumed(+0x146dd)[0x55f782d1d6dd]
[runnervmmklqx:09562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd9c842a1ca]
[runnervmmklqx:09562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd9c842a28b]
[runnervmmklqx:09562] [11] plumed(+0x15365)[0x55f782d1e365]
[runnervmmklqx:09562] *** End of error message ***
</pre>
{% endraw %}
