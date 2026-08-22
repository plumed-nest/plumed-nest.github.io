**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16222-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.SsQgWU/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.1.so ../../code/ReweightGeomFES.cpp

[runnervm76f27:09476] *** Process received signal ***
[runnervm76f27:09476] Signal: Aborted (6)
[runnervm76f27:09476] Signal code:  (-6)
[runnervm76f27:09476] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f28045330]
[runnervm76f27:09476] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f2809ec0c]
[runnervm76f27:09476] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f2804527e]
[runnervm76f27:09476] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f280288ff]
[runnervm76f27:09476] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f284a5ff5]
[runnervm76f27:09476] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f284bb0da]
[runnervm76f27:09476] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f284a5a55]
[runnervm76f27:09476] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f284a5a6f]
[runnervm76f27:09476] [ 8] plumed(+0x146dd)[0x55f3e690b6dd]
[runnervm76f27:09476] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f2802a1ca]
[runnervm76f27:09476] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f2802a28b]
[runnervm76f27:09476] [11] plumed(+0x15365)[0x55f3e690c365]
[runnervm76f27:09476] *** End of error message ***
</pre>
{% endraw %}
