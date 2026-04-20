**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8580-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.GKslyg/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmeorf1:06295] *** Process received signal ***
[runnervmeorf1:06295] Signal: Aborted (6)
[runnervmeorf1:06295] Signal code:  (-6)
[runnervmeorf1:06295] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fae7c245330]
[runnervmeorf1:06295] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fae7c29eb2c]
[runnervmeorf1:06295] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fae7c24527e]
[runnervmeorf1:06295] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fae7c2288ff]
[runnervmeorf1:06295] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fae7c6a5ff5]
[runnervmeorf1:06295] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fae7c6bb0da]
[runnervmeorf1:06295] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fae7c6a5a55]
[runnervmeorf1:06295] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fae7c6a5a6f]
[runnervmeorf1:06295] [ 8] plumed(+0x146dd)[0x55e264bf76dd]
[runnervmeorf1:06295] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fae7c22a1ca]
[runnervmeorf1:06295] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fae7c22a28b]
[runnervmeorf1:06295] [11] plumed(+0x15365)[0x55e264bf8365]
[runnervmeorf1:06295] *** End of error message ***
</pre>
{% endraw %}
