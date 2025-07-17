**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:11602] *** Process received signal ***
[pkrvmq0rgcvqdmg:11602] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11602] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbe4b045330]
[pkrvmq0rgcvqdmg:11602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbe4b09eb2c]
[pkrvmq0rgcvqdmg:11602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbe4b04527e]
[pkrvmq0rgcvqdmg:11602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbe4b0288ff]
[pkrvmq0rgcvqdmg:11602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbe4b4a5ff5]
[pkrvmq0rgcvqdmg:11602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbe4b4bb0da]
[pkrvmq0rgcvqdmg:11602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbe4b4a5a55]
[pkrvmq0rgcvqdmg:11602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbe4b4a5a6f]
[pkrvmq0rgcvqdmg:11602] [ 8] plumed_master(+0x146dd)[0x564162f476dd]
[pkrvmq0rgcvqdmg:11602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbe4b02a1ca]
[pkrvmq0rgcvqdmg:11602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbe4b02a28b]
[pkrvmq0rgcvqdmg:11602] [11] plumed_master(+0x15365)[0x564162f48365]
[pkrvmq0rgcvqdmg:11602] *** End of error message ***
</pre>
{% endraw %}
