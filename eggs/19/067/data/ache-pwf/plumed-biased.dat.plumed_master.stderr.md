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
[fv-az1442-469:09510] *** Process received signal ***
[fv-az1442-469:09510] Signal: Aborted (6)
[fv-az1442-469:09510] Signal code:  (-6)
[fv-az1442-469:09510] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fef71a42520]
[fv-az1442-469:09510] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fef71a969fc]
[fv-az1442-469:09510] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fef71a42476]
[fv-az1442-469:09510] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fef71a287f3]
[fv-az1442-469:09510] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fef71ea2b9e]
[fv-az1442-469:09510] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fef71eae20c]
[fv-az1442-469:09510] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fef71eae277]
[fv-az1442-469:09510] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fef71eae52b]
[fv-az1442-469:09510] [ 8] plumed_master(+0x14254)[0x55f24b525254]
[fv-az1442-469:09510] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fef71a29d90]
[fv-az1442-469:09510] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fef71a29e40]
[fv-az1442-469:09510] [11] plumed_master(+0x14eb5)[0x55f24b525eb5]
[fv-az1442-469:09510] *** End of error message ***
</pre>
{% endraw %}
