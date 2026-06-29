**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.3FeMKc/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:08530] *** Process received signal ***
[runnervmmklqx:08530] Signal: Aborted (6)
[runnervmmklqx:08530] Signal code:  (-6)
[runnervmmklqx:08530] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f366de45330]
[runnervmmklqx:08530] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f366de9eb2c]
[runnervmmklqx:08530] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f366de4527e]
[runnervmmklqx:08530] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f366de288ff]
[runnervmmklqx:08530] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f366e2a5ff5]
[runnervmmklqx:08530] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f366e2bb0da]
[runnervmmklqx:08530] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f366e2a5a55]
[runnervmmklqx:08530] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f366e2a5a6f]
[runnervmmklqx:08530] [ 8] plumed(+0x146dd)[0x55ee7397f6dd]
[runnervmmklqx:08530] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f366de2a1ca]
[runnervmmklqx:08530] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f366de2a28b]
[runnervmmklqx:08530] [11] plumed(+0x15365)[0x55ee73980365]
[runnervmmklqx:08530] *** End of error message ***
</pre>
{% endraw %}
