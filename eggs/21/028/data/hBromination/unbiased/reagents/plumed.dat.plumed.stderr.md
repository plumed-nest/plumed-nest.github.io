**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az801-114:08120] *** Process received signal ***
[fv-az801-114:08120] Signal: Aborted (6)
[fv-az801-114:08120] Signal code:  (-6)
[fv-az801-114:08120] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fcd36c42520]
[fv-az801-114:08120] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fcd36c969fc]
[fv-az801-114:08120] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fcd36c42476]
[fv-az801-114:08120] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fcd36c287f3]
[fv-az801-114:08120] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fcd370a2b9e]
[fv-az801-114:08120] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fcd370ae20c]
[fv-az801-114:08120] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fcd370ae277]
[fv-az801-114:08120] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fcd370ae52b]
[fv-az801-114:08120] [ 8] plumed(+0x14254)[0x5631f25cc254]
[fv-az801-114:08120] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fcd36c29d90]
[fv-az801-114:08120] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fcd36c29e40]
[fv-az801-114:08120] [11] plumed(+0x14eb5)[0x5631f25cceb5]
[fv-az801-114:08120] *** End of error message ***
</pre>
{% endraw %}
