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
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:61968] *** Process received signal ***
[pkrvmf6wy0o8zjz:61968] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:61968] Signal code:  (-6)
[pkrvmf6wy0o8zjz:61968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2f3445330]
[pkrvmf6wy0o8zjz:61968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2f349eb2c]
[pkrvmf6wy0o8zjz:61968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2f344527e]
[pkrvmf6wy0o8zjz:61968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2f34288ff]
[pkrvmf6wy0o8zjz:61968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2f38a5ff5]
[pkrvmf6wy0o8zjz:61968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2f38bb0da]
[pkrvmf6wy0o8zjz:61968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2f38a5a55]
[pkrvmf6wy0o8zjz:61968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2f38a5a6f]
[pkrvmf6wy0o8zjz:61968] [ 8] plumed_master(+0x146dd)[0x5647d40916dd]
[pkrvmf6wy0o8zjz:61968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2f342a1ca]
[pkrvmf6wy0o8zjz:61968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2f342a28b]
[pkrvmf6wy0o8zjz:61968] [11] plumed_master(+0x15365)[0x5647d4092365]
[pkrvmf6wy0o8zjz:61968] *** End of error message ***
</pre>
{% endraw %}
