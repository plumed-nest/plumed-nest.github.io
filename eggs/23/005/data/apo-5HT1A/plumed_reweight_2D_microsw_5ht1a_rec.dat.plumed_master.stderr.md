**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:07545] *** Process received signal ***
[pkrvmxyh4eaekms:07545] Signal: Aborted (6)
[pkrvmxyh4eaekms:07545] Signal code:  (-6)
[pkrvmxyh4eaekms:07545] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff7c4c45330]
[pkrvmxyh4eaekms:07545] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff7c4c9eb2c]
[pkrvmxyh4eaekms:07545] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff7c4c4527e]
[pkrvmxyh4eaekms:07545] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7c4c288ff]
[pkrvmxyh4eaekms:07545] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7c50a5ff5]
[pkrvmxyh4eaekms:07545] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7c50bb0da]
[pkrvmxyh4eaekms:07545] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7c50a5a55]
[pkrvmxyh4eaekms:07545] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7c50a5a6f]
[pkrvmxyh4eaekms:07545] [ 8] plumed_master(+0x146dd)[0x55c4b6f5d6dd]
[pkrvmxyh4eaekms:07545] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff7c4c2a1ca]
[pkrvmxyh4eaekms:07545] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff7c4c2a28b]
[pkrvmxyh4eaekms:07545] [11] plumed_master(+0x15365)[0x55c4b6f5e365]
[pkrvmxyh4eaekms:07545] *** End of error message ***
</pre>
{% endraw %}
