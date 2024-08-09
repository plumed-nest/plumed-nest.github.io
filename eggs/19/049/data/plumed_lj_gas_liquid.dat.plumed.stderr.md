**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CLUSTER_PROPERTIES with label clust1 : cannot understand the following words from the input line : ARG=lq
[fv-az1019-654:08687] *** Process received signal ***
[fv-az1019-654:08687] Signal: Aborted (6)
[fv-az1019-654:08687] Signal code:  (-6)
[fv-az1019-654:08687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe5c1242520]
[fv-az1019-654:08687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe5c12969fc]
[fv-az1019-654:08687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe5c1242476]
[fv-az1019-654:08687] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe5c12287f3]
[fv-az1019-654:08687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe5c16a2b9e]
[fv-az1019-654:08687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe5c16ae20c]
[fv-az1019-654:08687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe5c16ae277]
[fv-az1019-654:08687] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe5c16ae52b]
[fv-az1019-654:08687] [ 8] plumed(+0x12f48)[0x564829187f48]
[fv-az1019-654:08687] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe5c1229d90]
[fv-az1019-654:08687] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe5c1229e40]
[fv-az1019-654:08687] [11] plumed(+0x131e5)[0x5648291881e5]
[fv-az1019-654:08687] *** End of error message ***
</pre>
{% endraw %}
