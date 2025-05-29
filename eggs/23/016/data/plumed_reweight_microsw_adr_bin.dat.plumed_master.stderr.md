**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @167 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:64499] *** Process received signal ***
[pkrvmf6wy0o8zjz:64499] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64499] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64499] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd2abe45330]
[pkrvmf6wy0o8zjz:64499] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd2abe9eb2c]
[pkrvmf6wy0o8zjz:64499] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd2abe4527e]
[pkrvmf6wy0o8zjz:64499] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2abe288ff]
[pkrvmf6wy0o8zjz:64499] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2ac2a5ff5]
[pkrvmf6wy0o8zjz:64499] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2ac2bb0da]
[pkrvmf6wy0o8zjz:64499] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2ac2a5a55]
[pkrvmf6wy0o8zjz:64499] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2ac2a5a6f]
[pkrvmf6wy0o8zjz:64499] [ 8] plumed_master(+0x146dd)[0x5595808666dd]
[pkrvmf6wy0o8zjz:64499] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd2abe2a1ca]
[pkrvmf6wy0o8zjz:64499] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd2abe2a28b]
[pkrvmf6wy0o8zjz:64499] [11] plumed_master(+0x15365)[0x559580867365]
[pkrvmf6wy0o8zjz:64499] *** End of error message ***
</pre>
{% endraw %}
