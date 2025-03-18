**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[fv-az790-36:61455] *** Process received signal ***
[fv-az790-36:61455] Signal: Aborted (6)
[fv-az790-36:61455] Signal code:  (-6)
[fv-az790-36:61455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a83245330]
[fv-az790-36:61455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a8329eb2c]
[fv-az790-36:61455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a8324527e]
[fv-az790-36:61455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a832288ff]
[fv-az790-36:61455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a836a5ff5]
[fv-az790-36:61455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a836bb0da]
[fv-az790-36:61455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a836a5a55]
[fv-az790-36:61455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a836a5a6f]
[fv-az790-36:61455] [ 8] plumed_master(+0x146dd)[0x560c94ac66dd]
[fv-az790-36:61455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a8322a1ca]
[fv-az790-36:61455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a8322a28b]
[fv-az790-36:61455] [11] plumed_master(+0x15365)[0x560c94ac7365]
[fv-az790-36:61455] *** End of error message ***
</pre>
{% endraw %}
