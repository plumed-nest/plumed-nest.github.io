**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @31 : keyword ARG is compulsory for this action
[fv-az787-589:60261] *** Process received signal ***
[fv-az787-589:60261] Signal: Aborted (6)
[fv-az787-589:60261] Signal code:  (-6)
[fv-az787-589:60261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4d5d245330]
[fv-az787-589:60261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4d5d29eb2c]
[fv-az787-589:60261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4d5d24527e]
[fv-az787-589:60261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4d5d2288ff]
[fv-az787-589:60261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4d5d6a5ff5]
[fv-az787-589:60261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4d5d6bb0da]
[fv-az787-589:60261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4d5d6a5a55]
[fv-az787-589:60261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4d5d6a5a6f]
[fv-az787-589:60261] [ 8] plumed_master(+0x146dd)[0x55b732def6dd]
[fv-az787-589:60261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4d5d22a1ca]
[fv-az787-589:60261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4d5d22a28b]
[fv-az787-589:60261] [11] plumed_master(+0x15365)[0x55b732df0365]
[fv-az787-589:60261] *** End of error message ***
</pre>
{% endraw %}
