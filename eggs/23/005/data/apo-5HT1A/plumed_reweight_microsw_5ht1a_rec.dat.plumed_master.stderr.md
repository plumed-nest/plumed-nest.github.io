**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @113 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:08657] *** Process received signal ***
[pkrvmq0rgcvqdmg:08657] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08657] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08657] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f445b845330]
[pkrvmq0rgcvqdmg:08657] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f445b89eb2c]
[pkrvmq0rgcvqdmg:08657] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f445b84527e]
[pkrvmq0rgcvqdmg:08657] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f445b8288ff]
[pkrvmq0rgcvqdmg:08657] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f445bca5ff5]
[pkrvmq0rgcvqdmg:08657] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f445bcbb0da]
[pkrvmq0rgcvqdmg:08657] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f445bca5a55]
[pkrvmq0rgcvqdmg:08657] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f445bca5a6f]
[pkrvmq0rgcvqdmg:08657] [ 8] plumed_master(+0x146dd)[0x55bb1a7ce6dd]
[pkrvmq0rgcvqdmg:08657] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f445b82a1ca]
[pkrvmq0rgcvqdmg:08657] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f445b82a28b]
[pkrvmq0rgcvqdmg:08657] [11] plumed_master(+0x15365)[0x55bb1a7cf365]
[pkrvmq0rgcvqdmg:08657] *** End of error message ***
</pre>
{% endraw %}
