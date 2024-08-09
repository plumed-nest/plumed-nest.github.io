**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az768-943:09601] *** Process received signal ***
[fv-az768-943:09601] Signal: Aborted (6)
[fv-az768-943:09601] Signal code:  (-6)
[fv-az768-943:09601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f58c8442520]
[fv-az768-943:09601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f58c84969fc]
[fv-az768-943:09601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f58c8442476]
[fv-az768-943:09601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f58c84287f3]
[fv-az768-943:09601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f58c88a2b9e]
[fv-az768-943:09601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f58c88ae20c]
[fv-az768-943:09601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f58c88ae277]
[fv-az768-943:09601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f58c88ae52b]
[fv-az768-943:09601] [ 8] plumed_master(+0x14274)[0x55cc1f970274]
[fv-az768-943:09601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f58c8429d90]
[fv-az768-943:09601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f58c8429e40]
[fv-az768-943:09601] [11] plumed_master(+0x14ed5)[0x55cc1f970ed5]
[fv-az768-943:09601] *** End of error message ***
</pre>
{% endraw %}
