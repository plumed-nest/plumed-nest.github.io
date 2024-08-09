**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[fv-az768-943:07764] *** Process received signal ***
[fv-az768-943:07764] Signal: Aborted (6)
[fv-az768-943:07764] Signal code:  (-6)
[fv-az768-943:07764] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd832c42520]
[fv-az768-943:07764] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd832c969fc]
[fv-az768-943:07764] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd832c42476]
[fv-az768-943:07764] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd832c287f3]
[fv-az768-943:07764] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd8330a2b9e]
[fv-az768-943:07764] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd8330ae20c]
[fv-az768-943:07764] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd8330ae277]
[fv-az768-943:07764] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd8330ae52b]
[fv-az768-943:07764] [ 8] plumed_master(+0x14274)[0x556d37e04274]
[fv-az768-943:07764] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd832c29d90]
[fv-az768-943:07764] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd832c29e40]
[fv-az768-943:07764] [11] plumed_master(+0x14ed5)[0x556d37e04ed5]
[fv-az768-943:07764] *** End of error message ***
</pre>
{% endraw %}
