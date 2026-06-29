**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.oks6tf/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[runnervmmklqx:09534] *** Process received signal ***
[runnervmmklqx:09534] Signal: Aborted (6)
[runnervmmklqx:09534] Signal code:  (-6)
[runnervmmklqx:09534] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa7ea845330]
[runnervmmklqx:09534] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa7ea89eb2c]
[runnervmmklqx:09534] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa7ea84527e]
[runnervmmklqx:09534] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7ea8288ff]
[runnervmmklqx:09534] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7eaca5ff5]
[runnervmmklqx:09534] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7eacbb0da]
[runnervmmklqx:09534] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7eaca5a55]
[runnervmmklqx:09534] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7eaca5a6f]
[runnervmmklqx:09534] [ 8] plumed_master(+0x146dd)[0x56189c2e46dd]
[runnervmmklqx:09534] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa7ea82a1ca]
[runnervmmklqx:09534] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa7ea82a28b]
[runnervmmklqx:09534] [11] plumed_master(+0x15365)[0x56189c2e5365]
[runnervmmklqx:09534] *** End of error message ***
</pre>
{% endraw %}
