**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1442-469:09500] *** Process received signal ***
[fv-az1442-469:09500] Signal: Aborted (6)
[fv-az1442-469:09500] Signal code:  (-6)
[fv-az1442-469:09500] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f71acc42520]
[fv-az1442-469:09500] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f71acc969fc]
[fv-az1442-469:09500] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f71acc42476]
[fv-az1442-469:09500] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f71acc287f3]
[fv-az1442-469:09500] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f71ad0a2b9e]
[fv-az1442-469:09500] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f71ad0ae20c]
[fv-az1442-469:09500] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f71ad0ae277]
[fv-az1442-469:09500] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f71ad0ae52b]
[fv-az1442-469:09500] [ 8] plumed(+0x14254)[0x559227cb3254]
[fv-az1442-469:09500] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f71acc29d90]
[fv-az1442-469:09500] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f71acc29e40]
[fv-az1442-469:09500] [11] plumed(+0x14eb5)[0x559227cb3eb5]
[fv-az1442-469:09500] *** End of error message ***
</pre>
{% endraw %}
