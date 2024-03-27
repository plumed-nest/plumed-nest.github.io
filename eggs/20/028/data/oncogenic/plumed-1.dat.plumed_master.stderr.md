**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:149) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[fv-az1200-632:72339] *** Process received signal ***
[fv-az1200-632:72339] Signal: Aborted (6)
[fv-az1200-632:72339] Signal code:  (-6)
[fv-az1200-632:72339] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fae83e42520]
[fv-az1200-632:72339] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fae83e969fc]
[fv-az1200-632:72339] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fae83e42476]
[fv-az1200-632:72339] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fae83e287f3]
[fv-az1200-632:72339] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fae842a4f26]
[fv-az1200-632:72339] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fae842b6d9c]
[fv-az1200-632:72339] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fae842b6e07]
[fv-az1200-632:72339] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fae842b70bb]
[fv-az1200-632:72339] [ 8] plumed_master(+0x12e7f)[0x55c046469e7f]
[fv-az1200-632:72339] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fae83e29d90]
[fv-az1200-632:72339] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fae83e29e40]
[fv-az1200-632:72339] [11] plumed_master(+0x13115)[0x55c04646a115]
[fv-az1200-632:72339] *** End of error message ***
</pre>
{% endraw %}
