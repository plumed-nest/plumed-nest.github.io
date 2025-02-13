**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/Multicanonical/Analysis/SampledDistribution/plumed.dat   
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
[fv-az1046-619:11371] *** Process received signal ***
[fv-az1046-619:11371] Signal: Aborted (6)
[fv-az1046-619:11371] Signal code:  (-6)
[fv-az1046-619:11371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f947b245330]
[fv-az1046-619:11371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f947b29eb2c]
[fv-az1046-619:11371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f947b24527e]
[fv-az1046-619:11371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f947b2288ff]
[fv-az1046-619:11371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f947b6a5ff5]
[fv-az1046-619:11371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f947b6bb0da]
[fv-az1046-619:11371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f947b6a5a55]
[fv-az1046-619:11371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f947b6a5a6f]
[fv-az1046-619:11371] [ 8] plumed_master(+0x146dd)[0x563ba6c696dd]
[fv-az1046-619:11371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f947b22a1ca]
[fv-az1046-619:11371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f947b22a28b]
[fv-az1046-619:11371] [11] plumed_master(+0x15365)[0x563ba6c6a365]
[fv-az1046-619:11371] *** End of error message ***
</pre>
{% endraw %}
