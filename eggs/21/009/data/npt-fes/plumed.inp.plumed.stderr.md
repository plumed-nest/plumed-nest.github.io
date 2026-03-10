**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.dT1WsS/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.0.so ../codes/ReweightGeomFES.cpp

[runnervm0kj6c:10301] *** Process received signal ***
[runnervm0kj6c:10301] Signal: Aborted (6)
[runnervm0kj6c:10301] Signal code:  (-6)
[runnervm0kj6c:10301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff59f245330]
[runnervm0kj6c:10301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff59f29eb2c]
[runnervm0kj6c:10301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff59f24527e]
[runnervm0kj6c:10301] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff59f2288ff]
[runnervm0kj6c:10301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff59f6a5ff5]
[runnervm0kj6c:10301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff59f6bb0da]
[runnervm0kj6c:10301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff59f6a5a55]
[runnervm0kj6c:10301] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff59f6a5a6f]
[runnervm0kj6c:10301] [ 8] plumed(+0x146dd)[0x56059d8636dd]
[runnervm0kj6c:10301] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff59f22a1ca]
[runnervm0kj6c:10301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff59f22a28b]
[runnervm0kj6c:10301] [11] plumed(+0x15365)[0x56059d864365]
[runnervm0kj6c:10301] *** End of error message ***
</pre>
{% endraw %}
