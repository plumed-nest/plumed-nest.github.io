**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.2wjZ86/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.1.so ../codes/ReweightGeomFES.cpp

[runnervmgx7h7:08878] *** Process received signal ***
[runnervmgx7h7:08878] Signal: Aborted (6)
[runnervmgx7h7:08878] Signal code:  (-6)
[runnervmgx7h7:08878] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f356f245330]
[runnervmgx7h7:08878] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f356f29ec0c]
[runnervmgx7h7:08878] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f356f24527e]
[runnervmgx7h7:08878] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f356f2288ff]
[runnervmgx7h7:08878] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f356f6a5ff5]
[runnervmgx7h7:08878] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f356f6bb0da]
[runnervmgx7h7:08878] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f356f6a5a55]
[runnervmgx7h7:08878] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f356f6a5a6f]
[runnervmgx7h7:08878] [ 8] plumed(+0x146dd)[0x5637e22d76dd]
[runnervmgx7h7:08878] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f356f22a1ca]
[runnervmgx7h7:08878] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f356f22a28b]
[runnervmgx7h7:08878] [11] plumed(+0x15365)[0x5637e22d8365]
[runnervmgx7h7:08878] *** End of error message ***
</pre>
{% endraw %}
