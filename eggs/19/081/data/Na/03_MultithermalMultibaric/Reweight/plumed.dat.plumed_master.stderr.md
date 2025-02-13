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
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az1046-619:11033] *** Process received signal ***
[fv-az1046-619:11033] Signal: Aborted (6)
[fv-az1046-619:11033] Signal code:  (-6)
[fv-az1046-619:11033] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb9cfa45330]
[fv-az1046-619:11033] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb9cfa9eb2c]
[fv-az1046-619:11033] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb9cfa4527e]
[fv-az1046-619:11033] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb9cfa288ff]
[fv-az1046-619:11033] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb9cfea5ff5]
[fv-az1046-619:11033] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb9cfebb0da]
[fv-az1046-619:11033] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb9cfea5a55]
[fv-az1046-619:11033] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb9cfea5a6f]
[fv-az1046-619:11033] [ 8] plumed_master(+0x146dd)[0x55a9aace66dd]
[fv-az1046-619:11033] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb9cfa2a1ca]
[fv-az1046-619:11033] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb9cfa2a28b]
[fv-az1046-619:11033] [11] plumed_master(+0x15365)[0x55a9aace7365]
[fv-az1046-619:11033] *** End of error message ***
</pre>
{% endraw %}
