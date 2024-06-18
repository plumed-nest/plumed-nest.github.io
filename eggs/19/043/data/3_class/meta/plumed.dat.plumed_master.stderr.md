**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az695-955:08321] *** Process received signal ***
[fv-az695-955:08321] Signal: Aborted (6)
[fv-az695-955:08321] Signal code:  (-6)
[fv-az695-955:08321] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc139c42520]
[fv-az695-955:08321] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc139c969fc]
[fv-az695-955:08321] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc139c42476]
[fv-az695-955:08321] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc139c287f3]
[fv-az695-955:08321] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc13a0a2b9e]
[fv-az695-955:08321] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc13a0ae20c]
[fv-az695-955:08321] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc13a0ae277]
[fv-az695-955:08321] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc13a0ae52b]
[fv-az695-955:08321] [ 8] plumed_master(+0x14274)[0x5632e19be274]
[fv-az695-955:08321] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc139c29d90]
[fv-az695-955:08321] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc139c29e40]
[fv-az695-955:08321] [11] plumed_master(+0x14ed5)[0x5632e19beed5]
[fv-az695-955:08321] *** End of error message ***
</pre>
{% endraw %}
