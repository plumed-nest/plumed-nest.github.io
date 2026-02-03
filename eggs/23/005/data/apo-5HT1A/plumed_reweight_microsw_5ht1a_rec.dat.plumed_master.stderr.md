**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @73 : keyword ARG is compulsory for this action
[runnervmkj6or:05871] *** Process received signal ***
[runnervmkj6or:05871] Signal: Aborted (6)
[runnervmkj6or:05871] Signal code:  (-6)
[runnervmkj6or:05871] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faffae45330]
[runnervmkj6or:05871] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faffae9eb2c]
[runnervmkj6or:05871] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faffae4527e]
[runnervmkj6or:05871] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faffae288ff]
[runnervmkj6or:05871] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faffb2a5ff5]
[runnervmkj6or:05871] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faffb2bb0da]
[runnervmkj6or:05871] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faffb2a5a55]
[runnervmkj6or:05871] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faffb2a5a6f]
[runnervmkj6or:05871] [ 8] plumed_master(+0x146dd)[0x55705bad66dd]
[runnervmkj6or:05871] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faffae2a1ca]
[runnervmkj6or:05871] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faffae2a28b]
[runnervmkj6or:05871] [11] plumed_master(+0x15365)[0x55705bad7365]
[runnervmkj6or:05871] *** End of error message ***
</pre>
{% endraw %}
