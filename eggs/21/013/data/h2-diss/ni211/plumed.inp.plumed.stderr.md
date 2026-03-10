**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.m4lYFU/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervm0kj6c:09065] *** Process received signal ***
[runnervm0kj6c:09065] Signal: Aborted (6)
[runnervm0kj6c:09065] Signal code:  (-6)
[runnervm0kj6c:09065] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e18245330]
[runnervm0kj6c:09065] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e1829eb2c]
[runnervm0kj6c:09065] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e1824527e]
[runnervm0kj6c:09065] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e182288ff]
[runnervm0kj6c:09065] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e186a5ff5]
[runnervm0kj6c:09065] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e186bb0da]
[runnervm0kj6c:09065] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e186a5a55]
[runnervm0kj6c:09065] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e186a5a6f]
[runnervm0kj6c:09065] [ 8] plumed(+0x146dd)[0x56110cc556dd]
[runnervm0kj6c:09065] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e1822a1ca]
[runnervm0kj6c:09065] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e1822a28b]
[runnervm0kj6c:09065] [11] plumed(+0x15365)[0x56110cc56365]
[runnervm0kj6c:09065] *** End of error message ***
</pre>
{% endraw %}
