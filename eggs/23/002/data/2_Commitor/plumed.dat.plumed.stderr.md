**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1429-284:05077] *** Process received signal ***
[fv-az1429-284:05077] Signal: Aborted (6)
[fv-az1429-284:05077] Signal code:  (-6)
[fv-az1429-284:05077] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f07b7842520]
[fv-az1429-284:05077] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f07b78969fc]
[fv-az1429-284:05077] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f07b7842476]
[fv-az1429-284:05077] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f07b78287f3]
[fv-az1429-284:05077] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f07b7ca2b9e]
[fv-az1429-284:05077] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f07b7cae20c]
[fv-az1429-284:05077] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f07b7cae277]
[fv-az1429-284:05077] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f07b7cae52b]
[fv-az1429-284:05077] [ 8] plumed(+0x14254)[0x558b375d3254]
[fv-az1429-284:05077] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f07b7829d90]
[fv-az1429-284:05077] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f07b7829e40]
[fv-az1429-284:05077] [11] plumed(+0x14eb5)[0x558b375d3eb5]
[fv-az1429-284:05077] *** End of error message ***
</pre>
{% endraw %}