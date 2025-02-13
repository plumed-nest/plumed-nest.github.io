**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp400K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[fv-az1046-619:11464] *** Process received signal ***
[fv-az1046-619:11464] Signal: Aborted (6)
[fv-az1046-619:11464] Signal code:  (-6)
[fv-az1046-619:11464] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fceca845330]
[fv-az1046-619:11464] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fceca89eb2c]
[fv-az1046-619:11464] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fceca84527e]
[fv-az1046-619:11464] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fceca8288ff]
[fv-az1046-619:11464] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcecaca5ff5]
[fv-az1046-619:11464] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcecacbb0da]
[fv-az1046-619:11464] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcecaca5a55]
[fv-az1046-619:11464] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcecaca5a6f]
[fv-az1046-619:11464] [ 8] plumed_master(+0x146dd)[0x558fddd556dd]
[fv-az1046-619:11464] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fceca82a1ca]
[fv-az1046-619:11464] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fceca82a28b]
[fv-az1046-619:11464] [11] plumed_master(+0x15365)[0x558fddd56365]
[fv-az1046-619:11464] *** End of error message ***
</pre>
{% endraw %}
