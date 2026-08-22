**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.LWJpD2/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.1.so ../../code/ReweightGeomFES.cpp

[runnervm76f27:08797] *** Process received signal ***
[runnervm76f27:08797] Signal: Aborted (6)
[runnervm76f27:08797] Signal code:  (-6)
[runnervm76f27:08797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f847f445330]
[runnervm76f27:08797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f847f49ec0c]
[runnervm76f27:08797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f847f44527e]
[runnervm76f27:08797] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f847f4288ff]
[runnervm76f27:08797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f847f8a5ff5]
[runnervm76f27:08797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f847f8bb0da]
[runnervm76f27:08797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f847f8a5a55]
[runnervm76f27:08797] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f847f8a5a6f]
[runnervm76f27:08797] [ 8] plumed(+0x146dd)[0x555597f526dd]
[runnervm76f27:08797] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f847f42a1ca]
[runnervm76f27:08797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f847f42a28b]
[runnervm76f27:08797] [11] plumed(+0x15365)[0x555597f53365]
[runnervm76f27:08797] *** End of error message ***
</pre>
{% endraw %}
