**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14724-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.9KQegA/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervm0kj6c:06355] *** Process received signal ***
[runnervm0kj6c:06355] Signal: Aborted (6)
[runnervm0kj6c:06355] Signal code:  (-6)
[runnervm0kj6c:06355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f477be45330]
[runnervm0kj6c:06355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f477be9eb2c]
[runnervm0kj6c:06355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f477be4527e]
[runnervm0kj6c:06355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f477be288ff]
[runnervm0kj6c:06355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f477c2a5ff5]
[runnervm0kj6c:06355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f477c2bb0da]
[runnervm0kj6c:06355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f477c2a5a55]
[runnervm0kj6c:06355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f477c2a5a6f]
[runnervm0kj6c:06355] [ 8] plumed(+0x146dd)[0x5583357ca6dd]
[runnervm0kj6c:06355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f477be2a1ca]
[runnervm0kj6c:06355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f477be2a28b]
[runnervm0kj6c:06355] [11] plumed(+0x15365)[0x5583357cb365]
[runnervm0kj6c:06355] *** End of error message ***
</pre>
{% endraw %}
