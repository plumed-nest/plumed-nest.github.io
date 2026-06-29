**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.l8Fai8/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.0.so ../codes/ReweightGeomFES.cpp

[runnervmmklqx:09500] *** Process received signal ***
[runnervmmklqx:09500] Signal: Aborted (6)
[runnervmmklqx:09500] Signal code:  (-6)
[runnervmmklqx:09500] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f960b845330]
[runnervmmklqx:09500] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f960b89eb2c]
[runnervmmklqx:09500] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f960b84527e]
[runnervmmklqx:09500] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f960b8288ff]
[runnervmmklqx:09500] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f960bca5ff5]
[runnervmmklqx:09500] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f960bcbb0da]
[runnervmmklqx:09500] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f960bca5a55]
[runnervmmklqx:09500] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f960bca5a6f]
[runnervmmklqx:09500] [ 8] plumed(+0x146dd)[0x56310890e6dd]
[runnervmmklqx:09500] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f960b82a1ca]
[runnervmmklqx:09500] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f960b82a28b]
[runnervmmklqx:09500] [11] plumed(+0x15365)[0x56310890f365]
[runnervmmklqx:09500] *** End of error message ***
</pre>
{% endraw %}
