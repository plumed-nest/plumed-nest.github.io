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
[fv-az1771-923:09672] *** Process received signal ***
[fv-az1771-923:09672] Signal: Aborted (6)
[fv-az1771-923:09672] Signal code:  (-6)
[fv-az1771-923:09672] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc631042520]
[fv-az1771-923:09672] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc6310969fc]
[fv-az1771-923:09672] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc631042476]
[fv-az1771-923:09672] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc6310287f3]
[fv-az1771-923:09672] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc6314a2b9e]
[fv-az1771-923:09672] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc6314ae20c]
[fv-az1771-923:09672] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc6314ae277]
[fv-az1771-923:09672] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc6314ae52b]
[fv-az1771-923:09672] [ 8] plumed_master(+0x14274)[0x555bc5d73274]
[fv-az1771-923:09672] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc631029d90]
[fv-az1771-923:09672] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc631029e40]
[fv-az1771-923:09672] [11] plumed_master(+0x14ed5)[0x555bc5d73ed5]
[fv-az1771-923:09672] *** End of error message ***
</pre>
{% endraw %}
