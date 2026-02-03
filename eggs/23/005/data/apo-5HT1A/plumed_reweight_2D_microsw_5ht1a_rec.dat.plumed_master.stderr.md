**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[runnervmkj6or:05833] *** Process received signal ***
[runnervmkj6or:05833] Signal: Aborted (6)
[runnervmkj6or:05833] Signal code:  (-6)
[runnervmkj6or:05833] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f767a645330]
[runnervmkj6or:05833] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f767a69eb2c]
[runnervmkj6or:05833] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f767a64527e]
[runnervmkj6or:05833] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f767a6288ff]
[runnervmkj6or:05833] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f767aaa5ff5]
[runnervmkj6or:05833] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f767aabb0da]
[runnervmkj6or:05833] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f767aaa5a55]
[runnervmkj6or:05833] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f767aaa5a6f]
[runnervmkj6or:05833] [ 8] plumed_master(+0x146dd)[0x55a018acf6dd]
[runnervmkj6or:05833] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f767a62a1ca]
[runnervmkj6or:05833] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f767a62a28b]
[runnervmkj6or:05833] [11] plumed_master(+0x15365)[0x55a018ad0365]
[runnervmkj6or:05833] *** End of error message ***
</pre>
{% endraw %}
