**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[fv-az805-507:10102] *** Process received signal ***
[fv-az805-507:10102] Signal: Aborted (6)
[fv-az805-507:10102] Signal code:  (-6)
[fv-az805-507:10102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5aebe45330]
[fv-az805-507:10102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5aebe9eb2c]
[fv-az805-507:10102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5aebe4527e]
[fv-az805-507:10102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5aebe288ff]
[fv-az805-507:10102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5aec2a5ff5]
[fv-az805-507:10102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5aec2bb0da]
[fv-az805-507:10102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5aec2a5a55]
[fv-az805-507:10102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5aec2a5a6f]
[fv-az805-507:10102] [ 8] plumed_master(+0x146dd)[0x565548af96dd]
[fv-az805-507:10102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5aebe2a1ca]
[fv-az805-507:10102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5aebe2a28b]
[fv-az805-507:10102] [11] plumed_master(+0x15365)[0x565548afa365]
[fv-az805-507:10102] *** End of error message ***
</pre>
{% endraw %}
