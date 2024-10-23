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
[fv-az975-395:07874] *** Process received signal ***
[fv-az975-395:07874] Signal: Aborted (6)
[fv-az975-395:07874] Signal code:  (-6)
[fv-az975-395:07874] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa4daa42520]
[fv-az975-395:07874] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa4daa969fc]
[fv-az975-395:07874] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa4daa42476]
[fv-az975-395:07874] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa4daa287f3]
[fv-az975-395:07874] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa4daea2b9e]
[fv-az975-395:07874] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa4daeae20c]
[fv-az975-395:07874] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa4daeae277]
[fv-az975-395:07874] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa4daeae52b]
[fv-az975-395:07874] [ 8] plumed_master(+0x14254)[0x555e55e9a254]
[fv-az975-395:07874] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa4daa29d90]
[fv-az975-395:07874] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa4daa29e40]
[fv-az975-395:07874] [11] plumed_master(+0x14eb5)[0x555e55e9aeb5]
[fv-az975-395:07874] *** End of error message ***
</pre>
{% endraw %}
