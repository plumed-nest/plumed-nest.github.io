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
[fv-az1530-541:08991] *** Process received signal ***
[fv-az1530-541:08991] Signal: Aborted (6)
[fv-az1530-541:08991] Signal code:  (-6)
[fv-az1530-541:08991] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3cd0042520]
[fv-az1530-541:08991] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3cd00969fc]
[fv-az1530-541:08991] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3cd0042476]
[fv-az1530-541:08991] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3cd00287f3]
[fv-az1530-541:08991] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3cd04a2b9e]
[fv-az1530-541:08991] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3cd04ae20c]
[fv-az1530-541:08991] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3cd04ae277]
[fv-az1530-541:08991] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3cd04ae52b]
[fv-az1530-541:08991] [ 8] plumed(+0x12f48)[0x562840dc8f48]
[fv-az1530-541:08991] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3cd0029d90]
[fv-az1530-541:08991] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3cd0029e40]
[fv-az1530-541:08991] [11] plumed(+0x131e5)[0x562840dc91e5]
[fv-az1530-541:08991] *** End of error message ***
</pre>
{% endraw %}
