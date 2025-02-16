**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az787-589:60558] *** Process received signal ***
[fv-az787-589:60558] Signal: Aborted (6)
[fv-az787-589:60558] Signal code:  (-6)
[fv-az787-589:60558] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f54d9e45330]
[fv-az787-589:60558] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f54d9e9eb2c]
[fv-az787-589:60558] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f54d9e4527e]
[fv-az787-589:60558] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f54d9e288ff]
[fv-az787-589:60558] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f54da2a5ff5]
[fv-az787-589:60558] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f54da2bb0da]
[fv-az787-589:60558] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f54da2a5a55]
[fv-az787-589:60558] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f54da2a5a6f]
[fv-az787-589:60558] [ 8] plumed_master(+0x146dd)[0x55b8b80d76dd]
[fv-az787-589:60558] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f54d9e2a1ca]
[fv-az787-589:60558] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f54d9e2a28b]
[fv-az787-589:60558] [11] plumed_master(+0x15365)[0x55b8b80d8365]
[fv-az787-589:60558] *** End of error message ***
</pre>
{% endraw %}
