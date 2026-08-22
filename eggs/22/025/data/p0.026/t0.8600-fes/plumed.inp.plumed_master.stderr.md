**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.0kG6rt/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervm76f27:08655] *** Process received signal ***
[runnervm76f27:08655] Signal: Aborted (6)
[runnervm76f27:08655] Signal code:  (-6)
[runnervm76f27:08655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc881445330]
[runnervm76f27:08655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc88149ec0c]
[runnervm76f27:08655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc88144527e]
[runnervm76f27:08655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8814288ff]
[runnervm76f27:08655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8818a5ff5]
[runnervm76f27:08655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8818bb0da]
[runnervm76f27:08655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8818a5a55]
[runnervm76f27:08655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8818a5a6f]
[runnervm76f27:08655] [ 8] plumed_master(+0x146dd)[0x563686bda6dd]
[runnervm76f27:08655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc88142a1ca]
[runnervm76f27:08655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc88142a28b]
[runnervm76f27:08655] [11] plumed_master(+0x15365)[0x563686bdb365]
[runnervm76f27:08655] *** End of error message ***
</pre>
{% endraw %}
