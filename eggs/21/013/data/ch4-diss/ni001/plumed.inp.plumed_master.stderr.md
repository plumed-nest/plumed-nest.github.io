**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.8sU4bt/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervm0kj6c:09553] *** Process received signal ***
[runnervm0kj6c:09553] Signal: Aborted (6)
[runnervm0kj6c:09553] Signal code:  (-6)
[runnervm0kj6c:09553] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa52245330]
[runnervm0kj6c:09553] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa5229eb2c]
[runnervm0kj6c:09553] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa5224527e]
[runnervm0kj6c:09553] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa522288ff]
[runnervm0kj6c:09553] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa526a5ff5]
[runnervm0kj6c:09553] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa526bb0da]
[runnervm0kj6c:09553] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa526a5a55]
[runnervm0kj6c:09553] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa526a5a6f]
[runnervm0kj6c:09553] [ 8] plumed_master(+0x146dd)[0x561625ab66dd]
[runnervm0kj6c:09553] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa5222a1ca]
[runnervm0kj6c:09553] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa5222a28b]
[runnervm0kj6c:09553] [11] plumed_master(+0x15365)[0x561625ab7365]
[runnervm0kj6c:09553] *** End of error message ***
</pre>
{% endraw %}
