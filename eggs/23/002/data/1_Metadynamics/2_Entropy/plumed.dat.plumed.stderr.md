**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1429-284:04978] *** Process received signal ***
[fv-az1429-284:04978] Signal: Aborted (6)
[fv-az1429-284:04978] Signal code:  (-6)
[fv-az1429-284:04978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f39e2e42520]
[fv-az1429-284:04978] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f39e2e969fc]
[fv-az1429-284:04978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f39e2e42476]
[fv-az1429-284:04978] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f39e2e287f3]
[fv-az1429-284:04978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f39e32a2b9e]
[fv-az1429-284:04978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f39e32ae20c]
[fv-az1429-284:04978] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f39e32ae277]
[fv-az1429-284:04978] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f39e32ae52b]
[fv-az1429-284:04978] [ 8] plumed(+0x14254)[0x55e0ae1e0254]
[fv-az1429-284:04978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f39e2e29d90]
[fv-az1429-284:04978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f39e2e29e40]
[fv-az1429-284:04978] [11] plumed(+0x14eb5)[0x55e0ae1e0eb5]
[fv-az1429-284:04978] *** End of error message ***
</pre>
{% endraw %}
