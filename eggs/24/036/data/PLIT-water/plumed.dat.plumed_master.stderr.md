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
[fv-az807-718:61455] *** Process received signal ***
[fv-az807-718:61455] Signal: Aborted (6)
[fv-az807-718:61455] Signal code:  (-6)
[fv-az807-718:61455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe62e245330]
[fv-az807-718:61455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe62e29eb2c]
[fv-az807-718:61455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe62e24527e]
[fv-az807-718:61455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe62e2288ff]
[fv-az807-718:61455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe62e6a5ff5]
[fv-az807-718:61455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe62e6bb0da]
[fv-az807-718:61455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe62e6a5a55]
[fv-az807-718:61455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe62e6a5a6f]
[fv-az807-718:61455] [ 8] plumed_master(+0x146dd)[0x55d6554dd6dd]
[fv-az807-718:61455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe62e22a1ca]
[fv-az807-718:61455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe62e22a28b]
[fv-az807-718:61455] [11] plumed_master(+0x15365)[0x55d6554de365]
[fv-az807-718:61455] *** End of error message ***
</pre>
{% endraw %}
