**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:137) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[fv-az1200-632:72331] *** Process received signal ***
[fv-az1200-632:72331] Signal: Aborted (6)
[fv-az1200-632:72331] Signal code:  (-6)
[fv-az1200-632:72331] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd451c42520]
[fv-az1200-632:72331] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd451c969fc]
[fv-az1200-632:72331] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd451c42476]
[fv-az1200-632:72331] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd451c287f3]
[fv-az1200-632:72331] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd4520a4f26]
[fv-az1200-632:72331] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd4520b6d9c]
[fv-az1200-632:72331] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd4520b6e07]
[fv-az1200-632:72331] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd4520b70bb]
[fv-az1200-632:72331] [ 8] plumed(+0x12f48)[0x55e466827f48]
[fv-az1200-632:72331] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd451c29d90]
[fv-az1200-632:72331] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd451c29e40]
[fv-az1200-632:72331] [11] plumed(+0x131e5)[0x55e4668281e5]
[fv-az1200-632:72331] *** End of error message ***
</pre>
{% endraw %}
