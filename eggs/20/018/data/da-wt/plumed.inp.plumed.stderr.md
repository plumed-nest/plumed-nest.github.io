**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.SIyXFP/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmq0rgcvqdmg:11366] *** Process received signal ***
[pkrvmq0rgcvqdmg:11366] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11366] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11366] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5671645330]
[pkrvmq0rgcvqdmg:11366] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f567169eb2c]
[pkrvmq0rgcvqdmg:11366] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f567164527e]
[pkrvmq0rgcvqdmg:11366] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56716288ff]
[pkrvmq0rgcvqdmg:11366] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5671aa5ff5]
[pkrvmq0rgcvqdmg:11366] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5671abb0da]
[pkrvmq0rgcvqdmg:11366] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5671aa5a55]
[pkrvmq0rgcvqdmg:11366] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5671aa5a6f]
[pkrvmq0rgcvqdmg:11366] [ 8] plumed(+0x146dd)[0x5641d61fd6dd]
[pkrvmq0rgcvqdmg:11366] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f567162a1ca]
[pkrvmq0rgcvqdmg:11366] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f567162a28b]
[pkrvmq0rgcvqdmg:11366] [11] plumed(+0x15365)[0x5641d61fe365]
[pkrvmq0rgcvqdmg:11366] *** End of error message ***
</pre>
{% endraw %}
