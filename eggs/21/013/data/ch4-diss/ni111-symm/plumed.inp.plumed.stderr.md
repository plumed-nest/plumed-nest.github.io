**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.rJLT6k/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmmklqx:08918] *** Process received signal ***
[runnervmmklqx:08918] Signal: Aborted (6)
[runnervmmklqx:08918] Signal code:  (-6)
[runnervmmklqx:08918] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f113c645330]
[runnervmmklqx:08918] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f113c69eb2c]
[runnervmmklqx:08918] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f113c64527e]
[runnervmmklqx:08918] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f113c6288ff]
[runnervmmklqx:08918] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f113caa5ff5]
[runnervmmklqx:08918] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f113cabb0da]
[runnervmmklqx:08918] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f113caa5a55]
[runnervmmklqx:08918] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f113caa5a6f]
[runnervmmklqx:08918] [ 8] plumed(+0x146dd)[0x55800bbab6dd]
[runnervmmklqx:08918] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f113c62a1ca]
[runnervmmklqx:08918] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f113c62a28b]
[runnervmmklqx:08918] [11] plumed(+0x15365)[0x55800bbac365]
[runnervmmklqx:08918] *** End of error message ***
</pre>
{% endraw %}
