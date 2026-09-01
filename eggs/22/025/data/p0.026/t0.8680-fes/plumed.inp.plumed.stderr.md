**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.vU4cE5/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.1.so ../../code/ReweightGeomFES.cpp

[runnervmgx7h7:07652] *** Process received signal ***
[runnervmgx7h7:07652] Signal: Aborted (6)
[runnervmgx7h7:07652] Signal code:  (-6)
[runnervmgx7h7:07652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7625045330]
[runnervmgx7h7:07652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f762509ec0c]
[runnervmgx7h7:07652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f762504527e]
[runnervmgx7h7:07652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76250288ff]
[runnervmgx7h7:07652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76254a5ff5]
[runnervmgx7h7:07652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76254bb0da]
[runnervmgx7h7:07652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76254a5a55]
[runnervmgx7h7:07652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76254a5a6f]
[runnervmgx7h7:07652] [ 8] plumed(+0x146dd)[0x558b5aa5c6dd]
[runnervmgx7h7:07652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f762502a1ca]
[runnervmgx7h7:07652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f762502a28b]
[runnervmgx7h7:07652] [11] plumed(+0x15365)[0x558b5aa5d365]
[runnervmgx7h7:07652] *** End of error message ***
</pre>
{% endraw %}
