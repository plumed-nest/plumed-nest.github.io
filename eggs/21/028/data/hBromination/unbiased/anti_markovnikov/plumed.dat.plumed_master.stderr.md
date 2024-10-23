**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:221) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az801-114:08060] *** Process received signal ***
[fv-az801-114:08060] Signal: Aborted (6)
[fv-az801-114:08060] Signal code:  (-6)
[fv-az801-114:08060] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa1d9a42520]
[fv-az801-114:08060] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa1d9a969fc]
[fv-az801-114:08060] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa1d9a42476]
[fv-az801-114:08060] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa1d9a287f3]
[fv-az801-114:08060] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa1d9ea2b9e]
[fv-az801-114:08060] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa1d9eae20c]
[fv-az801-114:08060] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa1d9eae277]
[fv-az801-114:08060] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa1d9eae52b]
[fv-az801-114:08060] [ 8] plumed_master(+0x14254)[0x55f8ce112254]
[fv-az801-114:08060] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa1d9a29d90]
[fv-az801-114:08060] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa1d9a29e40]
[fv-az801-114:08060] [11] plumed_master(+0x14eb5)[0x55f8ce112eb5]
[fv-az801-114:08060] *** End of error message ***
</pre>
{% endraw %}
