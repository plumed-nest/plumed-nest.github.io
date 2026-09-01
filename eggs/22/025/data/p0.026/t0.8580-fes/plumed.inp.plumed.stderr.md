**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8580-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.UiYskc/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.1.so ../../code/ReweightGeomFES.cpp

[runnervmgx7h7:07793] *** Process received signal ***
[runnervmgx7h7:07793] Signal: Aborted (6)
[runnervmgx7h7:07793] Signal code:  (-6)
[runnervmgx7h7:07793] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabc3645330]
[runnervmgx7h7:07793] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabc369ec0c]
[runnervmgx7h7:07793] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabc364527e]
[runnervmgx7h7:07793] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabc36288ff]
[runnervmgx7h7:07793] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabc3aa5ff5]
[runnervmgx7h7:07793] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabc3abb0da]
[runnervmgx7h7:07793] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabc3aa5a55]
[runnervmgx7h7:07793] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabc3aa5a6f]
[runnervmgx7h7:07793] [ 8] plumed(+0x146dd)[0x561ce14f16dd]
[runnervmgx7h7:07793] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabc362a1ca]
[runnervmgx7h7:07793] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabc362a28b]
[runnervmgx7h7:07793] [11] plumed(+0x15365)[0x561ce14f2365]
[runnervmgx7h7:07793] *** End of error message ***
</pre>
{% endraw %}
