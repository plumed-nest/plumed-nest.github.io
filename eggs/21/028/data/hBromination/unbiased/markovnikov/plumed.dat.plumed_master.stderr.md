**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[fv-az801-114:08095] *** Process received signal ***
[fv-az801-114:08095] Signal: Aborted (6)
[fv-az801-114:08095] Signal code:  (-6)
[fv-az801-114:08095] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f22a9042520]
[fv-az801-114:08095] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f22a90969fc]
[fv-az801-114:08095] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f22a9042476]
[fv-az801-114:08095] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f22a90287f3]
[fv-az801-114:08095] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f22a94a2b9e]
[fv-az801-114:08095] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f22a94ae20c]
[fv-az801-114:08095] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f22a94ae277]
[fv-az801-114:08095] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f22a94ae52b]
[fv-az801-114:08095] [ 8] plumed_master(+0x14254)[0x55dd8ed95254]
[fv-az801-114:08095] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f22a9029d90]
[fv-az801-114:08095] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f22a9029e40]
[fv-az801-114:08095] [11] plumed_master(+0x14eb5)[0x55dd8ed95eb5]
[fv-az801-114:08095] *** End of error message ***
</pre>
{% endraw %}
