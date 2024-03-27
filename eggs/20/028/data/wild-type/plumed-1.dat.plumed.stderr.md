**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:137) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[fv-az1200-632:72300] *** Process received signal ***
[fv-az1200-632:72300] Signal: Aborted (6)
[fv-az1200-632:72300] Signal code:  (-6)
[fv-az1200-632:72300] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7a5ca42520]
[fv-az1200-632:72300] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7a5ca969fc]
[fv-az1200-632:72300] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7a5ca42476]
[fv-az1200-632:72300] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7a5ca287f3]
[fv-az1200-632:72300] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f7a5cea4f26]
[fv-az1200-632:72300] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f7a5ceb6d9c]
[fv-az1200-632:72300] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f7a5ceb6e07]
[fv-az1200-632:72300] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7a5ceb70bb]
[fv-az1200-632:72300] [ 8] plumed(+0x12f48)[0x55e6d445af48]
[fv-az1200-632:72300] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7a5ca29d90]
[fv-az1200-632:72300] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7a5ca29e40]
[fv-az1200-632:72300] [11] plumed(+0x131e5)[0x55e6d445b1e5]
[fv-az1200-632:72300] *** End of error message ***
</pre>
{% endraw %}
