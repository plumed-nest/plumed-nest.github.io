**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.IOLL2B/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervm0kj6c:08921] *** Process received signal ***
[runnervm0kj6c:08921] Signal: Aborted (6)
[runnervm0kj6c:08921] Signal code:  (-6)
[runnervm0kj6c:08921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f17b4045330]
[runnervm0kj6c:08921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f17b409eb2c]
[runnervm0kj6c:08921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f17b404527e]
[runnervm0kj6c:08921] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17b40288ff]
[runnervm0kj6c:08921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f17b44a5ff5]
[runnervm0kj6c:08921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f17b44bb0da]
[runnervm0kj6c:08921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f17b44a5a55]
[runnervm0kj6c:08921] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f17b44a5a6f]
[runnervm0kj6c:08921] [ 8] plumed_master(+0x146dd)[0x56224e3236dd]
[runnervm0kj6c:08921] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f17b402a1ca]
[runnervm0kj6c:08921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f17b402a28b]
[runnervm0kj6c:08921] [11] plumed_master(+0x15365)[0x56224e324365]
[runnervm0kj6c:08921] *** End of error message ***
</pre>
{% endraw %}
