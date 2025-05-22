**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:34798] *** Process received signal ***
[pkrvmf6wy0o8zjz:34798] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34798] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34798] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6761445330]
[pkrvmf6wy0o8zjz:34798] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f676149eb2c]
[pkrvmf6wy0o8zjz:34798] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f676144527e]
[pkrvmf6wy0o8zjz:34798] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67614288ff]
[pkrvmf6wy0o8zjz:34798] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67618a5ff5]
[pkrvmf6wy0o8zjz:34798] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67618bb0da]
[pkrvmf6wy0o8zjz:34798] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67618a5a55]
[pkrvmf6wy0o8zjz:34798] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67618a5a6f]
[pkrvmf6wy0o8zjz:34798] [ 8] plumed_master(+0x146dd)[0x563c92cf76dd]
[pkrvmf6wy0o8zjz:34798] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f676142a1ca]
[pkrvmf6wy0o8zjz:34798] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f676142a28b]
[pkrvmf6wy0o8zjz:34798] [11] plumed_master(+0x15365)[0x563c92cf8365]
[pkrvmf6wy0o8zjz:34798] *** End of error message ***
</pre>
{% endraw %}
