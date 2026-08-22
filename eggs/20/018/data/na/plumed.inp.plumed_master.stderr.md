**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Xi6eBY/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[runnervm76f27:09953] *** Process received signal ***
[runnervm76f27:09953] Signal: Aborted (6)
[runnervm76f27:09953] Signal code:  (-6)
[runnervm76f27:09953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f86c9e45330]
[runnervm76f27:09953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f86c9e9ec0c]
[runnervm76f27:09953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f86c9e4527e]
[runnervm76f27:09953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f86c9e288ff]
[runnervm76f27:09953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f86ca2a5ff5]
[runnervm76f27:09953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f86ca2bb0da]
[runnervm76f27:09953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f86ca2a5a55]
[runnervm76f27:09953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f86ca2a5a6f]
[runnervm76f27:09953] [ 8] plumed_master(+0x146dd)[0x564377f0d6dd]
[runnervm76f27:09953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f86c9e2a1ca]
[runnervm76f27:09953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f86c9e2a28b]
[runnervm76f27:09953] [11] plumed_master(+0x15365)[0x564377f0e365]
[runnervm76f27:09953] *** End of error message ***
</pre>
{% endraw %}
