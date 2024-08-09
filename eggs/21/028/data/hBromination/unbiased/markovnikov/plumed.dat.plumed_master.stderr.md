**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[fv-az768-943:07853] *** Process received signal ***
[fv-az768-943:07853] Signal: Aborted (6)
[fv-az768-943:07853] Signal code:  (-6)
[fv-az768-943:07853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe761442520]
[fv-az768-943:07853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe7614969fc]
[fv-az768-943:07853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe761442476]
[fv-az768-943:07853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe7614287f3]
[fv-az768-943:07853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe7618a2b9e]
[fv-az768-943:07853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe7618ae20c]
[fv-az768-943:07853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe7618ae277]
[fv-az768-943:07853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe7618ae52b]
[fv-az768-943:07853] [ 8] plumed_master(+0x14274)[0x55f11daf6274]
[fv-az768-943:07853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe761429d90]
[fv-az768-943:07853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe761429e40]
[fv-az768-943:07853] [11] plumed_master(+0x14ed5)[0x55f11daf6ed5]
[fv-az768-943:07853] *** End of error message ***
</pre>
{% endraw %}
