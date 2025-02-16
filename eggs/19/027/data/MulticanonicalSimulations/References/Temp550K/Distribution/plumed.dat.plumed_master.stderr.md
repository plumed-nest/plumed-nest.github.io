**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp550K/Distribution/plumed.dat   
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
[fv-az1112-175:71400] *** Process received signal ***
[fv-az1112-175:71400] Signal: Aborted (6)
[fv-az1112-175:71400] Signal code:  (-6)
[fv-az1112-175:71400] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6e1c45330]
[fv-az1112-175:71400] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6e1c9eb2c]
[fv-az1112-175:71400] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6e1c4527e]
[fv-az1112-175:71400] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6e1c288ff]
[fv-az1112-175:71400] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6e20a5ff5]
[fv-az1112-175:71400] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6e20bb0da]
[fv-az1112-175:71400] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6e20a5a55]
[fv-az1112-175:71400] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6e20a5a6f]
[fv-az1112-175:71400] [ 8] plumed_master(+0x146dd)[0x564c31b146dd]
[fv-az1112-175:71400] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6e1c2a1ca]
[fv-az1112-175:71400] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6e1c2a28b]
[fv-az1112-175:71400] [11] plumed_master(+0x15365)[0x564c31b15365]
[fv-az1112-175:71400] *** End of error message ***
</pre>
{% endraw %}
