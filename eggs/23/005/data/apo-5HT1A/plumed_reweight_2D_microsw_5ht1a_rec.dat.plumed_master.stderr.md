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
[pkrvmq0rgcvqdmg:08618] *** Process received signal ***
[pkrvmq0rgcvqdmg:08618] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08618] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe051845330]
[pkrvmq0rgcvqdmg:08618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe05189eb2c]
[pkrvmq0rgcvqdmg:08618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe05184527e]
[pkrvmq0rgcvqdmg:08618] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0518288ff]
[pkrvmq0rgcvqdmg:08618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe051ca5ff5]
[pkrvmq0rgcvqdmg:08618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe051cbb0da]
[pkrvmq0rgcvqdmg:08618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe051ca5a55]
[pkrvmq0rgcvqdmg:08618] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe051ca5a6f]
[pkrvmq0rgcvqdmg:08618] [ 8] plumed_master(+0x146dd)[0x560911c336dd]
[pkrvmq0rgcvqdmg:08618] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe05182a1ca]
[pkrvmq0rgcvqdmg:08618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe05182a28b]
[pkrvmq0rgcvqdmg:08618] [11] plumed_master(+0x15365)[0x560911c34365]
[pkrvmq0rgcvqdmg:08618] *** End of error message ***
</pre>
{% endraw %}
