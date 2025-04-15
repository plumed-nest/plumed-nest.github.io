**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az2233-502:61449] *** Process received signal ***
[fv-az2233-502:61449] Signal: Aborted (6)
[fv-az2233-502:61449] Signal code:  (-6)
[fv-az2233-502:61449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e66445330]
[fv-az2233-502:61449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e6649eb2c]
[fv-az2233-502:61449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e6644527e]
[fv-az2233-502:61449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e664288ff]
[fv-az2233-502:61449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e668a5ff5]
[fv-az2233-502:61449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e668bb0da]
[fv-az2233-502:61449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e668a5a55]
[fv-az2233-502:61449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e668a5a6f]
[fv-az2233-502:61449] [ 8] plumed_master(+0x146dd)[0x558c0ef3a6dd]
[fv-az2233-502:61449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e6642a1ca]
[fv-az2233-502:61449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e6642a28b]
[fv-az2233-502:61449] [11] plumed_master(+0x15365)[0x558c0ef3b365]
[fv-az2233-502:61449] *** End of error message ***
</pre>
{% endraw %}
