**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1771-923:07871] *** Process received signal ***
[fv-az1771-923:07871] Signal: Aborted (6)
[fv-az1771-923:07871] Signal code:  (-6)
[fv-az1771-923:07871] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3914242520]
[fv-az1771-923:07871] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f39142969fc]
[fv-az1771-923:07871] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3914242476]
[fv-az1771-923:07871] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f39142287f3]
[fv-az1771-923:07871] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f39146a2b9e]
[fv-az1771-923:07871] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f39146ae20c]
[fv-az1771-923:07871] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f39146ae277]
[fv-az1771-923:07871] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f39146ae52b]
[fv-az1771-923:07871] [ 8] plumed_master(+0x14274)[0x563965e1c274]
[fv-az1771-923:07871] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3914229d90]
[fv-az1771-923:07871] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3914229e40]
[fv-az1771-923:07871] [11] plumed_master(+0x14ed5)[0x563965e1ced5]
[fv-az1771-923:07871] *** End of error message ***
</pre>
{% endraw %}
