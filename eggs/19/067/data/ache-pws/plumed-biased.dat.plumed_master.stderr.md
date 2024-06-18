**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1771-923:09732] *** Process received signal ***
[fv-az1771-923:09732] Signal: Aborted (6)
[fv-az1771-923:09732] Signal code:  (-6)
[fv-az1771-923:09732] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f113cc42520]
[fv-az1771-923:09732] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f113cc969fc]
[fv-az1771-923:09732] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f113cc42476]
[fv-az1771-923:09732] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f113cc287f3]
[fv-az1771-923:09732] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f113d0a2b9e]
[fv-az1771-923:09732] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f113d0ae20c]
[fv-az1771-923:09732] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f113d0ae277]
[fv-az1771-923:09732] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f113d0ae52b]
[fv-az1771-923:09732] [ 8] plumed_master(+0x14274)[0x5581d7a32274]
[fv-az1771-923:09732] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f113cc29d90]
[fv-az1771-923:09732] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f113cc29e40]
[fv-az1771-923:09732] [11] plumed_master(+0x14ed5)[0x5581d7a32ed5]
[fv-az1771-923:09732] *** End of error message ***
</pre>
{% endraw %}
