**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1771-923:09664] *** Process received signal ***
[fv-az1771-923:09664] Signal: Aborted (6)
[fv-az1771-923:09664] Signal code:  (-6)
[fv-az1771-923:09664] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f098f242520]
[fv-az1771-923:09664] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f098f2969fc]
[fv-az1771-923:09664] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f098f242476]
[fv-az1771-923:09664] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f098f2287f3]
[fv-az1771-923:09664] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f098f6a2b9e]
[fv-az1771-923:09664] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f098f6ae20c]
[fv-az1771-923:09664] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f098f6ae277]
[fv-az1771-923:09664] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f098f6ae52b]
[fv-az1771-923:09664] [ 8] plumed(+0x12f48)[0x55e43feaaf48]
[fv-az1771-923:09664] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f098f229d90]
[fv-az1771-923:09664] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f098f229e40]
[fv-az1771-923:09664] [11] plumed(+0x131e5)[0x55e43feab1e5]
[fv-az1771-923:09664] *** End of error message ***
</pre>
{% endraw %}
