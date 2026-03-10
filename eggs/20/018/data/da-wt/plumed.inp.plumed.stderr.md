**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.CTnIo6/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.0.so ../src/bias/ReweightGeomFES.cpp

[runnervm0kj6c:10058] *** Process received signal ***
[runnervm0kj6c:10058] Signal: Aborted (6)
[runnervm0kj6c:10058] Signal code:  (-6)
[runnervm0kj6c:10058] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68ac245330]
[runnervm0kj6c:10058] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68ac29eb2c]
[runnervm0kj6c:10058] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68ac24527e]
[runnervm0kj6c:10058] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68ac2288ff]
[runnervm0kj6c:10058] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68ac6a5ff5]
[runnervm0kj6c:10058] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68ac6bb0da]
[runnervm0kj6c:10058] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68ac6a5a55]
[runnervm0kj6c:10058] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68ac6a5a6f]
[runnervm0kj6c:10058] [ 8] plumed(+0x146dd)[0x5555668466dd]
[runnervm0kj6c:10058] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68ac22a1ca]
[runnervm0kj6c:10058] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68ac22a28b]
[runnervm0kj6c:10058] [11] plumed(+0x15365)[0x555566847365]
[runnervm0kj6c:10058] *** End of error message ***
</pre>
{% endraw %}
