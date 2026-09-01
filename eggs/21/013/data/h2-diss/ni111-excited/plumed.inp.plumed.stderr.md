**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.hw497v/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.1.so ../../data/ReweightGeomFES.cpp

[runnervmgx7h7:09002] *** Process received signal ***
[runnervmgx7h7:09002] Signal: Aborted (6)
[runnervmgx7h7:09002] Signal code:  (-6)
[runnervmgx7h7:09002] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9392045330]
[runnervmgx7h7:09002] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f939209ec0c]
[runnervmgx7h7:09002] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f939204527e]
[runnervmgx7h7:09002] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93920288ff]
[runnervmgx7h7:09002] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93924a5ff5]
[runnervmgx7h7:09002] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93924bb0da]
[runnervmgx7h7:09002] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93924a5a55]
[runnervmgx7h7:09002] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93924a5a6f]
[runnervmgx7h7:09002] [ 8] plumed(+0x146dd)[0x556f58a936dd]
[runnervmgx7h7:09002] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f939202a1ca]
[runnervmgx7h7:09002] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f939202a28b]
[runnervmgx7h7:09002] [11] plumed(+0x15365)[0x556f58a94365]
[runnervmgx7h7:09002] *** End of error message ***
</pre>
{% endraw %}
